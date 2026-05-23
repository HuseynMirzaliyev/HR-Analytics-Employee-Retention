# HR-Analytics-Employee-Retention
Data əsaslı insan resursları analitikası: Şirkətdaxili Attrition, performans və istedadların idarə edilməsi analizi.

# 👥 İnsan Resursları Data Analizi və Dashboard Layihəsi

## 📌 Layihə Haqqında
Bu layihədə 1470 əməkdaşın demoqrafik göstəriciləri, iş məmnuniyyəti, əməkhaqqı və karyera inkişafı məlumatları analiz edilərək Attrition səbəbləri araşdırılmış və istedadların idarə edilməsi strategiyası formalaşdırılmışdır.

**Məqsəd:**
* Attrition təsir edən kritik faktorları tapmaq
* Şöbələr və demoqrafik qruplar üzrə iş məmnuniyyəti ölçmək
* Performans və loyallıq əlaqəsini data əsasında optimallaşdırmaq

## 🛠️ İstifadə Olunmuş Alətlər və Metodlar
* **Excel Funksiyaları və Data Cleaning:** Şirkətdaxili HR verilənlər bazasının təmizlənməsi, qruplaşdırılması və boş xanaların nizamlanması.
* **Qabaqcıl Vizualizasiya:** Çoxölçülü analizlər üçün Radar Chart, Scatter Plot, Klaster qrafikləri və Treemap vizuallarının tətbiqi.
* **Strukturlaşdırılmış Dashboard:** Rəhbərlik üçün 3 fərqli baxış bucağı:
  * **Executive Overview:** Ümumi şirkət profili və demoqrafik vəziyyət.
  * **Attrition Analysis:** Attrition riskləri və itkisinin səbəbləri.
  * **Talent Management:** Performans, təlim və karyera durğunluğunun analizi.

## 📊 Dashboard-dan Görüntü
Layihənin tam interaktiv dashboard görüntüləri aşağıdakı kimidir:

<p align="center">
  <img src="https://github.com/user-attachments/assets/3a4bab13-e9fc-4e5c-bfbd-653d34245821" width="32%"/>
  <img src="https://github.com/user-attachments/assets/8da0dc43-ab4e-4158-932b-cd866b56b235" width="32%"/>
  <img src="https://github.com/user-attachments/assets/73425f5a-301c-4a82-a2c9-89cbf21bbf1c" width="32%"/>
</p>

---

### DASHBOARD 1: Executive Overview 

#### 📉 İş Məmnuniyyəti və HR Departamentinin Paradoksu
<p align="center">
<img src="https://github.com/user-attachments/assets/c6d4cc6c-b7e3-4cdd-9ae5-9c7e96dc3474" width="100%"/>
<img src="https://github.com/user-attachments/assets/a4bf67d1-28c8-4e83-8528-1beb6fc72ac6" width="40%"/>
<img src="https://github.com/user-attachments/assets/bbbff164-858b-4bc5-b7bd-d5d178641d73" width="45%"/>

* **Insight:** Şirkətin ümumi Attrition göstəricisi 16% civarında olsa da, *Job Satisfaction* balı **2.7 / 4** həddindədir. Ən kritik vəziyyət isə məhz **Human Resources (2.6)** şöbəsindədir. Şirkətin loyallıq strategiyasını quran departamentin öz daxilində motivasiya böhranı yaşanır.
* **Action Plan:** HR departamenti ilə təcili görüşlər təşkil edilməli, iş yükü və resurs çatışmazlığı problemləri aydınlaşdırılmalıdır. HR komandasının daxili məmnuniyyəti artırılmalıdır ki, digər 1400+ işçini effektiv idarə edə bilsinlər.

#### ⚖️ Maaş Bərabərliyi vs. Gender Balansı
<p align="center">
<img src="https://github.com/user-attachments/assets/49ead1a5-0ffc-4ecc-bc75-3e5ae13fc24f" width="40%"/>
<img src="https://github.com/user-attachments/assets/5989554e-d545-4061-9bd1-f45b3d26d4a4" width="40%"/>

