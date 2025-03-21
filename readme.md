# README.md

## Proje Açıklaması
Bu proje, `gmt211_veri` adlı bir veri seti üzerinde çalışmayı ve bu süreçte Git ve GitHub komutlarını kullanmayı içermektedir. README.md dosyası, bu süreçte kullanılan komutları ve yaşanan deneyimleri kapsamaktadır.

---

## Kullanılan Git Komutları ve Açıklamaları

| Komut                         | Açıklama |
|--------------------------------|-------------------------------------------------------------|
| `touch point.py`              | Yeni bir `point.py` dosyası oluşturur.                      |
| `touch readme.md`             | Yeni bir `readme.md` dosyası oluşturur.                     |
| `git add .`                   | Çalışma alanındaki tüm dosyaları sahneleme alanına ekler.   |
| `git status`                  | Depodaki değişikliklerin durumunu kontrol eder.             |
| `git commit -m "firstcommit"` | Sahneleme alanındaki dosyaları "firstcommit" mesajıyla kalıcı hale getirir. |
| `git remote add origin <URL>`  | Uzak GitHub deposunu yerel repo ile ilişkilendirir.         |
| `git remote`                  | Tanımlanan uzak repo bağlantılarını listeler.               |
| `git push -u origin master`    | Değişiklikleri uzak depoya gönderir ve `origin/master` dalını takip eder. |

---

## Yerel Git İş Akışı ve GitHub İş Akışı
- **Yerel Git İş Akışı:** Dosyalarınızı oluşturur, değiştirir ve bu değişiklikleri `git add` ve `git commit` komutlarıyla yerel depoda kaydedersiniz. 
- **GitHub İş Akışı:** Yerel deponuzu GitHub'a göndermek için `git remote add` ve `git push` komutlarını kullanırsınız. Bu, projeyi başkalarıyla paylaşmanıza olanak tanır.

---

## Karşılaşılan Zorluklar ve Çözüm Yolları
- **`git add .` Hatası:** İlk denemede `git add .` komutu yanlış girildi (`git. add.` şeklinde). Doğru komutun `git add .` olduğunu fark ettim ve sorun çözüldü.
- **Uzak Repo Ekleme:** `git remote add origin` komutunun ardından `git push` işlemi sırasında bazı hata mesajlarıyla karşılaştım. Hatanın kaynağı GitHub bağlantısının eksik olmasıydı. Komutu tekrar girerek sorun çözüldü.
- **Yetkilendirme Hatası:** `git push` sırasında yetkilendirme hatası aldım. Çözüm olarak SSH anahtarlarını kullanarak GitHub hesabımla bağlantı kurdum.

---

## Commit Zamanlaması ve Gerekçesi
- İlk commit'i `point.py`, `readme.md` ve `coordinates.csv` dosyalarını ekledikten sonra gerçekleştirdim. Bu noktada dosyalarım temel yapıya ulaşmıştı ve çalışmamı kaydetmek mantıklıydı.
- Düzenli commit yaparak her değişiklik aşamasını takip etmeyi sağladım.

---

## AI Kullanımı ve Faydaları
- README.md dosyasının formatını oluştururken AI'den destek aldım. Özellikle, tablo yapısı, açıklamaların düzenlenmesi ve eksik kısımların tamamlanmasında büyük kolaylık sağladı.
- Hatalı girilen komutları düzeltme sürecinde AI'den faydalanarak daha verimli bir iş akışı oluşturdum.

---
![resim]("C:\Users\Excalibur\Desktop\resim.png")