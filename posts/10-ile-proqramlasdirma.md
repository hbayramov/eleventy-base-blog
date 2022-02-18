---
title: 10 İlə Proqramlaşdırma Öyrən
date: 2018-04-16
layout: layouts/post.njk
---

Niyə hamı tələsir?

Hər hansı bir kitab mağazasına getsəz, “24 saata Java Öyrən” kitabını görməklə yanaşı tükənmək bilməyən C, SQL, Ruby, Algorithms və s. kimi bir neçə saat və ya bir neçə günə öyrənmək təklifləri ilə dolu olan fərqli növ kitablarla da qarşılaşacaqsınız. Amazonda title: teach, yourself, hours, since: 2000 açar sözlərinin ətraflı axtarışı nəticəsində 512 növ belə kitab tapılıb. İlk onluqda olan kitabların doqquzu proqramlaşdırma kitabıdır (digəri mühasibata aiddir). Oxşar nəticəni “teach yourself” yerinə “learn” və ya “hours” yerinə “days” yazanda əldə etmək olar.

Nəticə olaraq belə görünür ki, ya insanlar proqramlaşdırmanı öyrənmək üçün çox tələsirlər, ya da proqramlaşdırmanı öyrənmək qalan hər şeydən inanılmaz dərəcədə asandır. Felleisen və digərləri bu trendə “How to Desing Programs” kitabında, “Pis proqramlaşdırma asandır. Gic adamlar bunu 21 günə öyrənə bilər, hətta onlar axmaq olsa belə.” şəklində tərif veriblər. Abtruse Goose-da məzəli şəkildə bu mövzuya toxunublar.

Gəlin “Teach Yourself C++ in 24 Hours” (özünə 24 saatda C++ öyrət) nə mənaya gələ biləcəyini analiz edək:

Özünə Öyrət: 24 saatda sənin bir neçə mühüm proqram yazmağa və onlarla birliktə əldə etdiyin uğurlu nəticələrin ya da uğursuz nəticələrinlə nesə öyrənməyə vaxtın olmayacaq. Sənin təcrübəli bir C++ proqramçısı ilə işləmək və C++ ətraf-mühitində olmağının nə olduğunu anlamaq üçün vaxtın olmayacaq. Qısacası, sənin çox şey öyrənmək üçün vaxtın olmayacaq. Kitab ancaq səthi tanışlıq haqda danışa bilər, dərindən anlamaq haqda yox. Alexander Pope-un dediyi kimi az öyrənmək təhlükəli şeydir.

C++: 24 saatda C++ ın sintaksisinin bəzilərini öyrənə bilərsən (əgər əvvəlcədən başqa bir dili bilirsənsə), amma sən dili necə istifadə etmək haqda çox şey öyrənə bilməyəcəksən. Qısacası, əgər Basic proqramçısısansa, sən C++ sintaksisi ilə Basic stilində proqram yazmağı öyrənə bilərsən, amma C++-ın nə üçün yaxşı ya da pis olduğunu yox. Bəs yaxşı məqsəd nədir? Alan Perlis bir dəfə dedi: “Əgər dil sənin proqramlaşdırma haqda düşünmənə tərzinə təsir etməyibsə, bilməyə dəyməz.” Bir səbəb bu ola bilər ki ,bəlli bir tapşırığı tamamlamaq üçün var olan bir alət (tool) ilə araüz (interface) etməniz lazım olduğu üçün C++ ın kiçik bir hissəsini (ya da böyük ehtimal, JavaScript və ya Processing kimi) öyrənməyə ehtiyacınız olsun. Ancaq o zaman sən necə proqlamlaşdırmağı öyrənmirsən; sən tapşırığı yerinə yetirməyi öyrənirsən.

24 saatda: Təəsüf ki, sonrakı hissədə də göstəriləcəyi kimi bu bəs deyil.

10 ilə Proqramlaşdırma Öyrən

