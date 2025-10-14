Ad Soyad: Sıla Ağgül
Öğrenci No: 250541020

Hastane Randevu ve Tahlil Sistemi Pseudocode'u:

Başla
    TC kimlik numarası gir
    Eğer kimlik geçerliyse devam et
    Aksi halde “Geçersiz kimlik numarası” uyarısı ver ve bitir

    İşlem seç:
        1 - Randevu Al
        2 - Tahlil Sonuçlarını Gör

    Eğer işlem = 1 ise
        Poliklinik listesini göster
        Doktor seçimi yap
        Uygun saatleri listele
        Kullanıcı saat seçene kadar döngü oluştur
        Randevu bilgilerini onayla
        SMS ile onay mesajı gönder
    Değilse eğer işlem = 2 ise
        Tahlil var mı kontrol et
        Eğer tahlil yoksa “Tahlil bulunamadı” mesajı ver
        Eğer tahlil varsa
            Sonuç hazır mı kontrol et
            Eğer hazırsa sonucu göster
            “PDF indir” seçeneği sun
            Eğer hazır değilse “Sonuç bekleniyor” mesajı ver
    Son

    Kullanıcıya “Başka işlem yapmak ister misiniz?” diye sor
    Eğer evet derse işlemleri tekrarla
    Hayır derse işlemi bitir
Bitir


