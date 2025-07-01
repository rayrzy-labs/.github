# 🧪 Rayrzy Labs

> Tempat naro *device tree*, *kernel tree*, *vendor*, dan segala *printilan build ROM*. Gitu aja.

Halo, selamat datang di **Rayrzy Labs** — repo ini bukan buat ngeluarin ROM keren siap-flash, tapi lebih kayak **tempat numpang naruh source**. Iya, kita tahu `device tree-nya belum clean`, kernel-nya `ada warning`, dan vendor-nya `ambil dari grup Telegram tahun 2019`. Tapi yaudahlah ya 🙃

## 📦 Isi Warung Ini

- `device_*`  – Device tree yang kadang bisa dipake, kadang cuma buat compile doang
- `kernel_*`  – Kernel tree, mostly CAF atau AOSP base, kadang kita tambahin magic
- `vendor_*`  – Vendor blobs biar bisa boot. Ya, isinya blob banget.
- `build-stuff` – Script atau patch yang cuma bisa dimengerti saat ngantuk jam 3 pagi

**Warning:**
Kalau kamu berharap tutorial lengkap, manifest repo, atau release ZIP, maaf banget bro — **ini bukan tempatnya.**

## 🤓 Buat Apa Nih?

- Buat kamu yang lagi ngulik device tertentu dan butuh base
- Buat backup-an pribadi (iya, kita males nyari di folder lokal)
- Buat pamer di GitHub biar keliatan produktif
- Buat orang lain yang suka bongkar-bongkar source (we see you 👀)

## 🧪 Bisa Digunakan?

Kalau kamu tahu apa yang kamu lakukan: ya, bisa.
Kalau kamu ngasal `repo sync` terus `make bacon`: siap-siap kena `FAILED: ninja: error` dan galau malam-malam.

## 📜 License

📢 Semua source ini asalnya dari open source atau reverse engineer yang capek.
Kalau mau make, make aja. Kalo mau ngedit, edit aja.
Kalo kamu flash ke device dan bootloop, jangan nyalahin kami 😇

---

**Rayrzy Labs — bukan tempat build, cuma tempat naruh.**