Araşdırmacılar (Bloom (1985), Bryan & Harter (1989), Hayes (1989), Simmon & Chase (1973)) sübut ediblər ki, şahmat oynamaq, musiqi bəstələmək, teleqraf əməliyyatı, rəsm, pianino çalmaq, üzmək, tennis, nevropsixologiya və topologiya sahələrinin hər hansı birində ixtisaslaşmaq hardasa on il çəkir. Əsas məsələ məşvərətçi praktikadır: sadəcə bir şeyi təkrar-təkrar etməklə yox, hal hazırkı bacarığının kifayət etməyəcəyi bir tapşırıqla özünü çətinliyə salaraq, cəhd edərək, bunu edərkən və tamamladıqdan sonra öz performasını analiz edib və səhvləri düzəltmək ilə olmalıdır. Sonra təkrar və yenə də təkrar. Burada real bir qısa yolun olmadığı görsənir. Hətta Mozart, dünya səviyyəsində musiqi meydana çıxartmaq üçün 13 ilini qurban verib. Hansıki, dörd yaşında musiqi dahisi olub. Bir başqa deyişə görə Beatles musiqi qrupunun, səhnədə məşhur olmasının səbəbi kimi 1964-də Ed Sullivian şousunda görünməsi və bir nömrəli hitlərinin olması ilə əlaqələndirilirdi. Əslində onlar 1957-dən bu yana Liverpool və Hamburg-un kiçik klublarında ifa edirdilər və onlar erkən etapda kütləvi olaraq diqqət çəkdiyi zaman, ilk kritik uğurları 1967-ci ildə buraxılan Sgt.Peppers albomu idi.

Malcolm Gladwell bu fikri populyarlaştırdı, baxmayaraq ki, o, 10 il yox məhz 10.000 saat üzərinə təmərküzləşib. Henri Cartier-Bresson-un (1908–2004) digər bir metriki var: “Sənin çəkdiyin ilk 10,000 şəkil ən pis olanlardır.” (o, digital kameralarla bəzi insanların buna bir həftədə nail ola biləcəyini gözləmirdi). Həqiqi ixtisaslaşma bir ömür çəkə bilər: Samuel Johnson (1709–1784) deyib ki, hər hansı bir sahədə mütəxəssis olmaq yalnız bir ömür əmək nəticəsində əldə edilə bilər, bundan az qiymətə yox.” və Chauser (1340–1400) “həyat sənət öyrənmək üçün çox qısadır” deyərək, gileylənib. Hippokrat (c. 400BC) “ars longa, vita brevis” sözləri ilə tanınır, hansı ki “Ars longa, vita brevis, occasio praeceps, experimentum periculosum, iudicium difficile” sözlərinin bir hissəsidir. Azərbaycanca bunların mənası “həyat qısa, sənət uzun, fürsət qısa, təcrübə güvənilməz (ya da xain), mühakimə çətindir.” şəklindədir. Təbii ki, hər hansı biri ümumi cavab ola bilməz: bütün bacarıqlar da (proqramlaşdırma, şahmat oynamaq, dama oynamaq və musiqi ilə məşğul olmaq) mütəxəssis olmaq üçün eyni vaxt tələb etdiyini demək ağıllıca bir iş olmaz. Həmçinin bütün insanlar üçün də eyni vaxtı alacaq demək məntiqli deyil. Professor K. Anders Ericsson isə məsələni “Bir çox sahədə ən yüksək performansa çatmaq üçün ən bacarıqlı insanların belə nə qədər zamana ehtiyacı olduğu nəzərə çarpır. 10.000 saat sadəcə bizə həftənin 10 ilə 20 saatını təşkil edən illərdən danışdığımız anlamına gəlir. Bu da bəzi insanların iddia edəcəyi kimi talantlı insanların da üst səviyyə çıxmasına ehtiyac var. ” şəklində ortaya qoymuşdur.

Deməli proqramçı olmaq istəyirsən?

Bu da proqramlaşdırmada uğur üçün reseptim:

