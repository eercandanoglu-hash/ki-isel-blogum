# Kişisel Blogum

Düşüncelerimi, ilgi alanlarımı ve hayata bakış açımı paylaştığım basit, tek sayfalık kişisel blog/web sitesi. Saf HTML ve CSS ile yazılmıştır; herhangi bir çatı (framework) veya derleme adımı gerektirmez.

## İçerik

- **Giriş / Hero:** Siteye hoş geldiniz bölümü ve kısa tanıtım yazısı.
- **Günlük yazı:** Sabah yolculuğu ve okuma üzerine kişisel bir deneme metni.
- **Görseller:** Metni destekleyen iki fotoğraf.
- **Hakkımda / İletişim:** E-posta ve telefon bilgileri.
- **Altbilgi (footer):** Telif notu.

## Teknolojiler

- HTML5
- CSS3 (sayfa içi `<style>` bloğu)

## Proje Yapısı

```
kisisel-blog/
├── index.html      # Ana sayfa (içerik + stiller)
├── images.jpg      # Üst görsel
├── img2.jpg        # İkinci görsel
└── README.md       # Bu dosya
```

## Çalıştırma

Sunucuya gerek yoktur; `index.html` dosyasını doğrudan tarayıcıda açabilirsiniz:

```bash
# Dosyayı tarayıcıda açın
open index.html        # macOS
xdg-open index.html    # Linux
start index.html       # Windows
```

İsterseniz basit bir yerel sunucu da kullanabilirsiniz:

```bash
python3 -m http.server 8000
# Ardından tarayıcıdan http://localhost:8000 adresini açın
```

## GitHub'a Yükleme

Bu klasörü yeni bir GitHub deposuna yüklemek için:

```bash
cd kisisel-blog
git init
git add .
git commit -m "İlk sürüm: kişisel blog"
git branch -M main
git remote add origin https://github.com/KULLANICI_ADINIZ/kisisel-blog.git
git push -u origin main
```

> `KULLANICI_ADINIZ` kısmını kendi GitHub kullanıcı adınızla değiştirin ve depoyu önce GitHub üzerinden oluşturun.

### GitHub Pages ile Yayınlama (isteğe bağlı)

Depo ayarlarından **Settings → Pages** bölümüne gidin, kaynağı `main` dalı olarak seçin. Birkaç dakika içinde siteniz `https://KULLANICI_ADINIZ.github.io/kisisel-blog/` adresinde yayına girer.

## İletişim

- E-posta: example@example.com
- Telefon: 123-456-7890

> Bu bilgiler örnektir; kendi gerçek iletişim bilgilerinizle güncellemeyi unutmayın.

## Lisans

Bu proje [MIT Lisansı](LICENSE) ile lisanslanmıştır. Dilerseniz farklı bir lisans seçebilirsiniz.
