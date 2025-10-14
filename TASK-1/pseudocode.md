Ad-Soyad: Sıla Ağgül
Öğrenci No: 250541020

ATM Para Çekme Sistemi Pseudocode'u:

Algoritma: ATM’den Para Çekme İşlemi

Başla
    Kart takılır
    "Lütfen PIN kodunuzu giriniz" mesajı göster
    hata_sayısı ← 0

    Tekrar PIN girişi yapılırken
        PIN doğru mu?
            Evet ise → İşleme devam et
            Hayır ise → hata_sayısı ← hata_sayısı + 1
                        Eğer hata_sayısı = 3 ise
                            "Kart bloke edildi" mesajı göster
                            Kartı iade et
                            Bitir
                        Değilse → "Yanlış PIN, tekrar deneyiniz" mesajı göster
        Döngü sonu (PIN doğrulanana kadar)

    İşlem menüsünü göster:
        1. Bakiye sorgula
        2. Para çek
        3. Çıkış

    Kullanıcı seçimi al
    Eğer seçim = 1 ise
        Bakiyeyi ekrana yaz
        Ana menüye dön
    Eğer seçim = 2 ise
        "Çekmek istediğiniz tutarı giriniz" mesajı göster
        tutar ← kullanıcı girişi

        Eğer tutar 20’nin katı değilse
            "Tutar 20 TL’nin katı olmalıdır" mesajı göster
            Ana menüye dön
        Eğer tutar > bakiye ise
            "Yetersiz bakiye" mesajı göster
            Ana menüye dön
        Eğer tutar + günlük_cekilen > günlük_limit ise
            "Günlük limit aşıldı" mesajı göster
            Ana menüye dön
        Aksi halde
            bakiye ← bakiye - tutar
            günlük_cekilen ← günlük_cekilen + tutar
            Para ver
            Fiş çıkar
            "Başka işlem yapmak ister misiniz?" sor
            Eğer cevap = Evet ise → Ana menüye dön
            Eğer cevap = Hayır ise → Kartı iade et, Bitir

    Eğer seçim = 3 ise
        Kartı iade et
        "İyi günler" mesajı göster
        Bitir
Bitir