Proqramlaşdırma ilə maraqlanmağa köklənin və bunun üçün nəsə edin, ona görə ki bu əyləncəlidir. Sizə gələcəkdə 10 il/10000 saat vaxtınızı ayırmağa vadar edəcək qədər maraqlı olacağından əmin olun.

Proqram. Ən yaxşı öyrənmək üsulu tətbiq edərək öyrənməkdir. Biraz da texniki olaraq əsaslandırsaq, “Fərdi olaraq verimliliyin ən yüksək həddi uzun təcrübənin nəticəsi kimi avtomatik əldə edilmir, lakin performansın səviyyəsi daha yaxşısına nail olmaq üçün məqsədyönlü səylərin köməyi ilə arta bilər” və “ən faydalı öyrənmə fərdin özünə uyğun çətinlikdə yaxşı təyin edilmiş tapşırıq, öyrədici rəy və səhvlərin təkrarlanması,eləcə də düzəldilməsi imkanlarıdır.” Bu baxımdan Cognition in Practice: Mind, Mathematics, and Culture in Everyday Life maraqlı vəsaitdir.

Başqa proqramçılar ilə danışın; başqa proqramları oxuyun. Bu hər hansı kitabdan və ya təlim kursundan daha vacibdir.

Əgər istəyirsinizsə, universitetə (və ya hər hansı ali təhsil ocağında daha çox vaxt) 4 ilinizi ayırın. Bu sizə biliklər tələb edən bəzi işlər üçün qapı açacaq və həmin sahənin dərin biliklərini verəcək, lakin əgər təhsil ocaqlarını sevmirsinizsə, eyni təcrübəni (bir sıra fərqlərlə) özünüz və ya iş mühitində əldə edə bilərsiniz. İstənilən halda, yalnız kitabdan öyrənmək kifayət etməyəcək. The New Hacker’s Dictionary-nin müəllifi olan Eric Raymondun dediyi kimi, “Kompyuter elmləri təhsili kimisə ekspert proqramçı etmək iqtidarında deyil, bir halda ki, fırçaları və piqmentləri öyrənmək kimisə ekspert rəssam etmir”. İşə qəbul etdiyim ən yaxşı proqramçılardan birinin yalnız bir ali təhsili var; hansı ki, çoxlu nəhəng proqram meydana gətirib, özünün xəbərlər qrupu var və öz gecə klubunu almaq üçün kifayət qədər pul əldə etti.

Başqa proqramçılar ilə birlikdə proyektlər üzərində işləyin. Bəzi proyektlərdə ən yaxşı proqramçı olun; bəzilərində ən pisi olun. Ən yaxşısı olduğun vaxt proyekti idarə etmək üçün bacarıqlarını sınaqdan keçirirsən və öz görüşlərinlə başqalarını da həvəsləndirirsən. Ən pisi olduğun vaxt isə, usta proqramçıların nə etdiyini və onların nə etməyi sevmədiklərini öyrənirsən (çünki bunu onlar üçün etmək zərurətini yaradırlar).

Başqa proqramçılardan sonra da proyekt üzərində işləyin. Hər hansı başqası tərəfindən yazılan proqramı başa düşün. Başa düşməyə nəyin kömək etdiyini görün və müəllifi olduğu proqramçı ətrafınızda olmayanda problemi həll edin. Sizdən sonra proqramın üzərində işləyəcək olanlar üçün proqramı daha asan şəkildə necə quracağınız haqqında fikirləşin.

Ən azı 6 proqramlaşdırma dilini öyrənin. Buna bir dil sinif abstraksiyasını ifadə edən (Java və ya C++ kimi) , biri funksional abstraksiyanı ifadə edən (Lisp , MR və ya Haskell kimi),biri sintaktik abstraksiyanı ifadə edən (Lisp kimi), biri nəqli (declarative) xüsusiyyətləri dəstəkləyən (Prolog və C++ şablonları), və paralellilik ifadə edən bir dil daxildir (Clojure və ya Go).

