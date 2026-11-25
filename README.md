# Al Quran Kareem — content packs

Downloadable content for the **Al Quran Kareem** Android app: translations, tafseers and hadith
books. The app downloads `<file>` from release `packs-v1` of this repository, checks its SHA-256
(listed in `packs.json`), unzips `pack.db` (an SQLite file with one edition) and uses it offline.

**Licence status: every pack is `pending`.** The texts belong to their authors, translators and
publishers; written permission for this app has not been received yet. They are published here for
the app's testing. If you hold the rights to any text and want it removed, please open an issue.

Attribution: hadith books marked "open-hadith-data" use **open-hadith-data by samt-qa —
https://github.com/samt-qa/open-hadith-data — CC BY 4.0** (structure, kitab / baab titles, isnad
split); the hadith texts themselves are public domain.

Content database version 10 · 22 packs.

| File | Title | Author / translator | Languages | Download | Source | Licence |
|---|---|---|---|---|---|---|
| `translation.ur.mahmoodhasan-fa26971452.zip` | Tarjuma Shaykh-ul-Hind (with Tafsir-e-Usmani notes) | Shaykh-ul-Hind Mahmood Hasan (notes: Shabbir Ahmad Usmani) | ur | 2.3 MB | Quran.com (Quran Foundation) API — `151` | pending |
| `translation.en.taqiusmani-4d25edda98.zip` | The Meanings of the Noble Qur'an | Mufti Muhammad Taqi Usmani | en | 0.4 MB | Quran.com (Quran Foundation) API — `84` | pending |
| `tafsir.ur.usmani-9b19eb572b.zip` | Tafseer-e-Usmani | Allama Shabbir Ahmad Usmani | ur | 1.8 MB | [Quran.com (Quran Foundation) API, resource 151: notes of Tarjuma Shaykh-ul-Hind](https://api.qurancdn.com/api/qdc/resources/translations/151/info) | pending |
| `tafsir.ur.tawzih-2337c717a1.zip` | Tawzih-ul-Quran (notes of Asaan Tarjuma) | Mufti Muhammad Taqi Usmani | ur | 0.6 MB | [GitHub muqeetiqbal2/Quran-Text-with-Translations-And-Tafsirs (no licence file; README: educational / non-commercial)](https://github.com/muqeetiqbal2/Quran-Text-with-Translations-And-Tafsirs/blob/d387baa45410620dd8fba0a0695cd93104e297d8/full_quran_tafsir/urdu/tafseer_taqi_usmani.json) | pending |
| `tafsir.en.maarif-9345c26d7f.zip` | Ma'arif al-Qur'an (English) | Mufti Muhammad Shafi (tr. Muhammad Hasan Askari, Muhammad Shamim) | en | 4.1 MB | [Quran.com (Quran Foundation) API, tafsir 168](https://api.qurancdn.com/api/qdc/tafsirs/168/by_chapter/1) | pending |
| `tafsir.ur.ibnkathir-e181a92f14.zip` | Tafseer Ibn Kaseer (Urdu) | Hafiz Imaduddin Ibn Kathir (Urdu translation) | ur | 4.2 MB | [Quran.com (Quran Foundation) API, tafsir 160 (tafseer-ibn-e-kaseer-urdu)](https://api.qurancdn.com/api/qdc/tafsirs/160/by_chapter/1) | pending |
| `tafsir.en.ibnkathir-6a1f464b0c.zip` | Tafsir Ibn Kathir (English, abridged) | Hafiz Imaduddin Ibn Kathir (abridged, Darussalam) | en | 3.4 MB | [Quran.com (Quran Foundation) API, tafsir 169 (en-tafisr-ibn-kathir)](https://api.qurancdn.com/api/qdc/tafsirs/169/by_chapter/1) | pending |
| `hadith.bukhari-92a58aa4b8.zip` | Sahih al-Bukhari | Imam Muhammad ibn Ismail al-Bukhari | ar + ur + en | 5.7 MB | Arabic + English + kitab/number: meeAtif/hadith_datasets @ `cd62605e4f` (text from sunnah.com); Urdu: fawazahmed0/hadith-api @ `df57907be3` (translator not stated); kitab titles: AhmedBaset/hadith-json | pending |
| `hadith.muslim-b7a44efbdf.zip` | Sahih Muslim | Imam Muslim ibn al-Hajjaj al-Naysaburi | ar + ur + en | 4.3 MB | Arabic + English + kitab/number: meeAtif/hadith_datasets @ `cd62605e4f` (text from sunnah.com); Urdu: fawazahmed0/hadith-api @ `df57907be3` (translator not stated); kitab titles: AhmedBaset/hadith-json | pending |
| `hadith.abudawud-de2faa48ff.zip` | Sunan Abi Dawud | Imam Abu Dawud Sulaiman ibn al-Ash'ath as-Sijistani | ar + ur + en | 3.1 MB | Arabic + English + kitab/number: meeAtif/hadith_datasets @ `cd62605e4f` (text from sunnah.com); Urdu: fawazahmed0/hadith-api @ `df57907be3` (translator not stated); kitab titles: AhmedBaset/hadith-json | pending |
| `hadith.tirmidhi-314b5f1aea.zip` | Jami at-Tirmidhi | Imam Abu Isa Muhammad ibn Isa at-Tirmidhi | ar + ur + en | 2.9 MB | Arabic + English + kitab/number: meeAtif/hadith_datasets @ `cd62605e4f` (text from sunnah.com); Urdu: fawazahmed0/hadith-api @ `df57907be3` (translator not stated); kitab titles: AhmedBaset/hadith-json | pending |
| `hadith.nasai-f95ef61a82.zip` | Sunan an-Nasa'i | Imam Ahmad ibn Shu'aib an-Nasa'i | ar + ur + en | 2.4 MB | Arabic + English + kitab/number: meeAtif/hadith_datasets @ `cd62605e4f` (text from sunnah.com); Urdu: fawazahmed0/hadith-api @ `df57907be3` (translator not stated); kitab titles: AhmedBaset/hadith-json | pending |
| `hadith.ibnmajah-65c739086b.zip` | Sunan Ibn Majah | Imam Muhammad ibn Yazid Ibn Majah al-Qazwini | ar + ur + en | 2.0 MB | Arabic + English + kitab/number: meeAtif/hadith_datasets @ `cd62605e4f` (text from sunnah.com); Urdu: fawazahmed0/hadith-api @ `df57907be3` (translator not stated); kitab titles: AhmedBaset/hadith-json | pending |
| `hadith.malik-4d3138929f.zip` | Muwatta Imam Malik | Imam Malik ibn Anas (riwayah of Yahya al-Laythi) | ar + ur + en | 1.1 MB | Arabic, kitab/baab, isnad: [open-hadith-data by samt-qa](https://github.com/samt-qa/open-hadith-data/releases/download/v0.1.0/open-hadith-data-0.1.0.zip) v0.1.0 — **CC BY 4.0** (texts public domain); Urdu + English: fawazahmed0/hadith-api (translators not stated) | pending |
| `hadith.ahmad-f966df1aa2.zip` | Musnad Ahmad | Imam Ahmad ibn Hanbal | ar | 4.2 MB | Arabic, kitab/baab, isnad: [open-hadith-data by samt-qa](https://github.com/samt-qa/open-hadith-data/releases/download/v0.1.0/open-hadith-data-0.1.0.zip) v0.1.0 — **CC BY 4.0** (texts public domain) | pending |
| `hadith.darimi-578811520c.zip` | Sunan ad-Darimi | Imam Abdullah ibn Abdur-Rahman ad-Darimi | ar | 0.5 MB | Arabic, kitab/baab, isnad: [open-hadith-data by samt-qa](https://github.com/samt-qa/open-hadith-data/releases/download/v0.1.0/open-hadith-data-0.1.0.zip) v0.1.0 — **CC BY 4.0** (texts public domain) | pending |
| `hadith.hakim-8a601dcd28.zip` | Al-Mustadrak (Hakim) | Imam al-Hakim an-Naysaburi | ar | 2.1 MB | Arabic, kitab/baab, isnad: [open-hadith-data by samt-qa](https://github.com/samt-qa/open-hadith-data/releases/download/v0.1.0/open-hadith-data-0.1.0.zip) v0.1.0 — **CC BY 4.0** (texts public domain) | pending |
| `hadith.ibnkhuzaymah-4464e2c919.zip` | Sahih Ibn Khuzaymah | Imam Ibn Khuzaymah | ar | 0.8 MB | Arabic, kitab/baab, isnad: [open-hadith-data by samt-qa](https://github.com/samt-qa/open-hadith-data/releases/download/v0.1.0/open-hadith-data-0.1.0.zip) v0.1.0 — **CC BY 4.0** (texts public domain) | pending |
| `hadith.ibnhibban-01f594b665.zip` | Sahih Ibn Hibban | Imam Ibn Hibban (al-Ihsan, Ibn Balban) | ar | 1.8 MB | Arabic, kitab/baab, isnad: [open-hadith-data by samt-qa](https://github.com/samt-qa/open-hadith-data/releases/download/v0.1.0/open-hadith-data-0.1.0.zip) v0.1.0 — **CC BY 4.0** (texts public domain) | pending |
| `hadith.ibnabishaybah-5c49aecfb8.zip` | Musannaf Ibn Abi Shaybah | Imam Abu Bakr Ibn Abi Shaybah | ar | 4.3 MB | Arabic, kitab/baab, isnad: [open-hadith-data by samt-qa](https://github.com/samt-qa/open-hadith-data/releases/download/v0.1.0/open-hadith-data-0.1.0.zip) v0.1.0 — **CC BY 4.0** (texts public domain) | pending |
| `hadith.bayhaqi-7d12026e98.zip` | Sunan al-Kubra (Bayhaqi) | Imam Abu Bakr al-Bayhaqi | ar | 5.0 MB | Arabic, kitab/baab, isnad: [open-hadith-data by samt-qa](https://github.com/samt-qa/open-hadith-data/releases/download/v0.1.0/open-hadith-data-0.1.0.zip) v0.1.0 — **CC BY 4.0** (texts public domain) | pending |
| `hadith.mishkat-e07a04cffa.zip` | Mishkat al-Masabih | Al-Khatib at-Tabrizi | ar + en | 1.4 MB | Arabic + English (sunnah.com) via AhmedBaset/hadith-json @ `70b83d6d21` — partial: sunnah.com has 4,428 of the book's about 6,285 ahadith; only those are included | pending |

Notes
- Number coverage, gaps and missing translations of each hadith book are listed in the app
  repository (`tools/data/hadith.json`, PLAN.md, release checklist B13–B17).
- Not available yet: Majma-uz-Zawaid (no clean licensed text), Al-Silsila (modern copyrighted work).
- English Tafsir Ibn Kathir (Quran.com 169) has no commentary on Surah 105 in its source.
- Files are never changed in place: a changed pack gets a new file name (its SHA-256 is in the name);
  older files stay for older app versions.
