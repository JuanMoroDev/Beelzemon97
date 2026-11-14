<h1 align="center">Hi, I'm Juan Moroyoqui 👋</h1>

<p align="center">
  <a href="https://github.com/JuanMoroDev">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&color=2EA043&center=true&vCenter=true&width=600&lines=.NET+Developer+%26+Electronics+%2F+Semiconductors;ASP.NET+Core+%C2%B7+.NET+MAUI+%C2%B7+Azure;Semiconductors+%C2%B7+Digital+design+%C2%B7+PCB;Embedded+AI+on+STM32" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/juan-alfonso-moroyoqui-delgadillo-12b32b334/"><img src="https://img.shields.io/badge/LinkedIn-Juan_Moroyoqui-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <img src="https://img.shields.io/badge/ITESCA-Postgraduate_in_Semiconductors-6E40C9?style=for-the-badge" alt="ITESCA, postgraduate in semiconductors" />
</p>

---

## 🧠 About me

I work on both sides of the stack: **software** and **electronics**.

- 💻 **Software**: .NET developer who designs and delivers **end-to-end solutions** for real industrial environments, from the REST API and the database to the desktop and mobile apps that crews use in the field.
- ⚡ **Electronics & semiconductors**: postgraduate student in **Semiconductors** at **ITESCA**, with hands-on work in PCB design, digital logic and embedded AI. With the **ITESCA PCB Lab** team I designed a PCB that runs a **TinyML model on an STM32** to diagnose bearing faults from vibration.

**Right now**

- 🔭 Building **SICRY**, a maintenance management platform in production for an irrigation district
- 🎓 Postgraduate studies in **Semiconductors** at ITESCA (Instituto Tecnológico Superior de Cajeme)
- 🔌 Working on **AI-SED-PCB** with the ITESCA PCB Lab team, embedded AI for predictive maintenance (AI-SED 2026)
- 🔬 Getting into digital design with **Verilog**
- 🌱 Learning **Angular** to round out my full-stack skills

---

## 🛠️ Tech stack

**Backend & cloud**

![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Entity Framework](https://img.shields.io/badge/EF_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

**Apps**

![.NET MAUI](https://img.shields.io/badge/.NET_MAUI-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![XAML](https://img.shields.io/badge/XAML-0C54C2?style=flat-square&logo=xaml&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

**Electronics, semiconductors & embedded**

![Semiconductors](https://img.shields.io/badge/Semiconductors-6E40C9?style=flat-square)
![Digital logic](https://img.shields.io/badge/Digital_logic-Logisim-1F6FEB?style=flat-square)
![Verilog](https://img.shields.io/badge/Verilog-learning-6E40C9?style=flat-square)
![PCB design](https://img.shields.io/badge/PCB_design-Proteus-1F6FEB?style=flat-square)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![TensorFlow Lite](https://img.shields.io/badge/TensorFlow_Lite-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)

---

## 🏗️ Featured projects

### [SICRY](https://github.com/JuanMoroDev/SICRY): Industrial Maintenance Management System

End-to-end platform that digitizes maintenance operations for the Distrito de Riego del Río Yaqui irrigation district.

- **API**: ASP.NET Core, EF Core, JWT with role-based access, Azure SQL, Blob Storage for evidence
- **Desktop app** (.NET MAUI) for supervisors: dashboard, assignments, catalogs and reports
- **Mobile app** (.NET MAUI) for field technicians: tasks and technical reports
- **DevOps**: Azure App Service with CI/CD on GitHub Actions

<p align="center">
  <a href="https://github.com/JuanMoroDev/SICRY"><img src="https://raw.githubusercontent.com/JuanMoroDev/SICRY/main/docs/screenshots/dashboard.png" width="85%" alt="SICRY dashboard" /></a>
</p>

### [AI-SED-PCB](https://github.com/JuanMoroDev/AI-SED-PCB): Embedded-AI bearing-fault diagnosis

**ITESCA PCB Lab** project for **AI-SED 2026** (AI Smart Electronic Design), developed as part of my postgraduate studies in semiconductors.

- **Hardware**: 5 × 5 cm two-layer board with an STM32F411, an IIS3DWB vibration accelerometer and an ESP32-C3 for Wi-Fi / Bluetooth. Routed with 0 DRC errors, with Gerber files and bill of materials ready for fabrication.
- **AI model**: TinyML classifier (MLP, 1,332 parameters) that tells a healthy bearing from inner-race, ball and outer-race faults, with **100% accuracy on unseen load data**.
- **Firmware**: C inference pipeline identical to Python on 9,215 windows, simulated on the STM32 in Proteus VSM (16/16 correct).

<p align="center">
  <a href="https://github.com/JuanMoroDev/AI-SED-PCB"><img src="https://raw.githubusercontent.com/JuanMoroDev/AI-SED-PCB/main/docs/placa_ruteada.png" width="45%" alt="AI-SED routed PCB" /></a>
</p>

### More

| Project | Description | Stack |
|---|---|---|
| [CPU](https://github.com/JuanMoroDev/CPU) | Microprogrammed 8-bit processor and x86-style ALU | Logisim-evolution |

---

## 📊 GitHub stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=JuanMoroDev&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub stats" />
  <img height="165" src="https://streak-stats.demolab.com/?user=JuanMoroDev&theme=tokyonight&hide_border=true" alt="GitHub streak" />
</p>
