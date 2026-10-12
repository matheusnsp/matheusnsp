<a href="https://www.matheusnsp.com.br">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/matheusnsp/matheusnsp/main/assets/banner-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/matheusnsp/matheusnsp/main/assets/banner-light.svg">
    <img alt="Matheus Neves — infraestrutura e segurança da informação" src="https://raw.githubusercontent.com/matheusnsp/matheusnsp/main/assets/banner-light.svg" width="100%">
  </picture>
</a>

<p>
  <a href="https://www.matheusnsp.com.br"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/matheusnsp/matheusnsp/main/assets/btn-portfolio-dark.svg"><img alt="Portfólio" src="https://raw.githubusercontent.com/matheusnsp/matheusnsp/main/assets/btn-portfolio-light.svg" height="44"></picture></a>
  <a href="https://www.linkedin.com/in/matheusnsp"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/matheusnsp/matheusnsp/main/assets/btn-linkedin-dark.svg"><img alt="LinkedIn" src="https://raw.githubusercontent.com/matheusnsp/matheusnsp/main/assets/btn-linkedin-light.svg" height="44"></picture></a>
  <a href="mailto:matheusn.dev@gmail.com"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/matheusnsp/matheusnsp/main/assets/btn-email-dark.svg"><img alt="E-mail" src="https://raw.githubusercontent.com/matheusnsp/matheusnsp/main/assets/btn-email-light.svg" height="44"></picture></a>
  <a href="https://www.matheusnsp.com.br/cv-matheus-neves.pdf"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/matheusnsp/matheusnsp/main/assets/btn-cv-dark.svg"><img alt="Baixar CV" src="https://raw.githubusercontent.com/matheusnsp/matheusnsp/main/assets/btn-cv-light.svg" height="44"></picture></a>
</p>

### `$ whoami`

Engenheiro de software formado pela **University of Canberra** (Austrália), atuando em **infraestrutura e segurança da informação**. Coordeno a infraestrutura e a segurança de TI da **Cruz Vermelha Brasileira — RJ**: redes, controle de acesso (IAM), segurança física e ciclo de vida de ativos. Quando desenvolvo, segurança vem no desenho do sistema, não no fim.

<table>
  <tr>
    <td align="center" width="25%"><h3>350</h3><sub>alunos protegidos no sistema que desenvolvi para a Escola da Cruz Vermelha</sub></td>
    <td align="center" width="25%"><h3>SC-900</h3><sub>certificação Microsoft em segurança, compliance e identidade</sub></td>
    <td align="center" width="25%"><h3>CVE</h3><sub>correlação automática de serviços com a base NVD/NIST no NetScan</sub></td>
    <td align="center" width="25%"><h3>RLS</h3><sub>isolamento de dados por usuário direto no banco, nos meus apps</sub></td>
  </tr>
</table>

### `01` Áreas de atuação

| Área | O que faço |
|:--|:--|
| **🛡️ Segurança ofensiva** | Reconhecimento de rede, varredura de portas, banner grabbing e mapeamento de serviços para CVEs conhecidos |
| **🔐 Identidade e acesso** | Gestão de acessos (IAM), revisão de permissões e protocolos de autenticação |
| **🌐 Redes e infraestrutura** | Redes L2/L3, VLANs, ACLs, NAT e firewall (Cisco), ambientes Windows Server e Linux |
| **🗄️ Proteção de dados** | Row Level Security, autenticação gerenciada, descarte seguro de mídias e controle de ativos de armazenamento |
| **📹 Segurança física** | Monitoramento remoto e CFTV IP integrados à política de acesso |

### `02` Projetos de segurança

<table>
  <tr>
    <td width="50%" valign="top">

**🔍 NetScan**

Ferramenta de reconhecimento para pentest em Python: descoberta de hosts via ARP, varredura TCP concorrente (1.000+ portas em segundos), banner grabbing e cruzamento com CVEs da NVD/NIST, com severidade CVSS. Relatórios em HTML, JSON e CSV.

