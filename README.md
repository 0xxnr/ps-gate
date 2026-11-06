<p align="center">
  <img src="branding/psgate-icon.png" alt="PS Gate" width="160" height="160" />
</p>

<h1 align="center">PS Gate</h1>

<p align="center">
  Jailbreak'li PS5'iniz için macOS uygulaması: oyun, uygulama ve homebrew yükleyin, kurun, yönetin ve mac üzerinde oynayın.
</p>

<p align="center">
  <img alt="sürüm" src="https://img.shields.io/badge/s%C3%BCr%C3%BCm-1.1-7c5cff" />
  <img alt="platform" src="https://img.shields.io/badge/platform-macOS%2011%2B-1d1f3b" />
  <img alt="lisans" src="https://img.shields.io/badge/lisans-GPL--3.0-4ade9b" />
</p>
<p align="center">
  <img src="branding/screenshots/home.png" alt="PS Gate ana sayfa: Oyna, Yükle ve Kur, Oyunlar, Dosyalar ve konsol durumu" width="900" />
</p>

<p align="center">
  <a href="#türkçe">Türkçe</a> · <a href="#english">English</a>
</p>

---

## Türkçe

PS Gate, jailbreak'li bir PS5'i Mac'ten yönetmek için bir macOS uygulamasıdır. Oyunları ve
paketleri PS5'e gönderir ve kurar; konsoldaki dosyaları, oyunları ve kayıtları yönetir; PS5'i Mac'ten
oynamanızı sağlar.

