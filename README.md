<div align="center">

# 🚗🌧️ 3D OTONOM KOKPİT: LiDAR vs RADAR LABORATUVARI
### ⚡ *Sürücü Bakış Açısı, Nokta Bulutu Saçılımı ve Mikrodalga Doppler Telemetrisi* ⚡

<br/>

<a href="https://otonom-kokpit-lidar-radar-simulasyo.vercel.app/" target="_blank">
  <img src="https://img.shields.io/badge/CANLI_DEMO-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=00f2fe" alt="Vercel Live Demo" height="38"/>
</a>
<a href="https://www.linkedin.com/in/batuhanbayatlı" target="_blank">
  <img src="https://img.shields.io/badge/LINKEDIN-Profil-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" height="38"/>
</a>

<br/><br/>

<!-- TEKNOLOJİ ROZETLERİ -->
<img src="https://img.shields.io/badge/Motor-Three.js_r128-black?style=flat-square&logo=three.js&logoColor=00ffcc" alt="Three.js"/>
<img src="https://img.shields.io/badge/Grafik-WebGL_2.0-red?style=flat-square&logo=webgl&logoColor=white" alt="WebGL"/>
<img src="https://img.shields.io/badge/Perspektif-3B_Sürücü_POV-blue?style=flat-square" alt="POV"/>
<img src="https://img.shields.io/badge/Mimari-Sıfır_Kurulum_Saf_JS-yellow?style=flat-square&logo=javascript&logoColor=black" alt="JS"/>
<img src="https://img.shields.io/badge/Lisans-MIT-emerald?style=flat-square" alt="License"/>

<br/><br/>

> 🎯 **Otonom araçların dünyayı nasıl algıladığını doğrudan direksiyon başından deneyimleyin!**  
> Yağmurlu ve sisli bir şehir bulvarında, gerçekçi trafik akışında LiDAR'ın optik sınırları ile RADAR'ın sis delici Doppler yeteneğini yan yana inceleyin.

---

</div>

<br/>

## 🌟 TEMEL SİSTEM ÖZELLİKLERİ

<table>
  <tr>
    <td width="50%">
      <h3>🛰️ Sol Ekran: LiDAR (905 nm Lazer)</h3>
      <p>Binaların cephelerini, ön tamponları ve yol bariyerlerini milimetrik <b>3B nokta bulutu (Point Cloud)</b> olarak haritalandırır. Ancak yoğun sis ve yağmur damlalarında lazer ışınları saçılarak menzil ~30 metreyle sınırlandırılır ve optik gürültü oluşur.</p>
    </td>
    <td width="50%">
      <h3>📡 Sağ Ekran: RADAR (77 GHz mmWave)</h3>
      <p>Milimetrik radyo dalgaları sisi, suyu ve fırtınayı sıfır kayıpla delip geçer. Binaları arka plan olarak filtrelerken, öndeki araçları <b>Sınırlayıcı Kutu (Bounding Box)</b> ve <b>Doppler bağıl hız vektörleri</b> ile anında yakalar.</p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>🚗 3B Kokpit & Fonksiyonel Direksiyon</h3>
      <p>Sürücü gözü hizasından (POV); A-sütunları, dikiz aynası, konsol göğsü, vites tüneli ve yoldaki mikro virajlara göre dinamik dönen 3B spor deri direksiyon simülasyonu.</p>
    </td>
    <td width="50%">
      <h3>🛡️ Çarpışmasız Trafik & Vites/Devir Uyumu</h3>
      <p>Gerçekçi şehir içi seyir hızları (40–55 km/s). Öndeki araçlar fren yaptığında arka stop lambaları yanar ve Adaptif Hız Sabitleyici (ACC) takip mesafesini korur; araçlar asla iç içe geçmez.</p>
    </td>
  </tr>
</table>

---

## 📐 SENSÖR FİZİĞİ & KARŞILAŞTIRMA TABLOSU

| Parametre | 🛰️ LiDAR (Işık ile Tespit ve Menzil) | 📡 RADAR (Radyo Dalgaları ile Tespit) |
| :--- | :--- | :--- |
| **Taşıyıcı Dalga** | Kızılötesi Işık (~905 nm) | Milimetrik Radyo Dalgası (~77 GHz) |
| **Geometrik Çözünürlük** | **Çok Yüksek:** Detaylı yüzey ve kontur tespiti | **Düşük / Orta:** Kaba hedef kümeleme kutusu |
| **Atmosferik Dayanıklılık** | **Kırılgan:** Sis ve yağmurda optik sönümleme | **Kusursuz:** Sis, toz ve yağmuru kayıpsız deler |
| **Hız Tespiti** | Dolaylı (Ardışık kare takibi) | **Doğrudan:** Doppler frekans kayması |

---

## 🚀 HIZLI BAŞLANGIÇ

Proje herhangi bir derleme adımı (build step) veya harici paket yüklemesi gerektirmez:

1. Depoyu klonlayın:
   git clone https://github.com/batuhanbayatli/otonom-kokpit-lidar-radar-simulasyonu

2. Proje dizinine gidin:
   cd otonom-kokpit-lidar-radar-simulasyo

3. index.html dosyasını doğrudan tarayıcınızda açın veya VS Code Live Server ile başlatın.

Doğrudan tarayıcıda canlı denemek için:  
👉 [otonom-kokpit-lidar-radar-simulasyo.vercel.app](https://otonom-kokpit-lidar-radar-simulasyo.vercel.app/) 🎯

---

## 👨‍💻 PROJE GELİŞTİRİCİSİ

<div align="center">
  <b>BATUHAN BAYATLI</b><br/>
  
  <a href="https://www.linkedin.com/in/batuhanbayatlı" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Bağlantı_Kur-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://otonom-kokpit-lidar-radar-simulasyo.vercel.app/" target="_blank">
    <img src="https://img.shields.io/badge/Canlı_Demo-Vercel-black?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel"/>
  </a>
  <br/><br/>
  <sub>MIT Lisansı ile korunmaktadır. © 2026 Batuhan Bayatlı.</sub>
</div>