`Python` `ThreadPoolExecutor` `NVD API` `CVSS` `pytest`

[código](https://github.com/matheusnsp/NetScan)

  </td>
    <td width="50%" valign="top">

**🧱 Infraestrutura segura Windows & Linux**

Rede segmentada com VLANs, ACLs, NAT e firewall em roteador Cisco, testada entre Windows Server e Ubuntu. Documentada em relatório técnico.

`Cisco CLI` `VLAN` `ACL` `NAT` `Windows Server` `Ubuntu`

[relatório (PDF)](https://www.matheusnsp.com.br/A3_Report.pdf)

  </td>
  </tr>
  <tr>
    <td width="50%" valign="top">

**🏥 Infra e segurança — Cruz Vermelha RJ**

Auditoria e diagnóstico do parque tecnológico, protocolo de descarte seguro de dados e HDDs, expansão da rede para novos setores e reestruturação do monitoramento remoto com foco em IAM.

`Redes L2/L3` `IAM` `CFTV IP` `Gestão de ativos`

<sub>trabalho interno · sem código público</sub>

  </td>
    <td width="50%" valign="top">

**🎓 Sistema da Escola Cruz Vermelha**

Sistema de gestão com dados pessoais e pagamentos de 350 alunos: PIX e cartão confirmados via webhook, painel administrativo por perfil e dados em PostgreSQL.

`Node.js` `Express` `Prisma` `PostgreSQL` `Supabase`

[ao vivo ↗](https://escola.cursoscruzvermelha.org) · <sub>código privado</sub>

  </td>
  </tr>
  <tr>
    <td width="50%" valign="top">

**📊 Dash**

Finanças pessoais com autenticação via Supabase Auth e Row Level Security: cada usuário só enxerga os próprios dados, mesmo em chamadas diretas à API.

`Supabase Auth` `RLS` `PostgreSQL` `JavaScript`

[código](https://github.com/matheusnsp/Dash)

  </td>
    <td width="50%" valign="top">

**🎛️ Deck**

Celular como painel de botões para o computador (Mac, Windows e Linux), rodando na rede local, com instalador por uma linha no terminal.

`Python` `JavaScript` `Rede local`

[código](https://github.com/matheusnsp/deck) · [site ↗](https://deck-helper.vercel.app)

  </td>
  </tr>
</table>

<sub>Também: [Tom Louvores](https://github.com/matheusnsp/tom-louvores) — PWA offline com Supabase · [Portfólio](https://github.com/matheusnsp/Portfolio) — React + Framer Motion · [YouTube Transcriber](https://github.com/matheusnsp/trancriptingTranslating) — Whisper + tradução</sub>

### `03` Ferramentas

<table>
  <tr>
    <td><b>Segurança e redes</b></td>
    <td>
      <img src="https://cdn.simpleicons.org/wireshark/1679A7" height="34" alt="Wireshark" title="Wireshark">&nbsp;
      <img src="https://cdn.simpleicons.org/cisco/1BA0D7" height="34" alt="Cisco" title="Cisco (VLAN, ACL, NAT)">&nbsp;
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/azure/azure-original.svg" height="34" alt="IAM" title="IAM">&nbsp;
      <code>Nmap</code> <code>NVD / CVE</code> <code>CVSS</code>
    </td>
  </tr>
  <tr>
    <td><b>Sistemas</b></td>
    <td>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" height="34" alt="Linux" title="Linux">&nbsp;
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/windows11/windows11-original.svg" height="34" alt="Windows Server" title="Windows Server">&nbsp;
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" height="34" alt="Docker" title="Docker">
    </td>
  </tr>
  <tr>
    <td><b>Linguagens</b></td>
    <td>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="34" alt="Python" title="Python">&nbsp;
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="34" alt="JavaScript" title="JavaScript">&nbsp;
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" height="34" alt="Java" title="Java">
    </td>
  </tr>
  <tr>
    <td><b>Dados e back-end</b></td>
    <td>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" height="34" alt="PostgreSQL" title="PostgreSQL">&nbsp;
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/supabase/supabase-original.svg" height="34" alt="Supabase" title="Supabase (Auth + RLS)">&nbsp;
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="34" alt="Node.js" title="Node.js">&nbsp;
      <img src="https://cdn.simpleicons.org/prisma/8b98ad" height="34" alt="Prisma" title="Prisma">
    </td>
  </tr>
  <tr>
    <td><b>Versionamento e deploy</b></td>
    <td>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" height="34" alt="Git" title="Git">&nbsp;
      <img src="https://cdn.simpleicons.org/github/8b98ad" height="34" alt="GitHub" title="GitHub">&nbsp;
      <img src="https://cdn.simpleicons.org/vercel/8b98ad" height="34" alt="Vercel" title="Vercel">&nbsp;
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/netlify/netlify-original.svg" height="34" alt="Netlify" title="Netlify">
    </td>
  </tr>
</table>

### `04` Trajetória

| Quando | O quê | Onde |
|:--|:--|:--|
| **fev 2026 → hoje** | **Coordenador de Infraestrutura e Segurança** — redes L2/L3, IAM, CFTV IP, descarte seguro de dados e controle de ativos | Cruz Vermelha Brasileira · RJ |
| **jul → nov 2024** | **Estagiário de IA e Robótica** — pipeline de IA generativa em tempo real para o robô De Niro, latência de 7,5 s para 4,2 s | University of Canberra 🇦🇺 |
| **2022 → 2024** | **Bacharelado em Engenharia de Software** | University of Canberra 🇦🇺 |

### `05` Certificações

| Certificação | Emissor | Ano |
|:--|:--|:-:|
| SC-900 · Security, Compliance & Identity Fundamentals | Microsoft | 2025 |
| SAP BTP + S/4HANA | Lab2Learn | 2025 |
| Oratória e Comunicação | Clube da Fala | 2025 |
| Introduction to Mobile Development | Meta | 2023 |

<details>
<summary><b>🇬🇧 English version</b></summary>
<br>

**Hi, I'm Matheus** — a software engineer from the **University of Canberra** (Australia) working in **infrastructure and information security**. I coordinate IT infrastructure and security at the **Brazilian Red Cross — Rio de Janeiro**: networks, identity and access management, physical security and asset lifecycle. When I build software, security is part of the design, not an afterthought.

| Project | What it is |
|:--|:--|
| **NetScan** | Python pentest reconnaissance: ARP host discovery, concurrent TCP scanning, banner grabbing and CVE correlation via the NVD/NIST API with CVSS severity. [Code](https://github.com/matheusnsp/NetScan) |
| **Secure Windows & Linux infrastructure** | Segmented network with VLANs, ACLs, NAT and a firewall on a Cisco router, documented in a technical report. [Report (PDF)](https://www.matheusnsp.com.br/A3_Report.pdf) |
| **Red Cross IT & security** | Hardware audit, secure data and HDD decommissioning, network expansion and IAM-focused remote monitoring. |
| **Red Cross School platform** | Management system holding personal and payment data for 350 students, with webhook-confirmed PIX and card payments. [Live ↗](https://escola.cursoscruzvermelha.org) |
| **Dash** | Personal finance app with Supabase Auth and Row Level Security isolating each user's data. [Code](https://github.com/matheusnsp/Dash) |

📄 [Resume (PDF)](https://www.matheusnsp.com.br/resume-matheus-neves.pdf) · 🌐 [Portfolio](https://www.matheusnsp.com.br) · 💼 [LinkedIn](https://www.linkedin.com/in/matheusnsp)

</details>

<p align="center"><sub>📫 <a href="mailto:matheusn.dev@gmail.com">matheusn.dev@gmail.com</a> · <a href="https://www.matheusnsp.com.br">matheusnsp.com.br</a> · <a href="https://www.linkedin.com/in/matheusnsp">linkedin.com/in/matheusnsp</a></sub></p>