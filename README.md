# Kinerja-PWBLUD - APK Releases

Repositori ini hanya untuk mendistribusikan APK aplikasi **Kinerja-PWBLUD**
(`id.my.paruhwaktu.kinerja`). Kode sumber tidak disimpan di sini.

## Unduh

1. Buka tab [Releases](https://github.com/bandidev/kinerja-pwblud-releases/releases).
2. Pilih build yang diinginkan, lalu unduh file `.apk` beserta file checksum `.sha256`.
3. Pasang APK di perangkat Android. Jika diminta, izinkan pemasangan dari sumber
   tidak dikenal untuk aplikasi pengelola file atau browser yang dipakai.

## Verifikasi checksum

Setiap APK disertai nilai SHA-256 pada catatan rilis dan/atau file `.sha256`.
Verifikasi sebelum memasang:

```bash
sha256sum -c Kinerja-PWBLUD-<versi>.apk.sha256
```

Windows (PowerShell):

```powershell
Get-FileHash .\Kinerja-PWBLUD-<versi>.apk -Algorithm SHA256
```

Bandingkan hasilnya dengan nilai SHA-256 yang tercantum pada catatan rilis.
Jangan memasang APK bila nilainya tidak sama.

## Catatan

- Hanya APK yang diunggah sebagai aset rilis; artefak build tidak dimasukkan ke
  riwayat Git.
- Status pengujian perangkat dicantumkan pada catatan rilis masing-masing build.
  README ini tidak menyatakan bahwa pengujian perangkat telah lulus.
