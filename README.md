# Individual

Repo payung untuk proyek pribadi Dzaki Muhammad Yusfian. Setiap folder adalah **submodule** yang menunjuk ke repo proyeknya sendiri, dan susunannya sama dengan folder lokal `D:\VsCode\Individual\`.

| Folder | Repo | Visibilitas | Isi |
|---|---|---|---|
| `Financial Tracker/Financial-Tracker-V.02` | [DMY-cmyk/Financial-Tracker-V.02](https://github.com/DMY-cmyk/Financial-Tracker-V.02) | Publik | Aplikasi web keuangan multi-pengguna (Next.js, Neon Postgres, Vercel) |
| `Financial Tracker System Spreadsheet` | DMY-cmyk/Financial-Tracker-System-Spreadsheet | **Privat** | Buku keuangan pribadi (Google Sheets, Apps Script, bot Telegram, Cloudflare Worker) |
| `Proffesional_Portfolio` | [DMY-cmyk/Proffesional_Portfolio](https://github.com/DMY-cmyk/Proffesional_Portfolio) | Publik | Situs portofolio (Next.js static export, GitHub Pages) |

Repo FTSS bersifat privat karena memuat data keuangan pribadi, jadi foldernya hanya bisa dibuka oleh pemiliknya.

## Memperbarui penunjuk submodule

Setelah commit dan push di salah satu proyek, catat posisi terbarunya di repo payung:

```powershell
cd D:\VsCode\Individual
git add -A
git commit -m "chore: perbarui penunjuk submodule"
git push
```

Untuk mengkloning semuanya di komputer lain, jalankan `git clone --recurse-submodules https://github.com/DMY-cmyk/Individual.git`. Untuk submodule privat, Anda harus login sebagai pemiliknya.