> **Önemli:** PS Gate yalnızca jailbreak'li bir PS5 ile çalışır ve Sony ile hiçbir bağlantısı yoktur.
> Kullanmadan önce [Yasal uyarı](#yasal-uyarı) bölümünü okuyun.

### Özellikler

**1.1 ile gelenler.** Üç yeni özelliğin hepsi uygulamanın içinde; internetten ayrıca bir şey
indirmeniz gerekmez, PS Gate her şeyi bilgisayarınızdan PS5'e gönderir.

- **Steam Oyunları.** Uyumlu Steam PC oyunlarını jailbreak'li PS5'inizde oynayın.
  - **PS Gate Steam**'i tek tuşla PS5'e kurun, güncelleyin ve açın. Wine, Mesa ve DXVK'yi içeren
    çalışma kiti PS Gate'le birlikte gelir.
  - PS5'te Steam'e giriş yapın (QR kod ya da kullanıcı adı), kütüphanenizi indirin ve oynayın. Her
    oyun Ana ekranda kendi kutucuğunu alır.
  - Steam hesabı olmadan, elinizdeki Windows oyun klasörlerini PS Gate'ten PS5'e gönderip
    ekleyebilirsiniz.
  - Direct3D 8–12, OpenGL ve Vulkan; kol, klavye/fare ve dört kişiye kadar yerel çok oyunculu destek.
- **Klavye ve Fare.** PS5'e USB klavye ve fare takın, her oyunu onlarla oynayın; adaptör ya da
  bilgisayar gerekmez.
  - **PS Gate KBM**, klavye ve fareyi sanal bir DualSense'e çevirir ve açtığınız oyunu tanır.
  - 51 oyun PC sürümünün tuş düzeniyle, yaklaşık 280 oyun da tür şablonuyla hazır gelir. Oyun açık
    değilken PS5 menülerinde klavye ve fareyle gezinirsiniz.
  - Durum, profil ve sinyaller PS Gate'te canlı görünür; hassasiyet ve tuş atama ayarlar
    sayfasından yapılır.
  - İsterseniz PS5 Ana ekranına bir ikon kurun, bilgisayarı açmadan başlatın. Yeni bir klavye ya da
    fareyi önce tanılama moduyla deneyin. Kablolu Xbox kolları da çalışır.
- **Switch 2 (deneysel).** Switch 2 oyunlarını jailbreak'li PS5'te çalıştıran deneysel bir emülatör.
  - **PS Gate NS2**'yi PS5'e kurun; kendi konsolunuzdan ve kartuşlarınızdan aldığınız key, firmware
    ve oyunları PS Gate'ten PS5'e gönderin.
  - Şu an **Pokopia oynanabilir** (45–50 FPS). Donkey Kong Bananza ve Welcome Tour açılıyor ama
    yavaş; diğer oyunlar henüz açılmıyor. Düşük kare hızı, görüntü hataları ve çökmeler beklenmeli.
  - PS Gate key, firmware ya da oyun içermez.
- **Bu özellikler için gerekenler.** PS5 her açıldığında yüklenen **kstuff**, **ShadowMountPlus** ve
  **elfldr**; PS5'in DNS'i 127.0.0.1 ise Steam için **nanoDNS** de. Hepsi PS Gate'in Payload'lar
  ekranında. Steam Oyunları 13.60, Klavye ve Fare 11.60 yazılımında denendi; diğer sürümler
  engellenmiyor ama denenmedi. Bazı çevrimiçi oyunlar klavye/fare adaptörlerini ve değiştirilmiş
  Steam istemcilerini yasaklayabilir; bu özellikler çevrimdışı oyun için düşünülmüştür.

**Diğer özellikler**

- **Hızlı ve kesintiye dayanıklı aktarım.** Oyun klasörleri, disk imajları, paketler ve `.zip` / `.7z` /
  `.rar` arşivleri tek bir şifreli bağlantı üzerinden gönderilir. Bağlantı koparsa ya da PS5 dinlenme
  moduna geçerse aktarım kaldığı yerden devam eder; her dosya doğrulanır. Sıra, canlı hız ve kalan süre
  görünür; yer yetmeyecek bir iş baştan reddedilir.
- **Yükle ve Kur.** Tek bir bırakma alanı paketleri, oyun klasörlerini, disk imajlarını ve arşivleri
  tanır. PS4 `.pkg` ve PS5 sahte paketleri Mac'ten, ağ paylaşımından, USB sürücüden ya da bir
  bağlantıdan kurulabilir; bir yol işe yaramazsa uygulama başka bir yol önerir.
- **Oyunlar.** Bilgisayarınızdaki, ağ paylaşımlarınızdaki ve PS5'teki oyunlar tek bir ızgarada;
  güncellemeler ve DLC'ler oyunlarıyla birlikte. NAS'taki klasörler kopyalanmadan yerinde taranır.
  Kurulu bir oyun doğrudan kartından başlatılır ya da kapatılır; her oyunun sayfasından kurma,
  bağlama, ana ekrana ekleme, taşıma, yedekleme ve dönüştürme.
- **Atölye.** Oyunlarınızı bu bilgisayarda dönüştürür; iş Mac'te yapılır, sonra isterseniz PS5'e
  kurulur.
  - **Ne yapılacağını seçin:** kurulabilir bir **paket (`.pkg`)**: PS5'e mağazadan bir oyun gibi
    kurulur; PS4 oyunları her yazılımda, PS5 oyunları 11.60 ve altında çalışır. Ya da PS5'in
    bağlayabildiği bir **oyun kalıbı** (`.exfat`, `.ffpkg`, `.ffpfs`, `.ffpfsc`) ya da bir **oyun
    klasörü**. Uygulama, seçtiğiniz oyun ve PS5'iniz için hangisinin daha uygun olduğunu işaretler.
  - **Kaynak:** oyun klasörünü, imajı ya da arşivi sürükleyip bırakın, dosya veya klasör seçin ya
    da PS5'teki bir yolu yazın. Birden çok oyun ya da bütün bir oyun klasörü kuyruğa girer ve
    sırayla oluşturulur.
  - **Sıkıştırma:** Hızlı, Dengeli (önerilen), En küçük ya da Sıkıştırmasız; bir oyun seçince her
    seçeneğin tahmini boyutu görünür. Oyun her durumda aynıdır, yalnızca boyut ve süre değişir.
  - **Oyun dili:** başka bir dile ayarlı bir konsolda İngilizce açılan bir oyun için pakete dil
    bilgisi yazılabilir.
  - **Çıktı ve doğrulama:** çıktı klasörünü seçin ya da her birini kaynağının yanına kaydedin;
    **Tam doğrulama** çıktının her baytını yeniden okuyup denetler.
  - **Oluştur ve kur:** yalnızca dönüştürün ya da dönüştürüp hemen PS5'e kurun; kurduktan sonra
    paketi saklayın ya da silin. **Bu bilgisayarı daha az kullan** ile dönüştürme arka planda,
    Mac'i yormadan çalışır.
  - **İçine bakma ve düzenleme:** bir oyun imajının ya da paketin içine bakın, dosyaları Mac'e
    kaydedin ya da dosyaları değiştirip düzenlenmiş bir kopya yazın; açtığınız imaj hiç değişmez.
- **Dosyalar ve konsol.** PS5'teki dosyalara göz atma, kopyalama, taşıma, silme, izin ayarlama; ekran
  görüntüleri ve video klipler; oyun kaydetme, başlatma, durdurma ve kaldırma.
- **Kayıt verileri.** Otomatik yedekler, tek tıkla yedekleme ve geri yükleme, başka bir kullanıcıya
  kopyalama. PS1, PS2 ve Switch emülatör kayıtları da yedeklenir.
- **Oyna.** PS5'i Mac'ten oynayın: dinlenme modundaki konsolu uyandırır ve kullanıcınızla oturum açar.
  Oyun kumandası, klavye veya fare; 1080p/720p, 60/30 fps; resim içinde resim. **Birlikte Oyna** ile
  arkadaşlarınız bir bağlantı ya da QR kod ile oyununuza 2., 3. ve 4. oyuncu olarak katılır. Oyunu
  YouTube, Twitch ve diğer RTMP/SRT sunucularına canlı yayınlayabilirsiniz.
- **Paylaşılan Klasörler.** NAS'ınızı ya da sunucunuzu SMB, FTP veya SFTP/WebDAV ile bağlayın;
  oyunlar doğrudan oradan seçilir ve kurulur.
- **Birimler.** PS5'in depolama sürücüleri ve şu anda bağlı disk imajları.
- **Temizlik.** PS5'in sürücülerini dolduran ve güvenle silinebilecek dosyaları bulur: güncellemeler,
  geride kalan paket dosyaları, geçici dosyalar ve kaldırılmış oyunların artıkları. Siz seçip
  onaylamadan hiçbir şey silinmez.
- **Hileler.** Bir oyun seçin, sürümüne uygun hileleri indirin ve oynarken açıp kapatın.
- **Konsol.** Çalışan işlemler, donanım ve sıcaklıklar, fan eğrisi, çekirdek günlüğü ve PS5 üzerinde
  komut çalıştırmak için bir **Shell**.
- **Payload'lar.** Payload ELF'lerini katalogdan ya da kendi dosyalarınızdan, tek tek veya bir oynatma
  listesi olarak konsolun yükleyicisine gönderin. Geriye taşınmış oyunlar için uyumluluk ayarı da
  buradadır.
- **Hesaplar.** Konsolun kullanıcı hesapları: adlarını değiştirin, bir hesaba kimliğini verin,
  avatarları değiştirin ve Oyna'yı kurun.
- **Birden çok cihaz, tek PS5.** Bilgisayarlar, telefonlar ve Docker kurulumları aynı anda eşleştirme
  kodu olmadan bağlanır; **Cihazlar** ekranında kimin ne yaptığı görünür. Konsollar ve ayarlar
  paylaşılır ve her gün hem motora hem konsola yedeklenir. **Mesh Drive** bir klasörü bütün
  cihazlarda aynı tutar.
- **Etkinlik, günlükler ve bildirimler.** Bütün yüklemeler, kurulumlar ve dosya işleri tek bir
  listede; önemli sonuçlar ve uyarılar bildirim olarak gelir.
- **Güç.** Dinlenme modu, yeniden başlatma, kapatma ve ağ üzerinden uyandırma.
- **PS Gate Minion.** PS5'in kendi tarayıcısında açılan, kumandayla kullanılan bir sayfa: kurulu
  oyunlar, kayıt yedekleri, dosyalar, hileler ve ayarlar; yanınızda bilgisayar olmadan.
- **Hata bildirimi.** Uygulamanın, motorun ve PS5 yardımcısının günlüklerini tek bir `.zip`'te
  toplar; adresler, seri numaraları ve anahtarlar çıkarılır.
- **MCP ve API: yapay zekâ ajanlarıyla yönetim.** PS Gate'in motoru `http://127.0.0.1:19113/mcp`
  adresinde bir MCP sunucusu çalıştırır; Claude Code, Codex veya OpenCode gibi bir yapay zekâ ajanı
  PS5'i anladığı araçlarla yönetebilir: dosya gönderme, oyun yükleme, sıcaklık kontrolü ve daha
  fazlası. Bir kez ekleyin, sonra yalnızca isteyin.
  - **Ajan bağla:** Claude Code'a tek tıkla ekleme; Codex ve OpenCode için hazır terminal
    komutları ve bağlantıyı doğrulama komutları (`mcp list`). Uygulama ajanın bu bilgisayarda
    kurulu ve ekli olup olmadığını gösterir; kurulu değilse indirme bağlantısını verir.
  - **Ajan araçları:** ajanın kullanabileceği 128 aracın aranabilir listesi: motor durumu,
    konsolları bulma, yardımcıyı gönderme, işleri başlatma, duraklatma ve iptal etme ve daha
    fazlası. Yalnızca okuyan araçlar **Salt okunur** olarak işaretlidir.
  - **API:** betikler için aynı motorun HTTP API'si ve OpenAPI belgesi.
  - **Kendiliğinden güncel:** ajanlar araçlarını motordan alır; PS Gate güncellendiğinde yeni
    araçlar ajanın bir sonraki oturumunda görünür. Motorun adresi değişirse uygulama bunu söyler ve
    tek tıkla düzeltir. Gemini CLI, Cursor, Claude Desktop ve kendi betikleriniz için kurulum
    bilgisi de ekranda.
  - **Örnek istekler:** "PS5'im şu anda ne kadar sıcak?", "PS5'imde en çok yeri ne kaplıyor?",
    "Bu paketi PS5'ime yükle ve bitince bana haber ver."

### Ekran görüntüleri

<table>
  <tr>
    <td width="50%"><img src="branding/screenshots/workshop.png" alt="Atölye: paket, oyun kalıbı ya da oyun klasörü oluşturma, sıkıştırma seçenekleri" /></td>
    <td width="50%"><img src="branding/screenshots/mcp-tools.png" alt="MCP ve API: yapay zekâ ajanlarının kullanabileceği 128 araç" /></td>
  </tr>
  <tr>
    <td align="center"><b>Atölye</b>: paket, oyun kalıbı ya da oyun klasörü oluşturma</td>
    <td align="center"><b>MCP ve API</b>: ajan araçları</td>
  </tr>
  <tr>
    <td width="50%"><img src="branding/screenshots/upload.png" alt="Yükle ve Kur: paket, oyun, disk imajı ve arşivleri PS5'e gönderme" /></td>
    <td width="50%"><img src="branding/screenshots/payloads.png" alt="Payload'lar: payload gönderme ve oynatma listeleri" /></td>
  </tr>
  <tr>
    <td align="center"><b>Yükle ve Kur</b>: paket, oyun ve dosya gönderme</td>
    <td align="center"><b>Payload'lar</b>: payload gönderme ve oynatma listeleri</td>
  </tr>
</table>

### Gereksinimler

- **Mac:** Apple Silicon (M1 ve sonrası) bir Mac, macOS 11 (Big Sur) veya daha yenisi.
- **PS5:** Jailbreak'li bir PS5 ve çalışan bir ELF yükleyici (port 9021). Sahte paketleri kurmak ve
  çalıştırmak için kstuff gerekir.
- **Ağ:** Mac ve PS5 aynı yerel ağda olmalı.

### İndirme ve kurulum

1. **[PS Gate'i indirin (Apple Silicon Mac, .dmg)](https://github.com/0xxnr/ps-gate/releases/latest/download/PS-Gate-mac-arm64.dmg)**. Tüm sürümler
   [Releases](https://github.com/0xxnr/ps-gate/releases) sayfasında.
2. `.dmg` dosyasını açın ve **PS Gate**'i **Applications** (Uygulamalar) klasörüne sürükleyin.
3. Uygulama ücretli bir Apple sertifikasıyla imzalı değildir; bu yüzden macOS ilk açılışta "hasarlı"
   ya da "açılamıyor" diyebilir. Açmadan önce Terminal'de bir kez şunu çalıştırın:

   ```bash
   xattr -dr com.apple.quarantine "/Applications/PS Gate.app"
   ```

4. PS Gate'i açın. macOS yerel ağ izni istediğinde, PS5'i bulabilmesi için **İzin Ver** deyin.

### İlk kullanım

1. PS5'te jailbreak'i çalıştırın ve ELF yükleyicinin açık olduğundan emin olun.
2. PS Gate'i açın ve sol üstteki **PS5 eklenmedi — eklemek için tıkla** kutusundan ya da
   **Bağlantı** ekranından PS5'inizin IP adresini girin.
3. **Bağlantı** ekranındaki **PS Gate yardımcısını PS5'inize gönderin** adımını tamamlayın.
   Yardımcı, uygulamanın konsolla konuştuğu küçük bir programdır; konsol yeniden başladığında
   tekrar gönderilmesi gerekir.
4. Artık **Yükle ve Kur**, **Oyunlar**, **Dosyalar** ve **Oyna** ekranlarını kullanabilirsiniz.


### Sık sorulan sorular

Uygulamanın **Yardım** ekranındaki soruların tamamı.

#### Başlarken

**PS Gate nedir**

<details>
<summary><b>PS Gate ne işe yarar?</b></summary>

Jailbreak'li bir PS5'i Mac'ten yönetmenizi sağlar: oyun, uygulama ve homebrew gönderip kurar,
konsoldaki dosyaları, oyunları ve kayıtları yönetir, PS5'i Mac'ten oynamanızı sağlar.

</details>

<details>
<summary><b>Hangi PS5 modelleri destekleniyor?</b></summary>

Tüm modeller: ilk seri (CFI-1xxx), Digital, Slim (CFI-2xxx) ve Pro (CFI-7xxx). Konsolun
jailbreak'li olması ve bir ELF yükleyicinin çalışıyor olması gerekir.

</details>

<details>
<summary><b>Ne gerekiyor?</b></summary>

macOS 11 veya daha yenisi olan bir Mac, jailbreak'li bir PS5 ve aynı yerel ağ. Sahte paketleri
kurmak ve çalıştırmak için PS5'te kstuff yüklü olmalı.

</details>

**İlk bağlantı**

<details>
<summary><b>PS5'imi nasıl eklerim?</b></summary>

Sol üstteki **PS5 eklenmedi — eklemek için tıkla** kutusuna ya da **Bağlantı** ekranına tıklayın ve
PS5'in IP adresini girin. IP adresini PS5'te **Ayarlar → Ağ → Bağlantı durumu** altında bulursunuz.

</details>

<details>
<summary><b>"Yardımcı" nedir, neden gönderiyorum?</b></summary>

PS Gate yardımcısı, PS5'te çalışan ve uygulamanın konsolla konuştuğu küçük bir programdır.
**Bağlantı** ekranından gönderilir. Konsol yeniden başlatıldığında silinir ve tekrar gönderilmesi
gerekir; dinlenme modunda genellikle çalışmaya devam eder.

</details>

<details>
<summary><b>Uygulama ilk açılışta açılmıyor ya da "hasarlı" diyor.</b></summary>

PS Gate ücretli bir Apple sertifikasıyla imzalı değildir. Terminal'de bir kez şunu çalıştırın:
`xattr -dr com.apple.quarantine "/Applications/PS Gate.app"`. Ya da Uygulamalar klasöründe PS Gate'e
sağ tıklayıp **Aç**'ı seçin.

</details>

<details>
<summary><b>macOS yerel ağ izni istiyor.</b></summary>

PS Gate'in PS5'i bulup ona bağlanabilmesi için gerekir; **İzin Ver** deyin. Yanlışlıkla
reddettiyseniz **Sistem Ayarları → Gizlilik ve Güvenlik → Yerel Ağ** altından PS Gate'i açın.

---

</details>

#### Bağlantı

**Portlar**

<details>
<summary><b>PS Gate hangi portları kullanıyor?</b></summary>

| Port | Nerede | Ne için |
|---|---|---|
| 9120 TCP | PS5 | Yardımcı: aktarım, dosyalar, yönetim (şifreli) |
| 9021 TCP | PS5 | ELF yükleyici: yardımcıyı göndermek için |
| 9115 TCP | PS5 | Yardımcının başlattığı kurulum aracı |
| 9180 TCP | PS5 | PS Gate Minion, PS5'in tarayıcısında açılan sayfa |
| 19113 TCP | Mac | Motor: Akışla kur sırasında PS5 paketi buradan alır |
| 9295–9304 TCP/UDP | PS5 | Oyna: eşleştirme, uyandırma ve görüntü aktarımı |

</details>

<details>
<summary><b>"Port 9021 açık değil" hatası alıyorum.</b></summary>

9021, jailbreak'in bir parçası olan ELF yükleyicinin portudur. Jailbreak'i yeniden çalıştırın ve
yükleyicinin bildirimini bekleyin. Konsol yeniden başladıysa jailbreak ile ilgili her şey silinmiştir.
Yükleyiciniz başka bir port kullanıyorsa onu **Payload'lar → Payload gönder** ekranında ayarlayın.

</details>

<details>
<summary><b>Yardımcı yanıt vermiyor.</b></summary>

Konsol yeniden başladıysa yardımcıyı **Bağlantı** ekranından tekrar gönderin. Mac ile PS5'in aynı
ağda olduğundan ve macOS'un yerel ağ iznini verdiğinizden emin olun.

</details>

**Dinlenme modu**

<details>
<summary><b>Aktarım sırasında PS5 dinlenme moduna geçerse ne olur?</b></summary>

Aktarım durur ve konsol uyanınca kaldığı yerden devam eder; tamamlanmış dosyalar yeniden
gönderilmez.

</details>

<details>
<summary><b>PS5'in dinlenme moduna geçmesini nasıl engellerim?</b></summary>

**Ayarlar → Konsol → Dinlenme modu** altında üç seçenek vardır: kapalı, yükleme ve kurulum
sırasında (varsayılan) ve bağlıyken her zaman. Uygulamayı kapattığınızda konsol normal düzenine
döner.

---

</details>

#### Yükleme ve kurulum

**Paketler**

<details>
<summary><b>Sahte paketleri Mac'ten kurabilir miyim?</b></summary>

Evet, **Yükle ve Kur** ekranından. PS4 `.pkg` ya da PS5 `.fpkg` dosyasını bırakın; iki yol vardır:

- **Akışla kur** (önerilen): PS5 paketi doğrudan Mac'ten kurar, önce bir kopya oluşturulmaz.
- **Yükle ve kur**: paket önce PS5'e kopyalanır, sonra o kopyadan kurulur.

Sahte paketlerin kurulması ve çalışması için PS5'te kstuff yüklü olmalıdır.

</details>

<details>
<summary><b>Arşivleri açmam gerekiyor mu?</b></summary>

Hayır. `.zip`, `.7z` ve `.rar` arşivleri aktarım sırasında açılır; bilgisayarınıza hiçbir şey
çıkarılmaz. İsterseniz arşivi olduğu gibi de gönderebilirsiniz.

</details>

<details>
<summary><b>Yer yetmezse ne olur?</b></summary>

PS Gate, konsoldaki mevcut dosyaları da hesaba katarak sığmayacak bir işi baştan reddeder.

---

</details>

#### Sorun giderme

**Hata bildirimi**

<details>
<summary><b>Bir hatayı nasıl bildiririm?</b></summary>

Kenar çubuğundaki **Hata bildirimi** ekranı, uygulamanın, motorun ve PS5 yardımcısının
günlüklerini seçtiğiniz zaman aralığı için tek bir `.zip` dosyasında toplar. Adresler, seri
numaraları ve anahtarlar dosyadan çıkarılır. Bu dosyayı GitHub'daki Issues sayfasına ekleyin.

</details>

<details>
<summary><b>Güncellemeler neden kapalı?</b></summary>

PS Gate güncellemeleri GitHub'daki Releases sayfasından elle indirilir. Yeni sürümü kurmak için
`.dmg` dosyasını açıp uygulamayı Uygulamalar klasöründekinin üzerine sürükleyin.

</details>

### API, yapay zekâ asistanları ve otomasyon

PS Gate'in motoru Mac'te `http://127.0.0.1:19113` adresinde bir HTTP API ve bir MCP sunucusu
çalıştırır; betikler ve yapay zekâ asistanları (Claude, Codex, OpenCode, Gemini) PS5'i bunlar
üzerinden yönetebilir. Uygulamadaki **MCP ve API** ekranı kurulum komutlarını, araç listesini
ve API belgesini hazır verir.

### Katkı

Hata bildirimleri ve öneriler için [Issues](https://github.com/0xxnr/ps-gate/issues) sayfasını
kullanın. Uygulamadaki **Hata bildirimi** ekranı, bildirime eklenecek günlükleri hazırlar.

### Lisans

PS Gate, **GNU General Public License v3.0** ile lisanslıdır; tam metin [`LICENSE`](LICENSE)
dosyasında. Bu uygulama, açık kaynak bir çalışmanın değiştirilmiş sürümüdür; telif ve değişiklik
bildirimleri [`NOTICE.md`](NOTICE.md) dosyasında.

Lisans gereği, yayınlanan her sürümün kaynak kodu o sürümün [Releases](https://github.com/0xxnr/ps-gate/releases/latest) sayfasında
`PS-Gate-<sürüm>-kaynak.zip` dosyası olarak indirilebilir; üçüncü taraf lisansları bu arşivdeki
`LICENSES/` klasöründedir.

### Yasal uyarı

PS Gate araştırma, eğitim, birlikte çalışabilirlik ve homebrew geliştirme amaçlıdır. Sony Interactive
Entertainment ile bağlantılı değildir ve onlar tarafından onaylanmamıştır. "PlayStation" ve "PS5",
Sony Interactive Entertainment Inc.'in ticari markalarıdır. Değiştirilmiş bir konsol kullanmak
konsola zarar verebilir, kayıtları silebilir ve hesabınızın yasaklanmasına yol açabilir; tüm risk
size aittir. Yalnızca sahip olduğunuz donanım ve yasal olarak sahip olduğunuz içerikle kullanın.
Ayrıntılar: [`DISCLAIMER.md`](DISCLAIMER.md).

---

## English

PS Gate is a native macOS app for managing a jailbroken PS5 from your Mac: send and install games
and packages, browse and manage the console's files, games and saves, and play the PS5 remotely.
The interface is available in 21 languages.

**Highlights:** resumable, verified transfers over one encrypted connection · Upload & Install for
packages, game folders, disk images and archives · one Games grid for your folders, network shares
and the console · Workshop to build packages and mountable images · save backups and restore ·
remote play with Play Together and live streaming · cheats, fan curve, payload sender · PS Gate
Minion, a controller-friendly page in the PS5's own browser · Workshop options (package, game
image or folder; four compression levels; game language; full verification; convert-and-install
queue; look inside and edit images) · Shared Folders (SMB, FTP, SFTP/WebDAV), Volumes and Clean Up ·
Accounts · console processes, hardware, fan curve, kernel log and a Shell · several devices on one
PS5 with Mesh Drive · activity, logs and notifications · an MCP server
(`http://127.0.0.1:19113/mcp`) so AI agents such as Claude Code, Codex and OpenCode can manage the
PS5 (one-click add for Claude Code, ready-made commands for the others, a searchable list of 128
tools and the HTTP API).

**New in 1.1** (everything ships inside the app, nothing extra to download):
- **Steam Games:** play compatible Steam PC games on a jailbroken PS5. Install, update and open
  **PS Gate Steam** with one button (its Wine, Mesa and DXVK runtime kit comes with PS Gate); sign in
  on the PS5 with a QR code or account name, download your library, or add Windows game folders you
  already have. Direct3D 8–12, OpenGL and Vulkan; controller, keyboard/mouse and up to four local players.
- **Keyboard & Mouse:** plug a USB keyboard and mouse into the PS5 and play with them, no adapter or
  PC needed. **PS Gate KBM** turns them into a virtual DualSense and recognises the game you open:
  51 games with their PC key layout, about 280 more with a genre template, menu navigation when no
  game is open. Live status in PS Gate, a settings page for sensitivity and key binding, an optional
  Home screen icon, a diagnostics mode, and wired Xbox controller support.
- **Switch 2 (experimental):** install **PS Gate NS2** and send the keys, firmware and games you
  dumped from your own console and cartridges. **Pokopia is playable** (45–50 FPS); Donkey Kong
  Bananza and Welcome Tour start but run slowly; other games don't start yet. PS Gate includes no
  keys, firmware or games.
- These need **kstuff**, **ShadowMountPlus** and **elfldr** loaded after each start (plus **nanoDNS**
  for Steam if the PS5's DNS is 127.0.0.1), all on the Payloads screen. Steam Games was tested on
  13.60 and Keyboard & Mouse on 11.60; other firmware is untested. Some online games ban
  keyboard/mouse adapters and modified Steam clients; these features are meant for offline play.

**Requirements:** a Mac with Apple Silicon and macOS 11 or later; a jailbroken PS5 with an ELF loader
(port 9021), and kstuff for fake packages; both on the same local network.

**API & MCP:** the engine serves an HTTP API and an MCP server at `http://127.0.0.1:19113` for
scripts and AI agents; the app's **MCP & API** screen gives the setup commands, tool list and API docs.

**Download:** [PS Gate for Apple Silicon Macs (.dmg)](https://github.com/0xxnr/ps-gate/releases/latest/download/PS-Gate-mac-arm64.dmg) · all versions on the
[Releases](https://github.com/0xxnr/ps-gate/releases) page. Open the `.dmg`, drag **PS Gate** into
**Applications**, then run `xattr -dr com.apple.quarantine "/Applications/PS Gate.app"` once.

**License:** GPL-3.0 (see [`LICENSE`](LICENSE)). PS Gate is a modified version of an open-source
work; copyright and modification notices are in [`NOTICE.md`](NOTICE.md). As the license requires,
each release's source code is attached to it on the [Releases](https://github.com/0xxnr/ps-gate/releases/latest) page as
`PS-Gate-<version>-kaynak.zip`.

**Disclaimer:** for research, education, interoperability and homebrew development only. Not
affiliated with or endorsed by Sony Interactive Entertainment. Use at your own risk, only with
hardware and content you own. See [`DISCLAIMER.md`](DISCLAIMER.md).
