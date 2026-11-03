<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=BD93F9&center=true&vCenter=true&width=600&lines=Ol%C3%A1%2C+eu+sou+o+Paulo+Souza+%F0%9F%91%8B;Desenvolvedor+Pleno+%F0%9F%92%BB;TypeScript+%2B+Vue+%2B+WebRTC+%F0%9F%93%9E;Telefonia+na+web+%C3%A9+comigo+%E2%9A%A1" alt="Olá, eu sou o Paulo Souza" />

<p>
  <a href="https://www.linkedin.com/in/paulo-souza-82a123248"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:paulo18santos2000@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" /></a>
  <a href="https://www.npmjs.com/package/easy-sipjs"><img src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white" alt="npm" /></a>
  <img src="https://komarev.com/ghpvc/?username=phs-santos&label=Visitas&color=bd93f9&style=for-the-badge" alt="Visitas ao perfil" />
</p>

</div>

---

## 🧑‍💻 Sobre mim

- 💼 Desenvolvedor **Pleno** na **56k - Pxtalk**, em Matão - SP
- 📞 Trabalho com **telefonia na web**: softphones, **SIP**, **WebRTC** e integração com PBX (Asterisk)
- ⚡ No dia a dia: **TypeScript**, **Vue 3** e **Node.js**
- 📡 Desenvolvo o **PX Edge**, equipamento de portaria remota que funciona mesmo sem internet
- 🖥️ Também faço apps desktop com **Electron**
- 🌱 Estudando agora: **C# / .NET**, **SQL** e **BI**
- 📕 Nas horas vagas: leitura e natureza 🌲

---

## 🏢 O que eu construo na Pxtalk

### 📡 PX Edge

Equipamento *plug-and-play* para **portarias remotas de condomínios**. Junta num só aparelho o roteador, o PABX IP e o relay de câmeras, e continua funcionando **mesmo sem internet** (*offline first*). Interfonia, câmeras e acesso seguem ativos dentro do condomínio quando o link cai.

- Painel web que roda **dentro do próprio roteador MikroTik**, em containers
- **PBX IP** com Asterisk: ramais, troncos, rotas de ligação e log de chamadas
- **Câmeras IP**: proxy RTSP e envio do stream por RTMP
- Gestão de rede: WAN/LAN, firewall, failover entre dois links e VPN WireGuard

<table>
  <tr>
    <td colspan="2"><img src="assets/pxedge-login.png" alt="Tela de login do PX Edge" /></td>
  </tr>
  <tr>
    <td width="50%"><img src="assets/pxedge-chamadas.png" alt="Log de chamadas do PX Edge" /></td>
    <td width="50%"><img src="assets/pxedge-camera.png" alt="Cadastro de câmera IP no PX Edge" /></td>
  </tr>
</table>

<sub>**Stack:** Nuxt · Go · Asterisk · MikroTik RouterOS · MediaMTX · Caddy · WireGuard · SQLite</sub>

### ☎️ Pxtalk: módulo de Call Center

Plataforma de atendimento da Pxtalk, com três painéis: o do **agente**, que atende pelo próprio ramal, o do **gestor** e o **monitor de filas** em tempo real. Também inclui um SDK de eventos usado pelos painéis.

<p align="center">
  <img width="85%" src="assets/pxtalk-agente.png" alt="Tela de entrada do painel do agente" />
</p>

<sub>**Stack:** Nuxt · Fastify · Firebase · TypeScript · Playwright</sub>

---

## 🚀 Projetos open source

| Projeto | O que é | Stack |
| --- | --- | --- |
| 📦 **[easy-sipjs](https://github.com/phs-santos/easy-sipjs)** | SDK de softphone WebRTC/SIP publicado no [npm](https://www.npmjs.com/package/easy-sipjs). Você passa ramal, domínio e senha, e a biblioteca cuida de registro, reconexão, DTMF, qualidade de chamada e presença | TypeScript · SIP.js · Vitest |
| 🌈 **[Íris](https://github.com/phs-santos/iris)** | Softphone desktop para testar telefonia. Registra várias contas de vários PBX ao mesmo tempo e mostra o SIP de cada uma na mesma janela | Electron · Vue 3 · Pinia · easy-sipjs |

---

## 🛠️ Tecnologias e ferramentas

**Linguagens**

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt="C#" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
</p>

**Front-end e desktop**

<p>
  <img src="https://img.shields.io/badge/Vue.js-41B883?style=for-the-badge&logo=vuedotjs&logoColor=white" alt="Vue.js" />
  <img src="https://img.shields.io/badge/Nuxt-00DC82?style=for-the-badge&logo=nuxt&logoColor=white" alt="Nuxt" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white" alt="Electron" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" />
</p>

**Telefonia e back-end**

<p>
  <img src="https://img.shields.io/badge/WebRTC-333333?style=for-the-badge&logo=webrtc&logoColor=white" alt="WebRTC" />
  <img src="https://img.shields.io/badge/SIP.js-0A66C2?style=for-the-badge&logo=javascript&logoColor=white" alt="SIP.js" />
  <img src="https://img.shields.io/badge/Asterisk-F68F1E?style=for-the-badge&logo=asterisk&logoColor=white" alt="Asterisk" />
  <img src="https://img.shields.io/badge/MikroTik-293239?style=for-the-badge&logo=mikrotik&logoColor=white" alt="MikroTik" />
  <img src="https://img.shields.io/badge/WireGuard-88171A?style=for-the-badge&logo=wireguard&logoColor=white" alt="WireGuard" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Fastify-000000?style=for-the-badge&logo=fastify&logoColor=white" alt="Fastify" />
  <img src="https://img.shields.io/badge/Firebase-DD2C00?style=for-the-badge&logo=firebase&logoColor=white" alt="Firebase" />
  <img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
</p>

**Ferramentas**

<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white" alt="Vitest" />
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Playwright" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitLab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white" alt="GitLab" />
  <img src="https://img.shields.io/badge/Figma-A259FF?style=for-the-badge&logo=figma&logoColor=white" alt="Figma" />
</p>

---

## 📊 Estatísticas

<div align="center">
  <img height="170" src="https://github-readme-stats-eight-theta.vercel.app/api?username=phs-santos&show_icons=true&theme=dracula&locale=pt-br&hide_border=true&rank_icon=github" alt="Estatísticas do GitHub" />
  <img height="170" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=phs-santos&layout=compact&theme=dracula&locale=pt-br&hide_border=true&hide=html" alt="Linguagens mais usadas" />
  <br />
  <img src="https://streak-stats.demolab.com?user=phs-santos&theme=dracula&locale=pt_BR&hide_border=true" alt="Sequência de contribuições" />
</div>

---

<div align="center">

<img width="220" src="spock.gif" alt="Spock" />

### 🖖 *Vida longa e próspera*

</div>