Yadınızda saxlayın ki, “Kompyuter elmləri”-də “kompyuter” sözü vardır. Sizin kompyuterinizin komandanı icra etmə, yaddaşdan sözü oxuma (keş yaddaş itkisi ilə və ya itkisiz),diskdən ardıcıl sözləri oxuma, yeni yer üçün diskdə axtarma vaxtını bilin.

Normallaşdırmada iştirak etməyə cəhd edin. Bu ANSI C++ komitəsi ola bilər və ya bu sizin lokal kodlaşdırma üsulunun 2 və ya 4 boşluqlu abzaslama səviyyəsini müəyyən etmək ola bilər. Bütün hallarda, siz dildə başqa insanların nəyi sevdiyini,onların necə dərindən hiss etdiyini və hətta biraz da niyə belə hiss etdiyini öyrənirsiniz.

Mümkün olduğu qədər tez dil standartlaşdırması prosesinə uyğunlaşın.

Bunların hamısını düşünüb, kitabla öyrənməyin nə qədər gec olacağı sual işarəsi altındadır. Mənim ilk uşağım anadan olandan əvvəl, mən bütün Necə etməli kitablarını oxudum və hələdə özümü xam proqramçı kimi hiss edirdim. 30 ay sonra, ikinci uşağım yolda olanda, bilikləri yeniləmək üçün kitablara qayıtdım ? Xeyr, əvəzində, mənim üçün ekspertlər tərəfindən yazılan minlərlə səhifələrdən daha faydalı və təskinləşdirici hala düşən təcrübəmə etibar etdim.

Fred Brooks, öz No Silver Bullet adlı referatında böyük proqram təminatçılarını tapmaq üçün üç-hissəli plan müəyyən edib:

1. Sistemli olaraq mümkün qədər tez ən yaxşı proqramçıları müəyyən edin.
2. Karyera təlimçisinə gələcək inkişaf və karyera faylının diqqətlə saxlanılmasına cavabdeh olmasını tapşırın.
3. İnkişafda olan proqramçıların qarşılıqlı təsir və bir-birini stimullaşdırma imkanlarını yaradın.

Bununla fərz olunur ki, bəzi insanların artıq böyük proqramçı olmaq üçün vacib keyfiyyətləri artıq var; əsas iş onları buna düzgün kökləməkdir. Alan Perlis bunu daha müfəssəl müəyyənləşdirib : “Hamıya heykəltaraşlıq tədris oluna bilər: Michelangelo tədris olunmalı idi, necə olunmasın. Bu böyük proqramçılar ilə də belədir. Perlis deyir ki, böyük insanların onların təlimlərini üstələyən hansısa daxili keyfiyyəti var. Bəs bu keyfiyyət hardan gəlir ? Bu anadangəlmədir ? Yoxsa onlar bunu çalışmaqla inkişaf etdirir ? Auguste Gusteau (Ratatouille də baş aşpaz) dediyi kimi, “hər hansı şəxs bişirə bilər, ancaq qorxusuzlar böyük ola bilər.” Mən bunu daha çox bir nəfərin həyatının böyük qismini danışılmış təcrübəyə həsr etməsinə hazır olmaq kimi hesab edirəm. Lakin ola bilər ki, qorxusuzluq bunları cəmləşdirməyin bir yoludur. Yaxud Gusteau-nun rəyinə əsasən, Anton Ego, deyir : “Hamı böyük rəssam ola bilməz, lakin böyük rəssam hardansa gələ bilər”.

Belə ki, davam edin və Java/Ruby/Javascript/PHP kitabını alın; güman ki, siz bunlardan əlavə bəzilərini də istifadə edəcəksiniz. Lakin siz həyatınızı və ya proqramçı kimi həqiqi ümumi təcrübənizi 24 saatda yaxud 21 gündə dəyişməyəcəksiniz. Bəs davamlı inkişaf üçün 24 ay boyu çox çalışmaq barədə necə ? Yaxşı, indi siz harasa çatmaq üçün başlayırsınız..

Referanslar

