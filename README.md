<h1 align="center">👋 HI, I'M <span style="color:#00BFFF;">CHI</span></h1>

<!-- Container ใส่ Pacman GIF + ข้อความแบบไล่สี RGB -->
<div align="center" style="display: flex; align-items: center; justify-content: center; gap: 15px; margin: 20px 0;">

  <!-- Pacman GIF -->
  <div style="border: 3px solid; border-radius: 20px; padding: 8px; animation: rgbGlow 5s linear infinite;">
    <img src="https://www.c64-wiki.com/images/8/89/PacMan_Animation1.gif" alt="Pacman" width="60" style="display: block;" />
  </div>

  <!-- ข้อความแบบกล่องไล่สี RGB + ฟอนต์สวย -->
  <div style="
    font-family: 'Trebuchet MS', Verdana, Tahoma, sans-serif;
    font-weight: bold; 
    font-size: 16px; 
    padding: 12px 20px; 
    border-radius: 20px; 
    color: white;
    animation: rgbGlow 5s linear infinite;
    border: 3px solid;
  ">
    💻 Web App Developer | 🎓 Computer Science Student
  </div>

</div>

<!-- CSS animation แบบ inline ใน markdown -->
<style>
  @keyframes rgbGlow {
    0% { border-color: rgb(255, 0, 0); background-color: rgba(255, 0, 0, 0.3); }
    25% { border-color: rgb(0, 255, 0); background-color: rgba(0, 255, 0, 0.3); }
    50% { border-color: rgb(0, 0, 255); background-color: rgba(0, 0, 255, 0.3); }
    75% { border-color: rgb(255, 255, 0); background-color: rgba(255, 255, 0, 0.3); }
    100% { border-color: rgb(255, 0, 0); background-color: rgba(255, 0, 0, 0.3); }
  }
</style>
