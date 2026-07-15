<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b27,50:24283b,100:3b4261&height=220&section=header&text=Qi%20Luo&fontSize=68&fontColor=c0caf5&desc=IC%20%2F%20SoC%20%C2%B7%20Digital%20Frontend%20%C2%B7%20FDU&descColor=7dcfff&descSize=22&descAlignY=72" width="100%"/>

<a href="https://github.com/RockyQLuo">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=2600&pause=700&color=7AA2F7&center=true&vCenter=true&width=760&lines=IC+%2F+SoC+Design;Digital+Frontend+Engineer;Verilog+%2F+SystemVerilog;RTL+%C2%B7+Integration+%C2%B7+Bring-up;Fudan+University" alt="Typing SVG" />
</a>

<br/>

<img src="https://komarev.com/ghpvc/?username=RockyQLuo&style=for-the-badge&color=7aa2f7&label=PROFILE+VIEWS"/>
<a href="https://github.com/RockyQLuo?tab=followers"><img src="https://img.shields.io/github/followers/RockyQLuo?style=for-the-badge&logo=github&labelColor=1a1b27&color=7aa2f7"/></a>
<img src="https://img.shields.io/badge/Shanghai-China-9ece6a?style=for-the-badge&labelColor=1a1b27"/>
<img src="https://img.shields.io/badge/Focus-Digital%20Frontend-bb9af7?style=for-the-badge&labelColor=1a1b27"/>
<img src="https://img.shields.io/badge/2026-UCIe%20%2B%20SoC%20Integration-ff9e64?style=for-the-badge&labelColor=1a1b27"/>

</div>

## 🧭 About me

- 🎓 **IC Master's student @ Fudan University (FDU)** — based in Shanghai
- 🔌 Focus: **SoC / digital frontend** — RTL, subsystem integration, lint & bring-up
- 🧩 Recent work theme: **Cortex-M0+ class SoC integration** and **UCIe** sideband / interconnect paths (lab / private tracks)
- 🛠 Comfort zone: Verilog / SystemVerilog, C/C++ for firmware & tools, Python/Bash for EDA automation
- ✍️ Learning notes live on [RockyQLuo.github.io](https://rockyqluo.github.io) — *rookie in IC*, still shipping

> 🎯 **2026 focus** — tighten the loop from **RTL → lint → sim → integration**, document the hard parts, and turn chip-side friction into reusable flows.

## 🚀 The journey so far

```mermaid
timeline
    title From IC learner to SoC integrator
    2022 : GitHub journey starts : First notes and tooling experiments
    2024 : IC master's track @ FDU : Env / protocol / algorithm study logs
    2025 : Digital frontend deep dive : AXI · DDR · open IP exploration
    2026 : SoC + UCIe integration : Cortex-M0+ class subsystem bring-up
```

## 🧠 Stack map (how I think about a chip)

```mermaid
flowchart LR
    subgraph Spec["Spec & Architecture"]
        A[Subsystem / Die-to-die goals]
    end
    subgraph FE["Digital Frontend"]
        B[RTL · SV]
        C[Lint · CDC checks]
        D[Sim · Unit + block]
    end
    subgraph Int["Integration"]
        E[Bus / IP glue]
        F[UCIe / sideband paths]
        G[FW bring-up hooks]
    end
    subgraph Tool["Automation"]
        H[Python · Bash]
        I[CI-ish scripts · Docker]
    end
    A --> B --> C --> D --> E
    E --> F
    E --> G
    B -.-> H
    C -.-> H
    H --> I
```

## 🧰 Arsenal

<div align="center">

**Languages & HDL**

<img src="https://skillicons.dev/icons?i=verilog,c,cpp,python,bash,scala,matlab,latex&perline=8" />

<br/>

**Platform & workflow**

<img src="https://skillicons.dev/icons?i=linux,docker,git,github,vscode,vim,cmake,md&perline=8" />

</div>

<details>
<summary>🗂 <b>Skill notes (what each row actually means)</b></summary>
<br/>

| Area | What I use it for |
|---|---|
| **HDL** | Verilog / SystemVerilog RTL, block & subsystem integration |
| **C / C++** | Bring-up, firmware hooks, host-side utilities around the SoC |
| **Python / Bash** | EDA glue, regression wrappers, repo hygiene |
| **Linux / Docker / Git** | Reproducible tool envs, daily design-flow hygiene |
| **Scala (read)** | Chisel / open hardware projects (e.g. Chipmunk exploration) |
| **MATLAB** | Algorithm / signal checks when the design needs it |

</details>

## 📚 Learning tracks (open-source IP I study)

> Private lab work stays private. Public signal is **what I fork, read, and re-implement against**.

<div align="center">

| Track | Repos I keep close |
|---|---|
| 🚌 **On-chip interconnect** | [verilog-axi](https://github.com/RockyQLuo/verilog-axi) · [common_cells](https://github.com/RockyQLuo/common_cells) · [connect](https://github.com/RockyQLuo/connect) |
| 💾 **Memory path** | [UberDDR3](https://github.com/RockyQLuo/UberDDR3) |
| 🧮 **Open hardware / Chisel** | [chipmunk](https://github.com/RockyQLuo/chipmunk) |
| 🧰 **Env & notes** | [dotfiles](https://github.com/RockyQLuo/dotfiles) · [RockyQLuo.github.io](https://github.com/RockyQLuo/RockyQLuo.github.io) |

</div>

## 🏠 Public corners

<div align="center">

<table>
<tr>
<td align="center" width="50%">
<a href="https://github.com/RockyQLuo/RockyQLuo.github.io"><picture><source media="(prefers-color-scheme: dark)" srcset="https://socialify.git.ci/RockyQLuo/RockyQLuo.github.io/image?description=1&font=Inter&language=1&name=1&owner=1&pattern=Plus&stargazers=1&theme=Dark"><img src="https://socialify.git.ci/RockyQLuo/RockyQLuo.github.io/image?description=1&font=Inter&language=1&name=1&owner=1&pattern=Plus&stargazers=1&theme=Light" alt="RockyQLuo.github.io" width="100%"></picture></a>
</td>
<td align="center" width="50%">
<a href="https://github.com/RockyQLuo/dotfiles"><picture><source media="(prefers-color-scheme: dark)" srcset="https://socialify.git.ci/RockyQLuo/dotfiles/image?description=1&font=Inter&language=1&name=1&owner=1&pattern=Plus&stargazers=1&theme=Dark"><img src="https://socialify.git.ci/RockyQLuo/dotfiles/image?description=1&font=Inter&language=1&name=1&owner=1&pattern=Plus&stargazers=1&theme=Light" alt="dotfiles" width="100%"></picture></a>
</td>
</tr>
</table>

</div>

## 📈 Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=RockyQLuo&theme=tokyo-night&hide_border=true&area=true&radius=8" width="100%"/>

</div>

## 🐍 Contribution snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/RockyQLuo/RockyQLuo/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/RockyQLuo/RockyQLuo/output/github-contribution-grid-snake.svg">
  <img alt="contribution snake" src="https://raw.githubusercontent.com/RockyQLuo/RockyQLuo/output/github-contribution-grid-snake.svg">
</picture>

</div>

<div align="center">

*"Show me the code — then show me it boots on silicon."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7aa2f7,55:414868,100:1a1b27&height=130&section=footer" width="100%"/>

</div>

<!-- profile-readme-active -->
