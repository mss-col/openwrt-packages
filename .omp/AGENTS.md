# AGENTS.md — openwrt-packages

> Fail konteks projek: `README.md`.
> Ringkasan operasi untuk agent kod — bukan pengganti dokumen di atas.
> Dijana 2026-09-12 daripada kod, commit `a99572e Update luci-app-helium packages`. Jana semula jika kod berubah.

## Apa ini

Custom OpenWrt packages repository by MSS.

_(dipetik daripada `README.md`)_

⚠ **Dokumen sumber boleh lapuk.** Sahkan versi dan bilangan terhadap kod — manifest sebenar dan seksyen *Kiraan komponen* di bawah. Kes sebenar: dokumen projek menyebut stack yang kod sudah tukar.

## Perintah

_Tiada manifest build/test dikesan dalam repo ini._

## Struktur direktori

Senarai aras 1–2. Kalau sesuatu tidak kelihatan di sini, sahkan dahulu dengan `ls` — jangan simpulkan ia tiada.

```
.mcp.json
README.md
.code-review-graph/
packages/
  all/
  (+4 fail dalam subdirektori)
```

## Fail konteks projek

| Fail | Saiz | Dikemas kini |
|---|---|---|
| `README.md` | 1 KB | 2026-01-23 |

## Konvensyen dan perangkap

Dipetik verbatim daripada dokumen projek. Sahkan terhadap kod.

_Tiada amaran tersurat dijumpai dalam dokumen projek._

## Di mana mencari apa

| Perlu | Fail |
|---|---|
| Gambaran projek | `README.md` |

## Peraturan kerja

- **Bukti diperlukan** — tulis "diuji dan disahkan", bukan "patut jalan".
- **Jangan `git push`** tanpa kelulusan Boss.
- **Jangan cipta** fail `.md`/dokumen/skrip baharu tanpa kelulusan Boss.
- **Baca fail konteks projek dahulu** sebelum mengubah kod.