# NATO Taleo Alerts (GitHub Notifications)

- Workflow her 3 saatte bir çalışır.
- Taleo'da **Posting Date = Today** filtreli ilanları tarar.
- Yeni ilan bulunursa:
  - `seen_jobs.json` güncellenir
  - `alert.md` üretilir
  - Repo'da **NATO Taleo Alerts** adlı tek bir issue altına **yorum** eklenir.
  - Issue `anthrozz` kullanıcısına assign edilir (push bildirimi gelir).

## Kurulum
1. Bu dosyaları yeni bir GitHub reposuna yükleyin (aynı klasör yapısıyla).
   - `nato_taleo_alert.py`
   - `requirements.txt`
   - `README.md`
   - `.github/workflows/taleo.yml`
2. Repo sayfasında **Actions** sekmesini açıp gerekirse **Enable workflows** deyin.
3. Sağ üstten **Watch → All Activity** seçin.
4. GitHub mobil uygulamasında **Issues** bildirimlerinin açık olduğundan emin olun.
5. Actions sekmesinden **Run workflow** ile ilk testi manuel başlatabilirsiniz.
