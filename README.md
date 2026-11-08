# 🐱 FİKO'YU BÜYÜT — 3D Kedi Simülatörü

**v13 · Duraklat Menüsü + MP Manuel Kayıt + Ayarlar**
**by Sancak Interactive**

> Sokak kedisi Fiko'ya şehir evinde bakan bir tıklama / yaşam simülasyonu.
> Mama ver, sev, çay demle; faturaları öde, kışın sobayı yak, çamaşırı yıka, duşunu al.
> Seviye atladıkça tık kazancın büyür... ama unutma: **Fiko hep haklıdır.**

---

## ℹ️ Hakkında

| | |
|---|---|
| **Oyun** | FİKO'YU BÜYÜT — 3D Kedi Simülatörü |
| **Sürüm** | v13 |
| **Geliştirici** | Sancak Interactive |
| **Tür** | 3D · Kedi Simülasyonu · Yaşam / Tıklama · Coop |
| **Platform** | 💻 PC (tarayıcı) & 📱 Mobil (tarayıcı) |
| **Modlar** | 👤 Tek Oyunculu · 👥 Coop Online (2 kişi) |
| **Teknoloji** | Three.js · Tek dosya HTML5 · PeerJS (online) · localStorage (kayıt) |
| **İletişim** | 📩 Sancakinteractive@gmail.com |

---

## ▶️ Nasıl Çalıştırılır?

Hiçbir kurulum gerekmez — **tek dosya** yeter:

1. `fiko-3d-v13.html` dosyasını indir.
2. Çift tıkla → tarayıcında (Chrome, Edge, Firefox, Safari) açılır.
3. Ana menüden avatar rengini seç, **Tek Oyunculu** veya **Coop Online** de.
4. Kankaevine hoş geldin! 🏠

* İnternet gerektirmez (Coop Online modu hariç).
* Kayıt otomatik tarayıcıya yazılır (`fiko_save_v1`), ayarlar da (`fiko_cfg_v1`).

---

## 🎮 Kontroller

### 💻 PC

| Tuş | İşlev |
|---|---|
| **W A S D** | Yürü (düzen modunda: seçili eşyayı taşır) |
| **Fare** | Etrafa bak · Objeye nişan al |
| **Sol Tık / E** | Etkileşim (Fiko'ya tıkla = **SEV ❤️** +$2/$5/$12) |
| **B** | 🛒 Dükkan (105+ parça) |
| **F** | 📸 Poz Paylaş (PNG indir + fenomen hesabına paylaş) |
| **U** | 🪑 Eşya Düzenleme modu (taşı / döndür / iade) |
| **R** | 🔄 Eşyayı 45° döndür (düzen modunda) |
| **X** | ♻️ Eşyayı yarım fiyatına iade et (düzen modunda) |
| **G / 📋** | 📋 Günlük görevler (3 görev) |
| **T** | 💬 Sohbet (Coop) |
| **ESC** | ⏸️ Duraklat menüsü · Fareyi serbest bırakır |

### 📱 Mobil

| Dokunuş | İşlev |
|---|---|
| **Sol joystick** | Yürü |
| **Sağ ekrana sürükle** | Etrafa bak |
| **Objeye dokun** | Etkileşim |
| **Fiko'ya dokun** | SEV ❤️ (emote'lar kendisinden gelir) |
| **⏸️ / 🪑 / 🛒** | Duraklat · Düzen · Dükkan butonları |

---

## 👥 Oyun Modları

### 👤 Tek Oyunculu
Klasik mod: Fiko, ev, kira ve hayat seninle. ESC ile duraklatırsan oyun **GERÇEKTEN durur** (kedi, saat, faturalar hepsi buz). Sekmeyi gizlersen tek oyunculu kendini duraklatır.

### 👥 Coop Online (arkadaşla aynı ev)
1. **Host Ol** de → **6 haneli oda kodun** otomatik verilir.
2. Kodu kankana yolla (WhatsApp, DM, yell...).
3. Kankan **Odaya Katıl** → kodu girer → bağlanana kadar oyun başlamaz.
4. **Ortak kasa, ortak Fiko, ortak ev!** Online mod en az **2 kişi** ister.

* Bağlantı: PeerJS sunucusu üzerinden (aynı ağ şart değil).
* Coop'ta: 🎁 hediye gönder, ⚔️ PvP kedi kavgası, 💬 sohbet.
* 💾 Manuel Kayıt artık çok oyunculuda da var: host ortak dünyayı kaydeder, katılan oyuncu host dünyasının kopyasını kendi tarayıcına alır (kendi ihtiyaçlarıyla).

---

## 🏠 Ev & Odalar

Çok odalı tam 3D bir ev — her şey Three.js ile prosedürel modellenmiş:

* 🛋️ **Salon** — kanepe (Fiko'nun tırmalama hedefi 🙀), TV, sehpa, halı
* 🍳 **Mutfak** — açılır kapılı **buzdolabı** (içinde Büfe yemekleri), ocak, çamaşır makinesi, çöp kovası
* 🛁 **Banyo** — duş (🧼 Temizlik barı), alaturka tuvalet (rahatla / el yıka)
* 🛏️ **Yatak odası** — yatak (uyu, sabah 8), gardırop
* 🌳 **Bahçe / Veranda** — kedi nanesi, martı bile uçar 😄
* ➕ Kedi tünekleri, tırmalama tahtası, kum kabı, mama & su kabı, akvaryum (terapi!), kuzine soba...

**Mevsimler:** 3 günde bir mevsim döner. Kışta ev soğur — **soba yak**, yoksa sıcaklık düşer, sağlığın döker. Ama soba her saniye az da olsa para yakar; kasa bitince söner!

---

## 😼 Kedi Doğası (Fiko AI)

**Butonlar yok — Fiko kendi başına davranır!** Sen sadece seveceksin:

| Fiko ne yapar? | Sonuç |
|---|---|
| 😈 Canı sıkılınca **bardağı KENDİ devirir** | -$8 tamir |
| 🗑️ **Çöpü KENDİ karıştırır** | Para / simit / FARE çıkar! |
| 🐭 **Fareyi KENDİ kovalayıp yakalar** | +$12 |
| 🛋️ Tırmalama tahtası yoksa **KANEPEYİ tırmalar** | Mobilya zarar görür |
| 🍽️ Aç kalırsa mama kabına gider; bağırarak "MAMA!" der | Besle! |
| 🚽 Tuvaleti doluysa yere yapar (sağlığı gider) | Kum kabını temizle |
| 🦨 Kum kabı kokar, temizlemezsen **halıya yapar** | Kokuyu topla |
| 🦟 Pire kaparsa | Pire Spreyi veya 🩺 veteriner |
| 😵‍💫 Kedi Nanesi yediyse | **30 sn gökkuşağı modu** 🌈 |
| ⚖️ Çok yerse şişmanlar, yavaşlar | Kiloya dikkat |
| 👀 Gerçek miyavlar: ağzı açılır, kafası kalkar, göz kırpır, kulağı oynar, gecede göz bebeği büyür, uykuda "Zzz…" | Sevimli patron |

**Sevme sistemi:** Fiko'ya tıkla ❤️ → pur pur, sürtülme, miyav, hamur yoğurma emote'ları (hepsi kalpli). Seviye atladıkça SEV tık başına kazancın büyür: **Lv1-3 ×2 · Lv4-7 ×5 · Lv8+ ×12**.

**Mahalle kedisi Tontiş:** Hırla-tırmala düellosu — kazanınca itibar +$15! Tontiş'e yaka + madalyon da giydirebilirsin.

---

## 💰 Ekonomi & Hayatta Kalma (ZOR MOD!)

* 💵 **Para kazanma:** Fiko'yu SEV (+$2/$5/$12), pisliği temizle (+$3), fare yak (+$12), günlük görevler, 📸 Poz Paylaş (beğeni + para + takipçi). Pasif gelir ancak pahalı mobilyalarla gelir. Klik aralığı 0.4 sn, her tık stamina yer.
* 🧾 **Faturalar:** 2 günde bir gelir. **3 fatura birikirse KOVULURSUN!**
* 🎉 **Olaylar:** 5 kategori — eğlenceli · üzücü · mantıklı · işlevsel · işlev bozucu. Elektrik/su/internet kesintileri, piyangolar, viral kediler... Nazar tasmalı kedide kötü olay seyrek.
* 🫀 **Kendi ihtiyaçların:** Buzdolabı → ye (Büfe'den yemek al), Yatak → uyu (sabah 8), Tuvalet → rahatla veya el yıka, Duş → 🧼 Temizlik yenile. İhtiyaç sıfırlanırsa sağlık döker, **sağlık 0 → ÖLÜM**.
* 🧺 **Kirli çamaşır:** Sepet zamanla dolar (6'ya kadar). 4+ kirliyken ev kokar. Çamaşır makinesine tıkla → 20 sn yıkar → +Temizlik, +XP.
* 🗑️ Fiko'nun sağlığı 0 → **VEDA**. (Kural 1: Fiko hep haklıdır. Kural 2: Yukarıdaki kuralı unutma.)

### 🏆 GERÇEK SON
Dükkan → Dekor → **Altın Anahtar ($99.999)** → salonun güney duvarındaki **kilitli dış kapı**ya gir. Kira serüveni biter, **ev senin olur** 🏠

---

## 🛒 Dükkan

**105+ parça**, 5 sekme: Mobilya · Yiyecek (Büfe) · Giyim (kedi skinleri: deri mont, tasma, pembe fiyonk + Tontiş'e yaka/madalyon) · Dekor (Türk bayrağı, Altın Anahtar...) · Diğer (kedi nanesi, pire spreyi...).

**🪑 Eşya Düzenleme:** U tuşu (mobil: 🪑) → eşyaya tıkla → WASD/oklarla taşı · R döndür · X iade (%50 geri) · U çık. Çakışan mobilyayı düzelt, beğenmediklerini geri sat!

---

## ⏸️ v13: Duraklat, Kayıt & Ayarlar

* **⏸️ Duraklat (ESC veya buton):**
  * **Tek oyunculu:** oyun GERÇEKTEN durur — kedi, saat, faturalar hepsi buz.
  * **Çok oyunculu:** dünya arkada akar; menü, ayarlar ve manuel kayıt sadece senin içinidir.
* **💾 Manuel Kayıt:** Tek ve çok oyunculuda çalışır (yukarıda anlatıldığı gibi).
* **⚙️ Ayarlar:** 🔊 Ses aç/kapa · 🎚️ Ses seviyesi · 🖱️ Fare hassasiyeti — hepsi kalıcı (`fiko_cfg_v1`).
* **🚪 Kaydet & Ana Menüye Dön** butonuyla güvenli çıkış.

---

## ✨ Sürüm Geçmişi

| Sürüm | Yenilikler |
|---|---|
| **v13** | ⏸️ Duraklat menüsü (SP gerçek duraklatma, MP dünya akmaya devam) · 💾 MP manuel kayıt · ⚙️ kalıcı ayarlar (ses/ses seviyesi/fare hassasiyeti) · sekme gizlenince SP otomatik duraklar · ana menüde "by Sancak Interactive" imzası |
| **v12** | 🛠️ Fiko'nun boyu artık seviyeyle DEĞİŞMEZ · deri mont, tasma ve pembe fiyonk kediye tam oturur · buzdolabı kapısı DIŞARI açılır, iç raflar ve yiyecekler gerçekten görünür |
| **v11** | 🪑 Eşya düzenleme modu (taşı/döndür/iade) · yeni mobilya gerçek boyutuyla yerleşir · GERÇEK miyav: ağız, kulak, göz bebeği, "MAMA!" bağırışı, Zzz · Tontiş'e yaka + madalyon, avatarlara boyun/kemer/ayakkabı |
| **v10** | 😼 Kedi Özerkliği: bardak devirme, çöp karıştırma, fare kovalama, kanepe tırmalama · emote'lar sevmeden gelir · 📸 PNG indir + fenomen paylaşımı |
| **v9** | Mahalle kedisi Tontiş (hırla-tırmala) · kedi nanesi (30 sn gökkuşağı) · gece yıldızlar & ay · pire + sprey + veteriner · kum kabı kokuşması · kilo sistemi · günlük görevler · coop hediye + PvP · ıslak pati izleri, cama burun izi · sesler + fotoğraf modu |
| **v8** | 🚪 Ana menü · açılır buzdolabı · kirli çamaşır + makine yıkama · duş/banyo (🧼 Temizlik) · tuvalette el yıkama · duvar saati, saksı, havlu & banyo paspası · buhar + kabarcık animasyonları |
| **v7** | 🔐 Kilitli dış kapı + **Altın Anahtar ($99.999) → GERÇEK SON: KENDİNE EV ALDIN** · online lobi düzeltmeleri |
| **v6** | 📱 Mobil arayüz yeniden tasarım (joystick, alt menü, bottom-sheet) |
| **v5** | 🍂 Mevsimler · 5 kategori olay · kuzine soba · fatura/ev sahibi sistemi |
| **v3-v4** | 👥 Coop online (6 haneli oda kodu) · alaturka tuvalet · Türk bayrağı · 105 parça dükkan |

---

## 🔧 Teknik Bilgiler

* **Tek dosya:** Tüm oyun (kod + modeller + dokular + sesler) tek HTML dosyasında; hiçbir ek dosya/sunucu gerekmez.
* **Three.js** ile prosedürel 3D modeller ve canvas dokular (ahşap, duvar kağıdı, kedi tüyü, çimen...), gerçek ışık & gölge haritaları, çarpışma sistemi.
* **Online:** PeerJS (6 haneli oda kodu) — aynı ağ şart değil. Aynı cihaz/tarayıcıda çoklu sekme için BroadcastChannel yedeği.
* **Kayıt:** `fiko_save_v1` (oyun) + `fiko_cfg_v1` (ayarlar) — localStorage.
* **Easter egg'ler:** Kettle'a tıkla (çay), simidi bul, çamaşır makinesiyle konuş... 👀

---

## ⚖️ Telif & İletişim

**Copyright © 2026 Sancak Interactive. Tüm hakları saklıdır.**

📩 İletişim & iş birliği: **Sancakinteractive@gmail.com**

*Kural 1: Fiko hep haklıdır. Kural 2: Yukarıdaki kuralı unutma.* 🐱👑
