---
title: Linux Ram İstifadəsi
date: 2016-02-07
layout: layouts/post.njk
---

Ghost platformuna keçəndə ən çox qarşılaşdığım problemlərdən biri də linux-un niyə ram-ı heç bir proses olmadığı halda çox istifadə etdiyi idi. Məsələn linux sistemində free-m əmr vasitəsi ilə nə qədər yaddaşın istifadə olunduğuna baxıla bilər.

![alt text](/img/linux-ram.png)

Yuxarıdakı şəkildə boş (free) olaraq 54 MB göstərsə də, əslində boş olan hissə mavi qutuda yer alan 306 MB-lıq hissədir.
Əslində Linux istifadə olunmayan yaddaşı disk keşi deyilən hissə üçün prosesləri daha tez işlədə bilsin deyə borc alır. Əgər sizin proqramların daha çox yaddaşa ehtiyacı olsa disk keşi borc aldığı hissəni geri qaytarır. Yəni əslində o borc alınan hissə programlar tərəfindən istifadə olunmayan hissədir. Əgər kompüterdə olan hər hansı bir proqramın yaddaşa ehtiyacı olsa disk keşi aldığı hissəni geri verir və bu o deməkdir ki, sizin ram-ın tamamı istifadə olunmur. Sadəcə olaraq ehtiyac üçün disk keş tərəfindən borc alınıb.
Disk keş dayandırıla bilməz. Əsasən insanların çoxu disk keşin ram-ı çox istifadə etdiyini və ram-da digər proqramlara yer ayrılmadığını fikirləşir. Amma disk keş proqramların tamamı ilə daha sürətli və axıcı işləməsi üçün yaddaşdan istifadə olunmayan hissəni borc alır. Yəni disk keşi dayandırmağın heç bir mənası yoxdur.

Referanslar: 
[Linux Ate My Ram](https://www.linuxatemyram.com)
[Linux Disk keş üzərində təcrübə](https://www.linuxatemyram.com/play.html)