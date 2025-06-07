# NYP_PROJE_2
Nesneye yönelik programlama; Sudoku projesi

1. Proje Adı:
Web Tabanlı Basit Sudoku Oyunu

2. Projenin Amacı:
Bu projenin amacı, kullanıcıların web tarayıcısı üzerinden oynayabileceği basit bir Sudoku oyunu geliştirmektir. Oyun, hem kullanıcıya interaktif bir deneyim sunar hem de temel PHP, HTML ve CSS bilgileri ile web tabanlı, nesneye yönelik bir oyun nasıl geliştirilir sorusuna cevap niteliğindedir.

3. Kullanılan Teknolojiler:
HTML & CSS: Arayüz tasarımı için kullanılmıştır.

PHP: Sudoku tahtasının oluşturulması ve oyun mantığının arka planında çalışması için kullanılmıştır.


4. Projenin Genel Yapısı:
a) Sudoku.php:
Sudoku oyununun mantığını barındıran sınıf yapısını içerir.

Sudoku tahtası üretir ve çözüm kontrol mekanizmasını sağlar.

Boş hücreleri belirleyip kullanıcıya gösterilecek şekilde hazırlar.

b) game.php:
HTML çıktısı ve oyunun oynandığı ana sayfadır.

PHP dosyasındaki Sudoku sınıfı dahil edilerek oyun tahtası oluşturulur.

Kullanıcıların giriş yapabileceği hücreler belirlenmiştir.

"Kontrol Et" butonu ile çözümün doğruluğu kontrol edilir.

Yanlış girişler .invalid sınıfı ile görsel olarak uyarılır.

c) style.css:
9x9 Sudoku tahtasının stilini belirler.

Her 3x3 bloğun kalın sınırlarla ayrılmasını sağlar.

Kullanıcı tarafından düzenlenebilir hücreler ile sabit hücrelerin görsel olarak ayrılmasını sağlar.

Başarı ve hata mesajları için animasyonlar ve özel stiller içerir.

5. Oyun Akışı:
Kullanıcı sayfayı açtığında önceden belirlenmiş bazı hücreler doldurulmuş halde bir Sudoku tahtası görür.

Kullanıcı eksik hücreleri doldurarak “Kontrol Et” butonuna tıklar.

PHP dosyası, kullanıcının girişlerini kontrol eder ve:

Hatalı hücreleri kırmızı arka plan ile belirtir.

Sudoku doğru çözülmüşse “Tebrikler!” mesajı verir.

6. Kullanıcı Deneyimi:
Arayüz sade ve kullanıcı dostudur.

Hatalı girişlerde anında geri bildirim sağlar.

