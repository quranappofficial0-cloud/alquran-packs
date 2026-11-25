# Al Quran Kareem — content packs

Downloadable content for the **Al Quran Kareem** Android app: translations, tafseers and hadith
books. The app downloads `<file>` from the latest release of this repository, checks its SHA-256
(listed in `packs.json`), unzips `pack.db` (an SQLite file with one edition) and uses it offline.

**Licence status: every pack is `pending`.** The texts belong to their authors, translators and
publishers; written permission for this app has not been received yet. They are published here for
the app's testing. If you hold the rights to any text and want it removed, please open an issue.

Release: `packs-v1` · 13 packs · content database version 9.

| File | Title | Author / translator | Download | Source | Licence |
|---|---|---|---|---|---|
| `translation.ur.mahmoodhasan-7c62a7b1a9.zip` | Tarjuma Shaykh-ul-Hind (with Tafsir-e-Usmani notes) | Shaykh-ul-Hind Mahmood Hasan (notes: Shabbir Ahmad Usmani) | 2.3 MB | Quran.com (Quran Foundation) API — `151` | pending |
| `translation.en.taqiusmani-6f20928b18.zip` | The Meanings of the Noble Qur'an | Mufti Muhammad Taqi Usmani | 0.4 MB | Quran.com (Quran Foundation) API — `84` | pending |
| `tafsir.ur.usmani-2810fb5359.zip` | Tafseer-e-Usmani | Allama Shabbir Ahmad Usmani | 1.8 MB | [Quran.com (Quran Foundation) API, resource 151: notes of Tarjuma Shaykh-ul-Hind](https://api.qurancdn.com/api/qdc/resources/translations/151/info) | pending |
| `tafsir.ur.tawzih-042dd15b34.zip` | Tawzih-ul-Quran (notes of Asaan Tarjuma) | Mufti Muhammad Taqi Usmani | 0.6 MB | [GitHub muqeetiqbal2/Quran-Text-with-Translations-And-Tafsirs (no licence file; README: educational / non-commercial)](https://github.com/muqeetiqbal2/Quran-Text-with-Translations-And-Tafsirs/blob/d387baa45410620dd8fba0a0695cd93104e297d8/full_quran_tafsir/urdu/tafseer_taqi_usmani.json) | pending |
| `tafsir.en.maarif-3c3ade9599.zip` | Ma'arif al-Qur'an (English) | Mufti Muhammad Shafi (tr. Muhammad Hasan Askari, Muhammad Shamim) | 4.1 MB | [Quran.com (Quran Foundation) API, tafsir 168](https://api.qurancdn.com/api/qdc/tafsirs/168/by_chapter/1) | pending |
| `tafsir.ur.ibnkathir-9ca42c7724.zip` | Tafseer Ibn Kaseer (Urdu) | Hafiz Imaduddin Ibn Kathir (Urdu translation) | 4.2 MB | [Quran.com (Quran Foundation) API, tafsir 160 (tafseer-ibn-e-kaseer-urdu)](https://api.qurancdn.com/api/qdc/tafsirs/160/by_chapter/1) | pending |
| `tafsir.en.ibnkathir-e3b4075286.zip` | Tafsir Ibn Kathir (English, abridged) | Hafiz Imaduddin Ibn Kathir (abridged, Darussalam) | 3.4 MB | [Quran.com (Quran Foundation) API, tafsir 169 (en-tafisr-ibn-kathir)](https://api.qurancdn.com/api/qdc/tafsirs/169/by_chapter/1) | pending |
| `hadith.bukhari-c46d508b95.zip` | Sahih al-Bukhari | Imam Muhammad ibn Ismail al-Bukhari | 5.7 MB | Arabic + English + kitab/number: meeAtif/hadith_datasets @ `cd62605e4f` (MIT dataset, text from sunnah.com); Urdu: fawazahmed0/hadith-api @ `df57907be3` (translator not stated); kitab titles: AhmedBaset/hadith-json @ `70b83d6d21` | pending |
| `hadith.muslim-2c814aeaa4.zip` | Sahih Muslim | Imam Muslim ibn al-Hajjaj al-Naysaburi | 4.3 MB | Arabic + English + kitab/number: meeAtif/hadith_datasets @ `cd62605e4f` (MIT dataset, text from sunnah.com); Urdu: fawazahmed0/hadith-api @ `df57907be3` (translator not stated); kitab titles: AhmedBaset/hadith-json @ `70b83d6d21` | pending |
| `hadith.abudawud-bb155d9141.zip` | Sunan Abi Dawud | Imam Abu Dawud Sulaiman ibn al-Ash'ath as-Sijistani | 3.1 MB | Arabic + English + kitab/number: meeAtif/hadith_datasets @ `cd62605e4f` (MIT dataset, text from sunnah.com); Urdu: fawazahmed0/hadith-api @ `df57907be3` (translator not stated); kitab titles: AhmedBaset/hadith-json @ `70b83d6d21` | pending |
| `hadith.tirmidhi-fe64867af6.zip` | Jami at-Tirmidhi | Imam Abu Isa Muhammad ibn Isa at-Tirmidhi | 2.9 MB | Arabic + English + kitab/number: meeAtif/hadith_datasets @ `cd62605e4f` (MIT dataset, text from sunnah.com); Urdu: fawazahmed0/hadith-api @ `df57907be3` (translator not stated); kitab titles: AhmedBaset/hadith-json @ `70b83d6d21` | pending |
| `hadith.nasai-f2179b69f5.zip` | Sunan an-Nasa'i | Imam Ahmad ibn Shu'aib an-Nasa'i | 2.4 MB | Arabic + English + kitab/number: meeAtif/hadith_datasets @ `cd62605e4f` (MIT dataset, text from sunnah.com); Urdu: fawazahmed0/hadith-api @ `df57907be3` (translator not stated); kitab titles: AhmedBaset/hadith-json @ `70b83d6d21` | pending |
| `hadith.ibnmajah-9fcb459662.zip` | Sunan Ibn Majah | Imam Muhammad ibn Yazid Ibn Majah al-Qazwini | 1.9 MB | Arabic + English + kitab/number: meeAtif/hadith_datasets @ `cd62605e4f` (MIT dataset, text from sunnah.com); Urdu: fawazahmed0/hadith-api @ `df57907be3` (translator not stated); kitab titles: AhmedBaset/hadith-json @ `70b83d6d21` | pending |

Notes
- Hadith packs: number coverage, gaps and missing Urdu are listed in the app repository
  (`tools/data/hadith.json`, PLAN.md §3.4.5, release checklist B13–B16).
- English Tafsir Ibn Kathir (Quran.com 169) has no commentary on Surah 105 in its source.
- Files are never changed in place: a changed pack gets a new file name (its SHA-256 is in the name).
