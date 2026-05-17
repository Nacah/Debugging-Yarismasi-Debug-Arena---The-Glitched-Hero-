# Debugging-Yarismasi-Debug-Arena---The-Glitched-Hero-
---

## 🛠️ ÇÖZÜLEN HATALAR FORMU

### 1- [Giriş noktasını kurgulama]

* **Dosya Adı ve Satır Aralığı:** game/main.py: (4-7 satirlara kod eklendi)
* **Hatanın Sebebi:** main.py dosyası orijinal kodda boştu, oyunu kurugulamasini ve tetiklemesini sağlayan kodu ekledim
* **Nasıl Çözdünüz:** game class'ının ana metodu start'ı çağırarak oyunu başlatan kısmı yazdım

---

### 2- [Eksik nesne/class importları]

* **Dosya Adı ve Satır Aralığı:** game/game.py: (4-7 satirlara kod eklendi)
* **Hatanın Sebebi:** Kodun calismasi icin gerekli olan classlar import edilmemis (4 tane) onlari importlayarak koda eklenmeler yaptim
* **Nasıl Çözdünüz:** Gerekli importlar yazdim:
from game.character import Character
from game.enemy import Enemy
from game.battle import Battle
from game.data import CHAPTERS

---

### 3- [Hatanın Konusu]

* **Dosya Adı ve Satır Aralığı:**
* **Hatanın Sebebi:**
* **Nasıl Çözdünüz:**

*(Not: Bu listeyi aşağıya doğru dilediğiniz kadar uzatabilirsiniz.)*

---

## 🌟 EKLENEN BONUS ÖZELLİKLER (İsteğe Bağlı)
