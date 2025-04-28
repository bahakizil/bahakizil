<!--
  README.md for Baha Kızıl's GitHub Profile
  Dynamic, self-updating, rich with badges and live metrics
-->

<!-- START: Profile Header -->
<div align="center">
  <h1>👋 Merhaba, ben Baha Kızıl</h1>
  <p>Mechatronics Engineer | AI & Computer Vision Enthusiast | R&D Intern @TAV Technologies</p>
  
  <!-- Profile Views Badge -->
  <img src="https://komarev.com/ghpvc/?username=bahakizil&color=blue&style=flat" alt="Profile views" />

  <!-- Social Links -->
  <p>
    <a href="https://www.linkedin.com/in/bahakizil/">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&style=flat-square" alt="LinkedIn" />
    </a>
    <a href="https://medium.com/@bahakizil">
      <img src="https://img.shields.io/badge/Medium-000000?logo=medium&style=flat-square" alt="Medium" />
    </a>
    <a href="mailto:kizilbaha26@gmail.com">
      <img src="https://img.shields.io/badge/Email-D14836?logo=gmail&style=flat-square" alt="Email" />
    </a>
  </p>
</div>
<!-- END: Profile Header -->

---

## 🔭 Güncel Çalışmalarım
- Gerçek zamanlı CCTV analiz projeleri (YOLO, DeepStream, Jetson Orin)
- Smart Growbox AI & IoT entegrasyonları
- FPGA & CUDA hızlandırmalı derin öğrenme çözümleri

## 💼 Deneyimlerim
- **R&D Intern**, TAV Technologies (Time Series Analysis, Action Recognition, Object Detection)
- Freelance AI Developer (Upwork): ISO 9001 SaaS Doc Gen, Traffic Monitoring

## 🛠 Teknoloji & Araçlar
<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&style=flat-square" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&style=flat-square" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&style=flat-square" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&style=flat-square" />
  <img src="https://img.shields.io/badge/DeepStream-30B0F0?style=flat-square" />
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&style=flat-square" />
  <img src="https://img.shields.io/badge/Git-F05032?logo=git&style=flat-square" />
</p>

---

## 📈 GitHub İstatistiklerim
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=bahakizil&show_icons=true&theme=radical" alt="GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=bahakizil&hide=jupyter%20notebook&layout=compact&theme=radical" alt="Top languages" />
</div>

---

## 📰 Son Blog Yazılarım
<!-- BLOG-POST-LIST:START -->
<!-- Bu alan GitHub Action tarafından her gece güncellenecektir -->
<!-- BLOG-POST-LIST:END -->

> **Nasıl Kurulur:**
> 1. Projeye aşağıdaki GitHub Action dosyasını ekleyin: `.github/workflows/update-readme.yml`
> 2. Ortam değişkenleri olarak `MEDIUM_USERNAME: "bahakizil"` ve `GITHUB_TOKEN` ayarlayın.
> 3. Action, her gece Medium RSS akışınızı çekerek `<-- BLOG-POST-LIST -->` bölümünü güncelleyecek.

```yaml
# .github/workflows/update-readme.yml
ame: Update README with Medium Posts
on:
  schedule:
    - cron: '0 0 * * *' # Her gece 00:00 UTC
jobs:
  update-readme:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - uses: rahuldkjain/github-readme-medium@v1
        with:
          github_token: ${{ secrets.GITHUB_TOKEN }}
          medium_username: ${{ secrets.MEDIUM_USERNAME }}
      - name: Commit changes
        run: |
          git config --local user.name 'github-actions[bot]'
          git config --local user.email 'github-actions[bot]@users.noreply.github.com'
          git add README.md
          git commit -m '📝 Update blog posts' || echo 'No changes'
      - uses: actions/push@v3
        with:
          github_token: ${{ secrets.GITHUB_TOKEN }}
```

---

## 📫 Bana Ulaşın
- 📧 [kizilbaha26@gmail.com](mailto:kizilbaha26@gmail.com)
- 🔗 [LinkedIn](https://www.linkedin.com/in/bahakizil/)
- 📰 [Medium](https://medium.com/@bahakizil)

---

<p align="center">Made with ❤️ by Baha Kızıl</p>
