# Av. Tolga Bilgin – Web Sitesi

Ankara Barosu kayıtlı Avukat Tolga Bilgin için hazırlanmış, sade HTML + CSS web sitesi.

## Dosyalar

- `index.html` – sayfa içeriği
- `style.css` – tasarım
- `images/tolga-bilgin.png` – portre fotoğrafı

## Yayınlamadan önce değiştirin

`index.html` içinde **İletişim** bölümündeki e-posta ve adres bilgilerini kendi bilgilerinizle güncelleyin (`ornek@eposta.com`, adres satırı).

## GitHub Pages ile yayınlama

1. GitHub’da yeni bir repo oluşturun (ör. `tolga-bilgin-hukuk`).
2. Bu klasördeki tüm dosyaları repoya yükleyin (`index.html` ana dizinde olmalı).
3. Repo sayfasında **Settings → Pages** bölümüne gidin.
4. **Source** olarak `Deploy from a branch` seçin, branch olarak `main` ve klasör olarak `/ (root)` seçip **Save** deyin.
5. Birkaç dakika sonra site şu adreste yayında olur:
   `https://KULLANICI-ADINIZ.github.io/tolga-bilgin-hukuk/`

### Komut satırıyla

```bash
git init
git add .
git commit -m "İlk sürüm"
git branch -M main
git remote add origin https://github.com/KULLANICI-ADINIZ/tolga-bilgin-hukuk.git
git push -u origin main
```