Bloom, Benjamin (ed.) Developing Talent in Young People, Ballantine, 1985.
Brooks, Fred, No Silver Bullets, IEEE Computer, vol. 20, no. 4, 1987, p. 10–19.
Bryan, W.L. & Harter, N. “Studies on the telegraphic language: The acquisition of a hierarchy of habits. Psychology Review, 1899, 8, 345–375
Hayes, John R., Complete Problem Solver Lawrence Erlbaum, 1989.
Chase, William G. & Simon, Herbert A. “Perception in Chess” Cognitive Psychology, 1973, 4, 55–81.
Lave, Jean, Cognition in Practice: Mind, Mathematics, and Culture in Everyday Life, Cambridge University Press, 1988.
Cavablar
Adi PC-də fərqli əməliyyatların işləmə vaxtı:
adi instruksiya işlətmək — 1/1,000,000,000 sec = 1 nanosn
L1 keş yaddaşından məlumat gətirmək — 0.5 nanosn
branch misprediction (necə tərcümə edə biləcəyimi bilmədim) — 5 nanosn
L2 keş yaddaşından məlumat gətirmək — 7 nanosn
Mutex lock/unlock — 25 nanosn
əsas yaddaşdan (main memory) məlumat gətirmək — 100 nanosn
2K baytı 1Gbps şəbəkə üzərindən göndərmək — 20,000 nanosn
Yaddaşdan ardıcıl olaraq 1MB oxumaq — 250,000 nansn
yeni disk mövqeyindən (location) məlumat gətirmək (seek) — 8,000,000 nanosn
Diskdən ardıcılq olaraq 1M oxumaq — 20,000,000 nanosn
Amerikadan Avropaya paketi göndərib və geri almaq — 150 milli saniyə = 150,000,000 nanosn

Əlavə: Dil seçimi

Bəzi insanlar soruşur ki, ilk olaraq hansı proqramlaşdırma dilini öyrənməliyəm. Bunun bir cavabı yoxdur, amma bunları nəzərə al:
Dostlarını istifadə et. Məndən, “Hansı əməliyyat sistemi işlətməliyəm, Windows, Unix yoxsa Mac?” sualını soruşanda, mən əsasən cavab verirəm ki, “dostların hansından istifadə edirsə”. Çünki, dostlarından öyrənmə şansı, əməliyyat sistemləri və ya proqramlaşdırma dilləri arasındakı həqiqə fərqi aradan qaldıracaq. Həmdə gələcək dostlarını nəzərə al: əgər davam etsən, bir hissəsi olacağın proqramçılar cəmiyyətini. Sənin seçdiyin dilin geniş auditoriyası var, yoxsa, kiçik və ölməyə hazır olan? Cavab alabiləcəyin kitablar, veb saytları və onlayn forumları var? Bu forumlardakı insanları xoşlayırsan?

Sadə ol. C++ və Java, kodlarının işləmə vaxtının məhsuldarlığını artırmağa çalışan, geniş təcrübəli proqramçılar qrupu tərəfindən professional tətbiq üçün dizayn olunmuşdur. Nəticə olaraq, bu proqramlaşdırma dillərinin bu kimi hallar üçün dizayn olunmuş mürəkkəb hissələri vardır. Sənin bu mürəkkəbliyə ehtiyacın yoxdur. Sənə, köməksiz yeni proqramçı üçün asan öyrənməsi və yadda saxlaması üzrə dizayn olunmuş bir dil lazımdır.

Oyna. Pianinonu öyrənmək üçün hansı yolu üstün tutardız: normal olan, interaktiv yol (hər düyməyə basdığında hər notanı eşitmək), “batch” metodu, hansı ki, bütün mahnını bitirdiktən sonra notaları eşidirsən. Aydındır ki, interaktiv yol həm pianino həm də proqramlaşdırmanı öyrənməyi asanlaşdırır. Dilin üzərində interaktiv metod ilə dirən və istifadə et.

