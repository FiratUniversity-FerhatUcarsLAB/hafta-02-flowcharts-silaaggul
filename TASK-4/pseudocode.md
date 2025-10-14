Ad Soyad: Sıla Ağgül
Öğrenci No: 250541020

Üniversite Ders Kayıt Sistemi Pseudocode'u:

Başla
    Öğrenci numarası ve şifre gir
    Eğer giriş bilgileri doğruysa devam et
    Aksi halde “Hatalı giriş” mesajı göster ve bitir

    Ders listesini görüntüle
    Kullanıcı ders ekleme veya çıkarma işlemi yapana kadar döngü başlat

        Ders seçildiğinde:
            Kontenjan dolu mu kontrol et
            Eğer doluysa “Kontenjan dolu” mesajı ver, devam et
            Ön koşul dersi tamamlanmış mı kontrol et
            Eğer tamamlanmamışsa “Ön koşul eksik” mesajı ver, devam et
            Zaman çakışması var mı kontrol et
            Eğer varsa “Zaman çakışması” mesajı ver, devam et
            Toplam kredi 35’i geçiyor mu kontrol et
            Eğer geçiyorsa “Kredi limiti aşıldı” uyarısı ver, devam et
            Tüm koşullar uygunsa dersi ekle

        İstenirse ders çıkarma işlemi yapılabilir

    Ders ekleme/çıkarma döngüsü bitince:
        Eğer ortalama (GPA) < 2.5 ise danışman onayı iste
        Aksi halde doğrudan kayıt onayına geç

    Kayıt özetini göster
    Kullanıcıya “Kayıt onaylıyor musunuz?” sorusu yönelt
    Evetse kaydı tamamla, hayırsa işlemi iptal et
Bitir
