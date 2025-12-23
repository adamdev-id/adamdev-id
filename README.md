<!-- Header -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=220&text=adamdev-id&fontAlign=50&fontAlignY=40&color=0:0ea5e9,100:6366f1&fontColor=ffffff" />
</div>

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=700&size=28&pause=1000&color=00C2FF&center=true&vCenter=true&width=900&lines=Government+GIS+%26+Data+Developer;ASP.NET+Core+%7C+C%23+%7C+Java+%7C+Lua;Tax+%26+Compliance+Analytics;Simplicity+over+complexity." alt="Typing SVG" />
</div>

<br/>

<div align="center">
  <a href="https://github.com/adamdev-id">
    <img src="https://img.shields.io/badge/GitHub-adamdev--id-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://id.linkedin.com/in/adamfriska">
    <img src="https://img.shields.io/badge/LinkedIn-adamfriska-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:id.adamdev@gmail.com">
    <img src="https://img.shields.io/badge/Email-id.adamdev%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <img src="https://img.shields.io/badge/Discord-typeshit1st-5865F2?style=for-the-badge&logo=discord&logoColor=white" />
</div>

<br/>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=adamdev-id&style=for-the-badge&color=0ea5e9" alt="Profile Views"/>
</div>

---

## 🧭 Snapshot

<table>
<tr>
<td width="60%">

### 👋 About
I build software for **government data systems**, **GIS workflows**, and **decision-ready reporting** — focusing on clarity, accuracy, and maintainability.

- 🔄 Multi-source data integration + reconciliation for reporting (incl. **Sekretaris Daerah**)
- 🤝 Work with **DPRD / stakeholders / leaders** to align needs → requirements → delivery
- 🧾 Tax/Data analytics to measure **“Tingkat Kepatuhan” WP** and flag potential **underpayment risks** for review

</td>
<td width="40%">

### 🎯 Focus Areas
- Government GIS & data visualization  
- ASP.NET Core apps & APIs  
- Desktop tools (Java / C#)  
- Automation & scripting (Lua)  
- Cloud & enterprise deployment

</td>
</tr>
</table>

---

## 🧰 Toolbox

### 👨‍💻 Languages
![C#](https://img.shields.io/badge/-C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![Java](https://img.shields.io/badge/-Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Lua](https://img.shields.io/badge/-Lua-2C2D72?style=for-the-badge&logo=lua&logoColor=white)

### 🌐 Web / Backend
![ASP.NET Core](https://img.shields.io/badge/-ASP.NET%20Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![.NET](https://img.shields.io/badge/-.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)

### 🗃️ Databases
![Oracle](https://img.shields.io/badge/-Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![SQL Server](https://img.shields.io/badge/-SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### ☁️ Cloud / Hosting
![IIS](https://img.shields.io/badge/-IIS-0078D4?style=for-the-badge&logo=windows&logoColor=white)
![Azure](https://img.shields.io/badge/-Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Google Cloud](https://img.shields.io/badge/-Google%20Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)

### 🧰 Tools
![Git](https://img.shields.io/badge/-Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/-VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Visual Studio](https://img.shields.io/badge/-Visual%20Studio-5C2D91?style=for-the-badge&logo=visualstudio&logoColor=white)

---

## 🚀 Featured Build

### 🧾 POS ByteStream Interceptor (C#) — Transaction Stream Analyzer
- Built for **authorized testing environments** (VM / testing PC) supporting **tax data collection & fiscal reporting**
- Captures **serial (COM/PORT) transaction byte streams** via a controlled monitoring layer, forwards to an analysis core
- Converts **HexStream → readable text**, structures into transaction records
- Uses **AI-assisted extraction** to capture:
  - item name / qty (if present)
  - item price
  - item amount
  - total purchase / summary fields
- Output-ready for reporting pipelines (**JSON/CSV**), dashboards, and audit review  
- 🔒 Focused on **compliance, traceability, and data validation** (test environment, controlled access)

#### Service → Brain → Agent (high-level)
```mermaid
flowchart LR
  A[COM/PORT Stream] --> B[Capture Service]
  B --> C[Analyzer / "Brain"\nParse + Normalize + AI Extraction]
  C --> D[Agent UI\nNear real-time display]
  C --> E[Exports\nJSON / CSV / Reporting Pipeline]