Bu meyarlara uyğun olaraq mənim ilk proqramlaşdırma dili üçün məsləhtim phyton və ya scheme olacaq. Digər bir seçim isə Javascriptdir. Ona görə yox ki, yeni öyrənənlər üçün çox gözəl dizayn olunub, ona görə ki, Khan Academy kimi onlayn olaraq çoxlu dərslər var. Əgər sənin yaşın tək rəqəmlidirsə, sən alice, squeak və ya blockly (yaşı çox olanlar üçün də maraqlı olabilər) üstün tuta bilərsən. Əsas şey odur ki, seçəsən və başlayasan.

Əlavə: Kitablar və Digər qaynaqlar

Bir neçə insan, hansı kitablardan və veb səhifələrindən öyrənmək haqda soruşdu. Mən təkrar edirəm, “təkcə kitabdan öyrənmək bəs olmayacaq”, amma aşağıdakıları məsləhət görə bilərəm:
Scheme: Structure and Interpretation of Computer Programs (Abelson & Sussman) bəlkə də kompüter elmlərinə giriş dərsi olaraq ən yaxşısıdır və proqramlaşdırmanı kompüter elmlərini anlamaq yolu ilə öyrədir. Bu kitabın onlayn dərsləri, həm də kitabın özü internetdə mövcuddur. Bu kitab çətin olduğuna görə, bəlkə də başqa bir yanaşma ilə uğurlu olabiləcək insanları özündən ayrı sala bilər.
Scheme: How to Design Programs (Felleisen et al.) proqramları zərif və funksional olaraq necə dizayn etmək üçün ən yaxşı kitablardandır.
Python: Python Programming: An Intro to CS (Zelle) mövzuya giriş üçün yaxşı kitabdır.
Python: Bir neçə onlayn dərslər Python.org-dan əldə edilə bilər.
Oz: Concepts, Techniques, and Models of Computer Programming (Van Roy & Haridi) bəziləri tərəfindən Abelson & Sussman-ın günümüzdəki davamçısı olaraq qəbul edilir. Bu böyük proqramlama fikirləri arasında , Abelson & Sussman-dan daha geniş və bəlkə də oxunması və təqib edilməsi daha asan olan bir turdur. Bu Oz proqramlaşdırma dilindən istifadə edir, hansı ki, çox tanınan deyil, amma digər dilləri öyrənmək üçün təməl təşkil edir.

Mənim əlavələrim

Bu məqalə Teach Yourself Programming in Ten Years başlığı altında Peter Norvig tərəfindən yazılmışdır. Mən və  Özal Əliyev bu yazının böyük bir hissəsini keçən il tərcümə etmişdik. Lakin mənim əsgərliyə getməmlə bu yazıda yarımçıq qaldı. Təxris olandan 2–3 gün sonra təkrar məqalənin qalan hissəsini tamamlamağa başladım. Bunu tərcümə etməmizdə ki, əsas səbəbimiz eyni problemlərin bizim proqramlaşdırmağa yeni başlayan gənclər arasındakı mövcudluğudur. Əsas məqsəd pul qazanmaq olduğuna görə, hamı tez bir zamanda professional proqramçı olmaq istəyir. Maddi çətinlik günümüz Azərbaycanında başa düşülən haldır. Ancaq, bir şeyi unutmamaq lazımdır ki, mütəxəssis olmaq qısa zamanda linux əməliyyat sistemi quraşdırıb, terminaldan npm paketləri yüklədiktən sonra iki-üç sətir javascript kodu yazaraq alınası iş deyil. Səbrli olun!

Məqalənin dili ağır və mənim azərbaycan dili qrammatika məlumatım möhtəşəm olduğuna görə tərcümədə səhvlərə yol verilmiş olabilər. Ona görə yazını diqqətli oxuyub, yazıda olan məna səhvlərini bildirməklə bizi çox sevindirmiş olarsız.

Mənə kömək göstərdiyi, dəstək verdiyi və səbr etdiyi üçün Özal Əliyev'ə təşəkkür edirəm.