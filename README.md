🏥 İKÜ Sağlık - Doktor Randevu Sistemi
Bu proje, hastaların belirli uzmanlık alanlarındaki doktorlardan tarih ve saat seçerek randevu almalarını sağlayan Python tabanlı bir masaüstü uygulamasıdır. Tkinter GUI kütüphanesi kullanılarak geliştirilen yazılım, nesne yönelimli programlama (OOP) mantığıyla randevu çakışmalarını önleyen dinamik bir takvim yönetimi sunar.

✨ Özellikler
Doktor ve Uzmanlık Seçimi: Farklı branşlardaki doktorların listelenmesi ve seçilmesi.

İnteraktif Takvim: tkcalendar modülü ile istenen tarihin görsel olarak seçilebilmesi.

Dinamik Saat Yönetimi: Sadece seçilen doktorun ve seçilen tarihin müsait olan (dolu olmayan) saatlerinin listelenmesi.

Randevu Kayıt ve İptal: Alınan randevuların anlık olarak listelenmesi ve istendiğinde tek tıkla iptal edilerek ilgili saatin tekrar boşa çıkarılması.

Hata Yönetimi: Eksik bilgi girişi veya yanlış seçimlerde kullanıcıyı bilgilendiren uyarı mekanizmaları.

🛠 Kullanılan Teknolojiler
Dil: Python 3.x

Arayüz: Tkinter (Standart GUI)

Ek Bileşenler: tkcalendar (Tarih seçici arayüzü)

Mimari: Nesne Yönelimli Programlama (Hasta, Doktor ve Uygulama sınıfları)

🚀 Kurulum ve Çalıştırma
Gerekli kütüphaneyi yükleyin:


pip install tkcalendar
Depoyu klonlayın:

git clone https://github.com/kullaniciadi/doktor-randevu-sistemi.git
Uygulamayı başlatın:

python doktor_randevu.py
