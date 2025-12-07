<!-- ===================== STYLES ======================= -->
<style>
  .title {
    font-size: 32px;
    font-weight: bold;
    padding: 12px 0;
    color: #e63946;
  }
  .subtitle {
    font-size: 22px;
    font-weight: bold;
    color: #1d3557;
    margin-top: 25px;
  }
  .section {
    background: #f8f9fa;
    padding: 14px;
    border-left: 5px solid #457b9d;
    border-radius: 8px;
    margin-top: 8px;
  }
  .feature-list li {
    margin: 6px 0;
  }
  .img-preview {
    border-radius: 10px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.2);
    margin: 10px 0;
  }
</style>

<!-- ===================== HEADER ======================= -->

<h1 align="center" class="title">🎮 Interactive Horror UI – Main Menu Game “The Path”</h1>

<p align="center">
UI Horror interaktif dengan animasi glitch, atmosfer gelap, dan sound ambience untuk menciptakan menu utama yang imersif pada game The Path.
</p>

---

<!-- ===================== DEMO ======================= -->

<h2 class="subtitle">🔥 Demo</h2>

<div class="section">
Tambahkan link demo (YouTube/Drive/GIF) di sini.

<p>
<img src="https://media.giphy.com/media/3oEjI6SIIHBdRxXI40/giphy.gif" width="450" class="img-preview">
</p>
</div>

---

<!-- ===================== FEATURES ======================= -->

<h2 class="subtitle">✨ Fitur Utama</h2>

<div class="section">
<ul class="feature-list">
  <li>🔥 Animasi transisi UI (fade, glitch, hover effect)</li>
  <li>👁 Atmosfer horror yang imersif</li>
  <li>🎵 Efek suara dinamis & ambience loop</li>
  <li>⚙️ Struktur modular, mudah dikembangkan</li>
  <li>🧭 Tampilan dan tema dapat dikustomisasi penuh</li>
</ul>
</div>

---

<!-- ===================== STRUCTURE ======================= -->

<h2 class="subtitle">📁 Struktur Folder</h2>

```
/Assets
  /Scripts
    - MainMenuController.cs
    - AudioManager.cs
    - SceneLoader.cs
  /UI
    /Animations
    /Buttons
    /Fonts
    /SFX
```

---

<!-- ===================== TECHNOLOGY ======================= -->

<h2 class="subtitle">🛠 Teknologi yang Digunakan</h2>

<div class="section">
- Unity 2021+<br>
- C#<br>
- Photoshop / Figma (UI design)<br>
- Audacity / FL Studio (audio)
</div>

---

<!-- ===================== INSTALL ======================= -->

<h2 class="subtitle">📥 Instalasi & Menjalankan</h2>

```
git clone https://github.com/username/ThePath-HorrorUI.git
```

1. Buka project di Unity  
2. Buka scene:  
   ```
   /Assets/Scenes/MainMenu.unity
   ```
3. Tekan **Play**

---

<!-- ===================== PREVIEW UI ======================= -->

<h2 class="subtitle">📌 Preview UI</h2>

<table>
<tr>
<td align="center">
<img src="https://via.placeholder.com/230" class="img-preview"><br>
Halaman utama dengan efek glitch
</td>
<td align="center">
<img src="https://via.placeholder.com/230" class="img-preview"><br>
Tombol hover animasi distortion
</td>
<td align="center">
<img src="https://via.placeholder.com/230" class="img-preview"><br>
Transisi menuju gameplay
</td>
</tr>
</table>

---

<!-- ===================== CODE EXAMPLES ======================= -->

<h2 class="subtitle">💻 Contoh Script</h2>

### Hover Effect (C#)
```csharp
public void OnHover()
{
    animator.SetTrigger("Hover");
    audioManager.Play("hoverSFX");
}
```

### Scene Transition
```csharp
public void PlayGame()
{
    StartCoroutine(LoadSceneWithFade("GameScene"));
}
```

---

<!-- ===================== ROADMAP ======================= -->

<h2 class="subtitle">📚 Roadmap</h2>

- [x] Animasi UI dasar  
- [x] Efek glitch & ambience  
- [ ] Pengaturan audio  
- [ ] Pengaturan grafis  
- [ ] Sistem multi-bahasa  
- [ ] Integrasi cutscene pembuka  

---

<!-- ===================== CONTRIBUTING ======================= -->

<h2 class="subtitle">🤝 Kontribusi</h2>

<div class="section">
Pull Request sangat dipersilakan!  
Harap buat branch baru sebelum melakukan perubahan.
</div>

---

<!-- ===================== LICENSE ======================= -->

<h2 class="subtitle">📄 Lisensi</h2>

Proyek ini menggunakan lisensi **MIT**.

---

<h3 align="center">⭐ Beri Star di GitHub jika proyek ini membantumu!</h3>