* **Insight:** Şirkətdə kişi işçilərin sayı (882) qadın işçilərdən (588) əhəmiyyətli dərəcədə çoxdur (60% vs 40%). Müsbət tərəfi odur ki, bütün karyera səviyyələrində (Junior-dan Executive-ə qədər) kişi və qadınların maaşları demək olar ki, tam bərabərdir (Maaş bərabərliyi qorunub).
* **Action Plan:** Mövzu maaş disbalansı deyil, işəqəbul hədəfləridir. Xüsusilə rəhbər pozisiyalara namizəd seçimində gender balansını qorumaq üçün  işəqəbul siyasətinə diqqət yetirilməlidir.

#### 🎓 Mentorluq Potensialı (Age vs. Tenure)
<p align="center">
<img src="https://github.com/user-attachments/assets/4a0cb459-50f8-41f0-a367-535e1b5ebbef" width="40%"/>

* **Insight:** Şirkətdə ən yüksək orta staj **46-55 yaş qrupuna (10 il)** məxsusdur. Gənc nəsildə (18-25 yaş) isə bu göstərici 4 ildir. Şirkətdə güclü və loyal bir praktiki yaddaş mövcuddur.
* **Action Plan:** Bu kritik təcrübəni şirkət daxilində saxlamaq və gənclərin adaptasiyasını sürətləndirmək üçün **Təcrübə Mübadiləsi proqramları** qurulmalı, 46-55 yaşlı işçilər gənc kadrlara rəsmi mentor təyin edilməlidir.

---

### DASHBOARD 2: Attrition (Kadr Axımı Analizi)

#### 🔴 R&D Şöbəsində İtki və Overtime (Artıq İş Saatları) Təzyiqi
<img src="https://github.com/user-attachments/assets/cd1fd675-d40e-4599-96b2-5a3d586b5b9b" width="100%"/>

* **Insight:** 237 nəfərlik ümumi işdənçıxma göstəricisində ən yüksək riskli sahə **Research & Development** şöbəsidir. KPI kartlarında görünür ki, **Overtime  Attrition səbəbinə 20% birbaşa təsir göstərir**. **Research & Development** komandası tükənmə (Burnout) mərhələsindədir.
* **Action Plan:** **Research & Development** ilə görüş keçirilməlidir. Artıq iş saatları tənzimlənməli, əlavə işləyən işçilər üçün icazə günləri və ya maliyyə stimulları dərhal aktivləşdirilməlidir.

#### 🚗 Məsafə Baryeri və Lokal Churn Riski
<p align="center">
<img src="https://github.com/user-attachments/assets/ef23a06b-99f0-436b-be72-0cea50554506" width="50%" />

* **Insight:** *Distance vs. Attrition* matrisinə əsasən, ev-iş məsafəsi 11 km-dən çox olan HR (43%-50%) və Sales (26%-27%) işçilərində axım faizi yüksəkdir. Yol məsafəsi uzandıqca işçilərin şirkəti tərk etmə ehtimalı artır.
* **Action Plan:** İş yerindən 11 km-dən uzaq məsafədə yaşayan komanda üzvləri üçün **Hibrid və ya Remote iş rejiminin** tətbiqi, yaxud regional servis/nəqliyyat kompensasiyası paketləri tətbiq olunmalıdır.

#### 💸 Giriş Səviyyəsində Maaş Qeyri-kafi̇li̇yi̇
<p align="center">
<img src="https://github.com/user-attachments/assets/00cdd056-dd32-4be4-9b5f-c9ff384075c5" width="50%"/>

