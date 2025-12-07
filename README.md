<h1 align="center">🎮 Interactive Horror UI – Main Menu Game “The Path”</h1>

<p align="center">
UI Horror interaktif dengan efek glitch, atmosfer gelap, dan animasi transisi untuk menghadirkan pengalaman menu utama yang imersif.
</p>

---

## 🚀 Demo

### 🎥 Preview / Rekaman
Tambahkan link demo di sini:

<p align="center">
  <img src="https://media.giphy.com/media/3oEjI6SIIHBdRxXI40/giphy.gif" width="500">
</p>

---

## ✨ Fitur Utama

- 🔥 Animasi glitch, fade, dan hover effect  
- 👁 Tema horror atmosferik  
- 🎵 Efek suara dinamis & ambience  
- 🧭 Struktur modular  
- ⚙️ Customizable UI theme  

---

## 📁 Struktur Folder
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

## 🛠 Teknologi
- Unity 2021+  
- C#  
- Photoshop / Figma  
- Audacity / FL Studio  

---

## 📥 Cara Instalasi

```bash
git clone https://github.com/username/ThePath-HorrorUI.git
```

1. Buka project di Unity  
2. Masuk ke scene:
   ```
   /Assets/Scenes/MainMenu.unity
   ```
3. Tekan **Play**

---

## 📌 Preview UI

<table align="center">
<tr>
<td align="center">
  <img src="https://via.placeholder.com/240" width="240"><br>
  Halaman Utama (Efek Glitch)
</td>
<td align="center">
  <img src="https://via.placeholder.com/240" width="240"><br>
  Hover Button Effect
</td>
<td align="center">
  <img src="https://via.placeholder.com/240" width="240"><br>
  Transisi ke Gameplay
</td>
</tr>
</table>

---

## 💻 Contoh Script

### Hover Effect
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

## 📚 Roadmap
- [x] Animasi UI dasar  
- [x] Efek glitch  
- [ ] Pengaturan audio  
- [ ] Pengaturan grafis  
- [ ] Cutscene pembuka  

---

## 🤝 Kontribusi
Pull Request dipersilakan.  
Buat branch baru sebelum melakukan perubahan.

---

## 📄 Lisensi
MIT License.

---

<p align="center"><b>⭐ Beri Star jika proyek ini bermanfaat!</b></p>
