<div style="background: linear-gradient(135deg, #0a0a0a 0%, #1a2a3a 100%); color:#fff; padding:30px; border-radius:10px; box-shadow: 0 10px 30px rgba(0,200,100,0.2); overflow: hidden; position: relative;">
  
  <!-- Background Animasi -->
  <div style="position: absolute; top:0; left:0; width:100%; height:100%; z-index:0; opacity:0.1;">
    <div style="position: absolute; top:10%; left:5%; width:50px; height:50px; border-radius:50%; background: #4CAF50; animation: float 15s infinite ease-in-out;"></div>
    <div style="position: absolute; top:70%; left:80%; width:70px; height:70px; border-radius:50%; background: #FF2D20; animation: float 12s infinite ease-in-out reverse; animation-delay: 2s;"></div>
    <div style="position: absolute; top:40%; left:90%; width:30px; height:30px; border-radius:50%; background: #0175C2; animation: float 18s infinite ease-in-out; animation-delay: 4s;"></div>
  </div>

  <div align="center" style="position: relative; z-index: 1;">
    <h1 style="color: #4CAF50; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; font-size: 2.8rem; text-shadow: 0 0 10px rgba(76, 175, 80, 0.5); animation: fadeIn 1.5s ease-out;">
      Assalamu'alaikum, Saya Alghifari888
    </h1>

    <p style="font-size: 18px; font-style: italic; color: #ddd; max-width: 600px; margin: 20px auto; padding: 10px; border-left: 3px solid #4CAF50; background: rgba(20,30,40,0.5); animation: slideIn 1s ease-out;">
      "Aku tidak berilmu; yang berilmu hanyalah DIA. Jika tampak ilmu dariku, itu hanyalah pantulan dari Cahaya-Nya."
    </p>

    <br>

    <div style="border-radius: 50%; overflow: hidden; width: 250px; height: 250px; margin: 0 auto; border: 3px solid #4CAF50; box-shadow: 0 0 20px rgba(76, 175, 80, 0.5); animation: pulse 4s infinite alternate;">
      <img src="profil2.gif" width="100%" style="display: block; transition: transform 0.5s;" onmouseover="this.style.transform='scale(1.05)'" onmouseout="this.style.transform='scale(1)'"/>
    </div>
  </div>

  <!-- Animasi CSS -->
  <style>
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(-20px); }
      to { opacity: 1; transform: translateY(0); }
    }
    @keyframes slideIn {
      from { opacity: 0; transform: translateX(-50px); }
      to { opacity: 1; transform: translateX(0); }
    }
    @keyframes pulse {
      0% { box-shadow: 0 0 20px rgba(76, 175, 80, 0.5); }
      100% { box-shadow: 0 0 40px rgba(76, 175, 80, 0.8); }
    }
    @keyframes float {
      0% { transform: translateY(0) translateX(0); }
      50% { transform: translateY(-30px) translateX(20px); }
      100% { transform: translateY(0) translateX(0); }
    }
    .badge-animate {
      transition: all 0.3s ease;
    }
    .badge-animate:hover {
      transform: scale(1.1) translateY(-5px);
      box-shadow: 0 5px 15px rgba(0,0,0,0.3);
    }
    .project-card {
      transition: all 0.4s ease;
    }
    .project-card:hover {
      transform: translateY(-10px);
      box-shadow: 0 15px 30px rgba(0,0,0,0.4) !important;
    }
  </style>

  <!-- Bagian selanjutnya tetap sama, hanya tambahkan class animasi -->
  <!-- ... (bagian Profil Saya) ... -->

  <div align="center">
    <h2>🧭 <strong>Profil Saya</strong></h2>
  </div>

  <div align="center" style="max-width: 800px; margin: 0 auto; line-height: 1.6; position: relative; z-index: 1;">
    <!-- ... (konten profil) ... -->
  </div>

  <!-- Keahlian Teknis dengan efek hover -->
  <div align="center" style="position: relative; z-index: 1;">
    <h2>🛠️ <strong>Keahlian Teknis</strong></h2>
    <!-- Ganti badge dengan menambahkan class -->
    <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" class="badge-animate" style="margin: 5px;">
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" class="badge-animate" style="margin: 5px;">
    <!-- ... (badge lainnya) ... -->
  </div>

  <!-- Project dengan animasi hover -->
  <div align="center" style="position: relative; z-index: 1;">
    <h2>🏆 <strong>Project Saya</strong></h2>
    <table>
      <tr>
        <td align="center">
          <a href="https://github.com/Alghifari888/website-manajemen-perpustakaan" class="project-card" style="display: inline-block;">
            <img src="https://github-readme-stats.vercel.app/api/pin/?username=Alghifari888&repo=website-manajemen-perpustakaan&theme=radical" width="400" style="border-radius: 10px; box-shadow: 0 5px 15px rgba(0,0,0,0.2);">
          </a>
        </td>
        <!-- ... (project lainnya) ... -->
      </tr>
    </table>
  </div>

  <!-- ... (bagian statistik dan footer) ... -->

  <div align="center" style="position: relative; z-index: 1;">
    <img src="https://media.giphy.com/media/ZVik7pBtu9dNS/giphy.gif" width="150px" style="border-radius: 50%; border: 2px solid #4CAF50; margin-top: 20px;">

    <h3 style="animation: fadeIn 2s ease-in; text-shadow: 0 0 8px rgba(76, 175, 80, 0.7);"> 
      "Kode yang baik itu seperti puisi - indah, bermakna, dan mudah dimengerti"
    </h3>
  </div>
</div>