* **Insight:** İşdən çıxanların böyük əksəriyyəti aylıq gəliri **5,000-dən aşağı olan (163 nəfər)** gənc mütəxəssislərdir. Yüksək maaş qruplarında (10k+) işdən çıxma halları demək olar ki, sıfıra enir. İtki əsasən aşağı maaşlı seqmentdə baş verir.
* **Action Plan:** Maaşı 5K altı olan giriş və orta səviyyəli pozisiyalar üçün bazar araşdırması (Salary Benchmarking) edilməli, rəqabətədavamlı minimum baza əməkhaqqı və performansa bağlı rüblük bonus sistemi tətbiq edilməlidir.

#### 📉 Manager Stability Index
<p align="center">
<img src="https://github.com/user-attachments/assets/7cfe3bda-103b-4c5a-aeda-c54933c15ca6" width="50%"/>

* **Insight:** *Manager Stability Index* qrafiki göstərir ki, işçilərin mövcud menecerləri ilə keçirdikləri illər üzrə Attrition dərəcəsi kəskin dalğalanır. Xüsusilə yeni təyin olunmuş və ya ilk ilində olan menecerlərin komandalarında işdənçıxma nisbəti **30%-dən çoxdur**. Ən dramatik siqnal isə **14-cü ildə** baş verir: Bu nöqtədə kadr axımı **40%-ə çataraq** pik edir. 
* **Action Plan:** İlk ilində olan menecerlər üçün liderlik vərdişləri və emosional intellekt təlimləri məcburi edilməlidir. 14-cü ilə çatmış kritik menecer strukturları isə təcili HR tərəfindən yoxlanılmalı və gərəkli təlimlər verilməlidir. 

#### ⏳ Karyera Durğunluğu və "Tenure vs. Promotion Lag" Anomaliyası
<p align="center">
<img src="https://github.com/user-attachments/assets/6ef58e3f-b16e-4a6c-a1df-26e2990c71ff" width="50%"/>

#### ⏳ Karyera Durğunluğu və "Tenure vs. Promotion Lag" Korrelyasiyası (Scatter Plot Analizi)
* **Insight:** *Tenure vs. Promotion Lag* scatter plot qrafikində, horizontal ox işçinin şirkətdəki ümumi stajını (**Avg Tenure**), şaquli ox isə sonuncu vəzifə artımından keçən vaxtı (**Promotion Lag**) tənzimləyir. Qrafikin yuxarı sağ kvadrantında yer alan uzaq nöqtələr şirkətdə həm ümumi stajı çox olan, həm də illərdir vəzifə artımı almayan (məsələn, 10-15+ il stajı olub, hələ də promotion gözləyən) kritik kütləni vizuallaşdırır. Sol aşağı kvadrantdakı sıxlaşma isə stajı az olan yeni işçilərin (0-3 il) qısa müddətdə dərhal vəzifə artımı gözlədiyini və bu reallaşmadıqda yaranan narazılığın erkən işdənçıxmalara (Early Attrition) birbaşa təkan verdiyini göstərir.
* **Action Plan:** X oxunda stajı 7 ildən (şirkət ortalamasından) çox olub, Y oxunda vizual olaraq yuxarıda qalan tıxandıqca risk yaradan işçilər üçün **"Sürətləndirilmiş Karyera Keçidi** yaradılmalıdır. Eyni zamanda, sol tərəfdəki gənc kadrların ilk 2 il daxilində inkişaf perspektivini şəffaf görünməsi üçün rüblük və ya daxili sertifikasiya əsaslı tənzimləmələr edilməlidir.

---

### DASHBOARD 3: Talent Management (İstedadların İdarə Edilməsi)

#### 🧗 "High Performer" Riski və Təlim Çatışmazlığı
<p align="center">
<img src="https://github.com/user-attachments/assets/b92046ca-b2e4-4ae0-80a5-1f1bfc0f12d1" width="50%"/>

