# patika_oop
**ÖDEV1 - ÜNİVERSİTE YÖNETİM SİSTEMİ**
* Üniversiteye ait sınıflıklar, çalışma ofisleri ve departmanlar vardır.
* Departmanlara ait ofisler vardır.
* Üniversiteye ait çalışanlar vardır. Bu çalışanlar profesör veya memur olabilir.
* Her çalışan bir ofiste çalışır.
* Not : Sınıflara ait nitelik ve davranışların belirtilmesine gerek yoktur.

![UniversityManagementSystem drawio](https://user-images.githubusercontent.com/88900722/132870869-6c0cac9f-9619-4bed-844c-66f80cda6ff7.png)



**********

**ÖDEV2 - HAYVANAT BAHÇESİ**
* Bir hayvanat bahçesindeki hayvanlar hakkındaki bilgileri takip etmek için bir sistem tasarlıyorsunuz.
* Hayvanlar:
    * Atlar (atlar, zebralar, eşekler vb.),
    * Kedigiller (kaplanlar, aslanlar vb.),
    * Kemirgenler (sıçanlar, kunduzlar vb.) gibi gruplardaki türlerle karakterize edilir.
* Hayvanlar hakkında depolanan bilgilerin çoğu tüm gruplamalar için aynıdır.
    * tür adı, ağırlığı, yaşı vb.
* Sistem ayrıca her hayvan için belirli ilaçların dozajını alabilmeli => getDosage ()
* Sistem Yem verme zamanlarını hesaplayabilmelidir => getFeedSchedule ()
* Sistemin bu işlevleri yerine getirme mantığı, her gruplama için farklı olacaktır. Örneğin, atlar için yem verme algoritması farklı olup, kaplanlar için farklı olacaktır.
* Polimorfizm modelini kullanarak, yukarıda açıklanan durumu ele almak için bir sınıf diyagramı tasarlayın.

![HayvanatBahçesi drawio](https://user-images.githubusercontent.com/88900722/132881661-1cd4820b-ccda-4833-bb08-8d56774f28e7.png)



**********

**ÖDEV3 - UÇUŞ YÖNETİM SİSTEMİ**
* Uçuşların ve pilotların yönetimi için bir sistem tasarlayın.
* Hava yolu şirketleri uçuşları gerçekleştirir. Her hava yolunun bir kimliği vardır.
* Hava yolu şirketi, farklı tipteki uçaklara sahiptir.
* Uçaklar çalışır veya onarım durumunda olabilir.
* Her uçuşun benzersiz kimliği, kalkacağı ve ineceği havaalanı, kalkış ve iniş saatleri vardır.
* Her uçuşun bir pilotu ve yardımcı pilotu vardır ve uçağı kullanırlar.
* Havaalanlarının benzersiz kimlikleri ve isimleri vardır.
* Hava yolu şirketlerinin pilotları vardır ve her pilotun bir deneyim seviyesi mevcuttur.
* Bir uçak tipi, belirli sayıda pilota ihtiyaç duyabilir.

![HAVA drawio](https://user-images.githubusercontent.com/88900722/132890385-52cb17b9-d5ef-4cae-a553-43b64e3bd33b.png)



**********

**ÖDEV4 - ONLİNE FİLM SİTESİ**
* Online film satan veya kiralayan uygulamanın sistemini tasarlayın.
* Uygulamada filmler listelenebilir, sıralanabilir ve kullanıcılar uygulamaya abone olabilir.
* Kullanıcılar abonelik için sistem üzerinden kredi satın alır.
* Sadece abone olan kullanıcılar, kredileri ile film kiralayabilir ve kiraladığı filmin kredi bedeli kadar hesabından düşülür.
* Normal kullanıcılar ve aboneler film satın alabilirler.
* Eğer film mevcut değil ise talep edilebilir.

