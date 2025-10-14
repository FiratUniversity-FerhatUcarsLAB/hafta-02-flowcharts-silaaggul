Ad Soyad: Sıla Ağgül
Öğrenci No:250541020

Online Alışveriş¸Sepet Sistemi Pseudocode'u:

Başla
    Kullanıcıdan giriş bilgilerini iste
    Eğer kullanıcı adı veya şifre yanlışsa
        Hata mesajı göster
        Yeniden giriş yapmasını iste
    Aksi halde
        Ana menüye yönlendir

    Ürün kategorilerini listele
    Kullanıcı kategori seçene kadar bekle (döngü)
    Seçilen kategorideki ürünleri göster

    Kullanıcı ürün seçtiğinde
        Eğer ürün stokta varsa
            Ürünü sepete ekle
            "Ürün sepete eklendi" mesajı göster
        Aksi halde
            "Stokta yok" uyarısı ver
            Başka ürün seçimi için kategoriye dön

    Kullanıcı dilerse sepeti görüntüleyebilir (döngü)
    Sepet üzerinde ürün çıkarma veya miktar değiştirme yapılabilir

    Eğer kullanıcı indirim kodu girmek isterse
        Kodu al ve doğrula
        Geçerli ise indirimi uygula
        Geçersiz ise uyarı ver

    Sepet toplam tutarını hesapla
    Eğer toplam 50 TL’nin altındaysa
        "Minimum alışveriş tutarı 50 TL olmalıdır" uyarısı ver
        Ürün ekleme adımına dön
    Eğer toplam 200 TL veya üzerindeyse
        Kargo ücretsiz
    Aksi halde
        20 TL kargo ücreti ekle

    Kullanıcıdan ödeme yöntemi seçmesini iste
    Eğer kredi kartı seçilirse kart bilgilerini al
    Eğer havale seçilirse banka bilgilerini göster
    Eğer işlem başarılıysa
        "Sipariş onaylandı" mesajı göster
    Aksi halde
        "Ödeme başarısız, tekrar deneyin" uyarısı ver

Bitir

