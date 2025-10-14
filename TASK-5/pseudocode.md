Ad Soyad: Sıla Ağgül
Öğrenci No: 250541020

 Akıllı Ev Güvenlik Sistemi Pseudocode'u

Başla
    Sistem aktif mi kontrol et
    Eğer sistem pasifse “Sistem devre dışı” mesajı göster ve bitir
    Eğer aktifse sensör okuma döngüsüne gir

    Sürekli döngü başlat
        Hareket sensörü kontrol et
        Kapı/pencere sensörlerini kontrol et

        Eğer hareket veya kapı/pencere ihlali varsa
            Kamera aktivasyonu başlat
            Ev sahibi evde mi kontrol et (yanlış alarm kontrolü)
            Eğer ev sahibi evdeyse “Yanlış alarm” mesajı göster ve döngüye dön
            Eğer ev sahibi evde değilse
                Alarm seviyesini belirle:
                    Düşük (tek sensör)
                    Orta (iki sensör)
                    Yüksek (birden fazla sensör ve hareket)
                Alarmı etkinleştir
                Bildirim gönder (SMS + Mobil Uygulama + E-posta)
        Aksi halde “Her şey normal” olarak devam et

        Bir süre bekle
        Alarm sıfırla veya devam ettir (koşul)
    Döngü sonu (sürekli çalışır)
Bitir
