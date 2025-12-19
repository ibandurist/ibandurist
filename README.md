<div align="center">
  <h1>Ivan Stepanov</h1>
  <h3>Technical Sound Designer | Unity & FMOD</h3>
  <p>
    I bridge the gap between creative sound design and low-level code.<br>
    Specialized in building scalable audio architectures, procedural acoustic systems, and tooling for Unity.
  </p>

  <div>
    <a href="https://www.linkedin.com/in/sound-designer-ivan/" target="_blank"> 
      <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin" alt="LinkedIn" />
    </a>
    <a href="mailto:gameaudioivan@gmail.com">
      <img src="https://img.shields.io/badge/Email-Contact_Me-c14438?style=for-the-badge&logo=gmail" alt="Email" />
    </a>
  </div>
</div>

<br />
<div align="center">
  
### Tech Stack & Audio Middleware

| Core Engineering | Audio Middleware | Workflow & Tools |
| :--- | :--- | :--- |
| ![C#](https://img.shields.io/badge/C%23-Scripting-239120?style=flat&logo=c-sharp&logoColor=white)<br>![Unity](https://img.shields.io/badge/Unity-Engine_API-100000?style=flat&logo=unity&logoColor=white)<br>![Optimization](https://img.shields.io/badge/Performance-Memory_Opt-red?style=flat) | ![FMOD Core](https://img.shields.io/badge/FMOD_Core_API-C%23_Wrapper-239120?style=flat&logo=c-sharp&logoColor=white)<br>![FMOD Studio](https://img.shields.io/badge/FMOD_Studio-Middleware-black?style=flat&logo=fmod&logoColor=white)<br>![Wwise](https://img.shields.io/badge/Wwise-Implementation-0536C0?style=flat&logo=audiokinetic&logoColor=white) | ![Ableton](https://img.shields.io/badge/Ableton_Live-000000?style=flat&logo=abletonlive&logoColor=white)<br>![Reaper](https://img.shields.io/badge/Reaper-Scripting-196F3D?style=flat&logo=reaper&logoColor=white)<br>![Git](https://img.shields.io/badge/Git-Version_Control-F05032?style=flat&logo=git&logoColor=white) |
</div>

<br />

### Featured Engineering Projects

#### 1. Procedural Acoustics & Volumetric Occlusion
**Stack:** `Unity` `C#` `FMOD` `Raycasting` `Fibonacci Sampling`

> *Automated environmental audio system that removes the need for manual Reverb Zones placement.*

<table>
<tr>
<td width="55%">
<br>
This system allows sound sources to "hear" the geometry around them.
<br><br>
<ul>
    <li><b>Volumetric Raycasting:</b> Real-time calculation of diffraction and occlusion based on player position and geometry.</li>
    <li><b>Room Scanning:</b> Uses Fibonacci Sphere Sampling to dynamically calculate Room Size and Reverb Amount.</li>
    <li><b>Smart Filtering:</b> Prevents false occlusion when close to walls using proximity logic.</li>
    <li><b>Result:</b> Level designers simply drop the prefab, and acoustics work automatically.</li>
</ul>
<br>
<a href="https://github.com/ibandurist/UnityFMOD.ProceduralAcoustics"><b>👉 View Repository</b></a>
</td>
<td width="45%">
    <img src="image/ProceduralAcoustics.png" alt="Console Engine" width="100%">
</td>
</tr>
</table>

<br />

#### 2. TinyArcade: Custom C# Game Engine
**Stack:** `C#` `FMOD Core API` `Custom Physics` `Double Buffering`

> *A custom-built game engine running in a Windows Console to master low-level architecture.*

<table>
<tr>
<td width="55%">
<br>
Built from scratch to understand engine architecture beyond high-level wrappers.
<br><br>
<ul>
    <li><b>Direct FMOD Integration:</b> Bypassed Unity/Unreal wrappers to communicate directly with FMOD Core API via C# bindings.</li>
    <li><b>Custom Audio System:</b> Implemented channel groups (Music, SFX, UI) and real-time DSP mixing.</li>
    <li><b>Spatial Audio Logic:</b> Dynamic Low-Pass filters and Reverb based on spatial coordinates in a text-based grid.</li>
    <li><b>Rendering:</b> Custom double-buffering rendering engine for flicker-free console graphics.</li>
</ul>
<br>
<a href="https://github.com/ibandurist/TinyArcade.ConsoleGameEngine"><b>👉 View Repository</b></a>
</td>
<td width="45%">
    <img src="image/ConsoleEngine.png" alt="Console Engine" width="100%">
</td>
</tr>
</table>

<br />

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ibandurist&layout=compact&theme=gotham&hide_border=true&langs_count=6" alt="Top Languages" height="150" />
</p>