* **Insight:** Şirkətdə 226 nəfər yüksək performanslı kadr var və ümumi performans 3.2 / 4-dür. Lakin **orta təlim saatının cəmi 2.8 saat olması** bu yüksək performansın gələcəkdə düşəcəyinə və ya bu sadiq işçilərin inkişaf edə bilmədiyi üçün işdən çıxacağına işarə edir.
* **Action Plan:** Bu 226 ulduz işçi üçün xüsusi **"Talent Retention Program"** hazırlanmalıdır. Hər birinə illik min. 40 saatlıq təlim büdcəsi ayrılmalıdır.

#### 📊 Maaş Artımı = Maksimum Performans Korrelyasiyası
<p align="center">
<img src="https://github.com/user-attachments/assets/f640e9ad-5dc3-4979-906a-43c57967e7ef" width="50%" />

* **Insight:** *Performance vs. Salary Hike* klaster qrafiki göstərir ki, maaş artım faizi 10%-15% arasında olan işçilərin performansı 3 bal səviyyəsində donub qalıb. Maaş artımı 20%-25% olan qrupda isə performans birbaşa maksimuma (4 bala) yüksəlib.
* **Action Plan:** Performansi 3 olan və "yaxşı" işləyən kütləni "mükəmməl" (4 bala) səviyyəsinə qaldırmaq üçün performansa bağlı düz mütənasib Maaş Artımı tətbiq edilməlidir. Yüksək nəticə dərhal yüksək maaş artımı ilə mükafatlandırılmalıdır.

#### 🕸️ Təşkilati Mədəniyyət Aşınması (Radar Chart Analizi)
<p align="center">
<img src="https://github.com/user-attachments/assets/e782c190-98a7-4f84-91f2-c9ca72391d0f" width="50%" />

* **Insight:** *Department Satisfaction Profile* göstərir ki, HR departamenti həm Relationship (Münasibətlər), həm Environment (Ətraf mühit), həm də daxili idarəetmədə ən kiçik sahəni tutur. Şirkətin daxili mədəniyyətini qorumalı olan orqan struktur daxilində tamamilə sıxılıb.
* **Action Plan:** HR-ın daxili vəiyyətini yaxşılaşdırmaq və departamentlərarası münasibətləri sağlamlaşdırmaq üçün kənar təşkilati konsultant cəlb edilməli və daxili təlimlər başladılmalıdır.

#### 🧘 İş-Həyat Balansının Performansa Birbaşa Təsiri
<p align="center">
<img src="https://github.com/user-attachments/assets/61fe460a-83d6-4629-9215-561c9d85655f" width="50%"  />

* **Insight:** *Work-Life Balance* səviyyəsi "Good" və ya "Excellent" olan işçilərin işə cəlb olunma (Involvement) səviyyəsi pik həddədir (516 nəfər). Balans "Poor" (Pis) olduqda isə işə bağlılıq kəskin şəkildə düşür (cəmi 51 nəfər). 
* **Action Plan:** Şirkətdə rəsmi olaraq **İş saatından sonra əlaqəni kəsmək hüququ** qaydası tətbiq olunmalıdır. Həftəsonları və ya axşam saat 19:00-dan sonra daxili korporativ yazışmalar və tapşırıq verilməsi məhdudlaşdırılmalıdır.

#### 🛑 15 İllik Karyera Tıxanması (Promotion Stagnation)
<p align="center">
<img src="https://github.com/user-attachments/assets/1ba5db99-5078-4f11-ad57-9fa6331ad90f" width="50%"/>

* **Insight:** *Promotion Stagnation* qrafikində xüsusilə 11 və 15-ci xidmət illərində olan bəzi işçilərin 15 ildən çoxdur eyni vəzifədə qaldığı (qırmızı və narıncı zonalar) görünür. Bu durğunluq (Stagnation) həm motivasiyanı öldürür, həm də altdan gələn gənc kadrların yüksəlməsinə mane olur.
* **Action Plan:** Uzun müddət eyni vəzifədə qalan işçilər üçün layihə əsaslı liderlik və ya yeni açılan regional ofislərdə idarəetmə rolları təklif edilərək karyera yolları yenidən aktivləşdirilməlidir.
