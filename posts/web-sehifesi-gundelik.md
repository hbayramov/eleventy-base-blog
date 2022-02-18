---
title: Bir Web Səhifəsinin Gündəlik Həyatı
date: 2016-02-11
layout: layouts/post.njk
---

Təxminən bir neçə gün əvvəl technetə mən də qoşuldum. Bu saytın ən xoşuma gələn tərəfi öz dilimizdə qaynaq ehtiyacını qarşılamağa çalışmasıdır. Mən də öz saytımı bu məqsəd ilə açmıştım. Bu yazını yazma səbəbim isə techneti dəstəklədiyimi bildirmək üçündür. Yazını biraz daha maraqlı hala salmaq istədim və qərara gəldim ki, sizin evinizdə oturub www.technet.az yazanda arxa fonda nələr baş verdiyini sizə biraz da olsa izah edim.

![alt text](/img/web-gundelik/web-gundelik-1.png)

Yuxarıdakı şəkillər google.com-a daxil olanda nələr baş verdiyini başa salmağa çalışsa da biz onu technet.az kimi fikirləşək. (Dəyişdirəndə çox vaxt aparır sözün açığı) Deməli, yuxarıda gördüyünüz kimi məktəbdən internete bağlanmaq istənir. Sol tərəfdə DNS server, alt tərəfdə veb server və onları birbirinə bağlayan routerlar mövcuddur. Comcast Şəbəkəsi dediyi Amerikan kabel televiziya şəbəkəsidir. Sol tərəfdə məktəbin şəbəkəsi və alt tərəfdə isə technet-in şəbəkəsi olduğunu düşünək. İndi bunları tək-tək izah etməyə çalışacağam.

![alt text](/img/web-gundelik/web-gundelik-2.png)

Komputerin internet-ə qoşula bilməsi üçün öz IP adresini, birinic-hop router adresini və DNS serverin adresini əldə etməlidir. İç-içə kapsul halında DHCP UDP-də, UDP IP-də, IP Ethernet frame-də cəmlənərək göndərilir. Qarşı tərəfdə isə bu kapsul bir növ sıra ilə açılaraq DHCP request istəndiyi bəlli olur. DHCP server, DHCP ACK hazırlayaraq istifadəçinin IP adresini, birinci-hop router-ın IP adresini və DNS serverin ad və IP adresini göndərmiş olur. Artıq istifadəçimiz öz IP adresini, DNS serverinin adı ve IP adresini və birinci-hop router-ın IP adresini bilir.

![alt text](/img/web-gundelik/web-gundelik-3.png)

HTTP request göndərmədən əvvəl technet.az-ın IP adresini əldə etmək lazımdır. Beləliklə DNS sorğusu (query) yaradılaraq yenə kapsul halında iç-içə göndərilir. Hə bir də, bu haqda təfərrüatlı açıqlama verməyi düşünmürəm amma aranızda bəziləri bu istəkləri göndəriləndə router-ların MAC adresini necə öyrəndiyini bilmək istəyə bilər. Bunu ARP sorğusu ilə həyata keçirir. Bir az əvvəl məktəbdən internet-ə qoşulmaq üçün birinci-hop router-ın IP adresini öyrənmiş olsa da, MAC adresini bilmirdi. Çünki ilk sorğuda hədəf MAC adresi olduğu üçün switch tərəfindən bütün gedən bağlı portlara broadcast edilmişdi (həmçinin birinci-hop router-ın portuna).Bu hissəni başa düşüb-düşməməyiniz vacib deyil. Beləliklə istifadəçi birinci-hop router-ın MAC adresini də öyrənərək DNS sorğusunu göndərir.

![alt text](/img/web-gundelik/web-gundelik-4.png)

IP datagram məktəb şəbəkəsindən comcast şəbəkə içinə yönləndirilir. DNS server beləliklə istifadəçiyə technet.az-ın IP adresini göndərmiş olur.

![alt text](/img/web-gundelik/web-gundelik-5.png)

HTTP request göndərmək üçün istifadəçi ilk olaraq veb serverə TCP soket açır. TCP SYN segment-i veb serverə yönləndirilir. Veb server TCP SYNACK ilə cavab verərək qoşulmağın mümkün olduğunu vurğulayır. Nəhayət TCP əlaqəsi qurulur. Daha sonra HTTP request TCP soketi ilə göndərilir. HTTP request tutan IP datagram technet.az-a yönləndirilir. Veb server HTTP reply ilə cavabını (veb səhifəsi ilə birliktə) verir. HTTP reply-ı tutan IP datagram istifadəçiyə geri göndərilir.
Gördüyünüz kimi işlər o qədər də fikirləşdiyimiz qədər asan olmur. Əlimdən gəldiyi qədər sadələşdirmə edərək izah etməyə çalışdım. Əslində arxa fonda bundan 2 ya da 3 qat daha çox əməliyyat olur desək bəlkə az demiş olarıq. Çünki hələ biz heç switch-lərdən, router-ların işləmə alqoritmasından, TCP və UDP-nin işləmə alqoritmasından, ARP-dan, HTTP növlərindən və s. heç danışmadıq.

Referans: 
[Computer Networking: A Top-Down Approach (6th Edition)](https://www.amazon.com/Computer-Networking-Top-Down-Approach-Edition/dp/0132856204)

