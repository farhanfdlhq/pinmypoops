# PinMyPoops Landing Page 🚀

Landing page ini didesain khusus untuk mendistribusikan aplikasi **PinMyPoops** melalui platform Netlify atau Vercel.

## Cara Persiapan:
1.  **Gambar Hero**: Ambil gambar yang telah di-generate sebelumnya dan simpan di folder ini dengan nama `hero.png`.
2.  **File APK**: 
    - Build APK Anda (ikuti panduan sebelumnya).
    - Ambil file `app-release.apk` dari `android/app/build/outputs/apk/release/`.
    - Salin file tersebut ke dalam folder `landingpage/` ini.
    - Pastikan namanya tetap `app-release.apk` agar link download berfungsi.

## Cara Deploy ke Vercel:
1.  Install Vercel CLI: `npm i -g vercel`.
2.  Jalankan `vercel` di dalam folder ini.
3.  Ikuti instruksi di terminal. Selesai!

## Cara Deploy ke Netlify:
1.  Buka [app.netlify.com](https://app.netlify.com).
2.  Drag & drop folder `landingpage` ini ke area "Drag and drop your site folder here".
3.  Tunggu proses upload. Selesai!

---
**Officiality Note:**
Menggunakan Vercel/Netlify sangat disarankan karena:
- **Gratis**: Untuk traffic personal/kecil.
- **Cepat**: CDN mereka sangat kencang di seluruh dunia.
- **SSL Otomatis**: Website Anda langsung punya `https://` (aman).
