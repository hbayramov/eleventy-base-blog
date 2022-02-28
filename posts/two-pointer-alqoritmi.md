---
title: two-pointer alqoritmi
date: 2018-11-11
layout: layouts/post.njk
---

Deməli, bugün danışacağımız alqoritm spesifik bir sahəyə məxsus deyil. Yəni, bəzilərinin dediyi kimi, ''cs oxuyuram improper integral nəyimə lazım olacaq?'', ''iş həyatında bunlar lazım olmur'' və s. kimi bir şey deyil. Əslində gündəlik iş həyatında bu tip problemlərlə üzləşə bilirik.
Məsələn, sizə sıralanmış array verilib. Bu da array'imiz:

int[] A = new int[]{10, 20, 35, 50, 75, 80};

Birdə, X dəyəri verilir və verilən arraydə iki ədədin toplamının bu ədədə bərabər olan dəyərlərin olub-olmamasının tapılması istənir.

İlk yazacağımız kod:

```java
public class Main {

    public static void main(String[] args) {
        System.out.println(Main.findPairs(new int[]{10, 20, 35, 50, 75, 80}, 70));
    }

    public static Boolean findPairs(int[] array, int X) {

        for(int i=0; i < array.length; ++i) {
            for(int j=i+1; j < array.length; ++j) {
                if(array[i] + array[j] == X) // tapdıq
                    return true;

                if(array[i] + array[j] > X) // sıralanmış olduğuna görə mənası yoxdur
                    break;
            }
        }

        return false; // tapılmadı
    }
}
```

İlk ağlımıza gələn həll yolu hamıda aşağı-yuxarı belə olur. Yəni mən arrayin bir dəyərini alıb bütün digər dəyərləri ilə toplayaraq, X ədədinə bərabər olub olmamasını yoxlayıram. Bu alqoritmin time complexitysi (cavabı tapmaq üçün sərf etdiyi vaxt) O(n^2) olacaq.

Lakin, biz arrayin sıralanmış olduğundan istifadə edərək ilk və son indeksini tutmaqla, başdan və sondan ədədləri toplayıb, verilən ədədə bərabər olub-olmamasını yoxlaya bilərik. Əgər toplam verilən ədəddən böyükdürsə, sondan bir azaldırıq (çünki, arrayimiz sıralanıb) yox əgər kiçikdirsə əvvələ bir əlavə edirik. Kod daha yaxşı izah edər.

```java
public class Main {

    public static void main(String[] args) {
        System.out.println(Main.findPairs(new int[]{10, 20, 35, 50, 75, 80}, 70));
    }

    public static Boolean findPairs(int[] array, int X) {
        int i = 0;
        int j = array.length-1;

        while (i < j) {
            if(array[i] + array[j] == X) return true; // tapdıq

            if(array[i] + array[j] > X) --j;  // əgər toplam X ədədindən böyükdürsə j-ni azalt
            else ++i; // yox əgər kiçikdirsə i-ni artır
        }

        return false; // tapılmadı
    }
}
```

Deməli, two-pointer alqoritmində istifadə edərək bir loopdan canımızı qurtara bildik. İndi isə, time complexityimiz O(n) oldu.

Bu tip sıralanmış arraylər iş həyatınızda belə asanlıqla qarşınıza çıxa bilər. Ona görə də, real həyatda bu nə işimə yarayacaq deməyin. Güya real həyatda nə kod yazırıq ki.

Gəlin başqa bir misala keçək. Daha maraqlı. Məsələn, sizə n ədədli array verilir. Bu arraydəki ədələrin hər biri x üzərində (2D olan x) hər birinin bir vertikal olaraq yan-yana sıralandığını düşünün (ədədlərin sıralanması yox). Məsələn,

[1,8,6,2,5,4,8,3,7]

![alt text](/img/two-pointer.jpeg)

Verilən ədələr arasında ən çox su tutan konteynerin (iki nöqtə arasındakı) sahəsini tapın. Yuxarıdakı misalda 8 və 7 arasındakı uzaqlıq 7-dir (yəni iki qırmızı xətti 7 boşluq ayırır). Deməli, bunun sahəsi 7*min(8,7) olaraq hesablananda, cavab 49 olacaq. Bu da bizə ən böyük sahəni verir. Bu sualı two-pointer alqoritmindən istifadə edərək edin. Sualın cavabını rahatlıqla googledan tapa bilərsiniz. Lakin, əvvəl özünüz etməyə çalışın.

Bu [linkdən](https://leetcode.com/tag/two-pointers/) suallara baxa bilərsiniz.