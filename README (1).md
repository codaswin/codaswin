<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,50:031f03,100:003300&height=220&section=header&text=ASWIN&fontSize=70&fontColor=39FF14&animation=fadeIn&fontAlignY=35&desc=AI%20Architect%20%7C%20Agentic%20Systems%20Builder%20%7C%20Founder%2C%20SAAVIBUDDY&descAlignY=55&descSize=18&descColor=00FF88" width="100%"/>

<img src="https://animatedsvg.vercel.app/generate?lines=%24%20whoami%3BAswin%20--%20AI%20Architect%20%26%20Agentic%20Systems%20Builder%3BBuilding%20agentic%20AI%20%26%20GaaS%20for%20real%20businesses.%3BTamil%20Nadu%2C%20India%20%F0%9F%87%AE%F0%9F%87%B3&animation=terminal&color=39FF14&bg_color=000000&font=Fira+Code&size=18&width=760&height=160&multiline=true&center=true&duration=4500&pause=1200" width="80%"/>

</div>

<p align="center">
  <img src="https://img.shields.io/badge/Agentic%20AI-000000?style=for-the-badge&logo=robotframework&logoColor=39FF14"/>
  <img src="https://img.shields.io/badge/CrewAI-000000?style=for-the-badge&logo=data:image/svg+xml;base64,&logoColor=39FF14&labelColor=000000"/>
  <img src="https://img.shields.io/badge/AutoGen-000000?style=for-the-badge&logoColor=39FF14&labelColor=000000"/>
  <img src="https://img.shields.io/badge/n8n-000000?style=for-the-badge&logo=n8n&logoColor=39FF14"/>
  <img src="https://img.shields.io/badge/RAG%20Systems-000000?style=for-the-badge&logoColor=39FF14&labelColor=000000"/>
  <img src="https://img.shields.io/badge/LangSmith-000000?style=for-the-badge&logoColor=39FF14&labelColor=000000"/>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/LoRA%2FQLoRA-000000?style=for-the-badge&logoColor=00FFFF&labelColor=000000"/>
  <img src="https://img.shields.io/badge/vLLM-000000?style=for-the-badge&logoColor=00FFFF&labelColor=000000"/>
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=00FFFF"/>
  <img src="https://img.shields.io/badge/OpenAI-000000?style=for-the-badge&logo=openai&logoColor=00FFFF"/>
  <img src="https://img.shields.io/badge/Gemini-000000?style=for-the-badge&logo=googlegemini&logoColor=00FFFF"/>
</p>

<div align="center">
<img src="https://animatedsvg.vercel.app/generate?lines=ENTER%20THE%20AGENTIC%20AI%20MATRIX&animation=matrix&color=00FF41&bg_color=000000&font=Fira+Code&size=30&width=650&height=90" width="65%"/>
</div>

---

### `> cat about_me.txt`

```
> Runs an AI automation agency shipping agentic systems + GaaS
  (Generative-AI-as-a-Service) for education & coaching businesses.

> Building SAAVIBUDDY — my own enterprise AI stack & product line.

> Multi-agent orchestration (CrewAI, AutoGen) · Advanced RAG
  (KG-RAG, Corrective RAG, Self-RAG, Fusion RAG) · LLMOps ·
  fine-tuning (LoRA/QLoRA) · guardrails (Llama Guard, NeMo).

> Background in digital marketing & high-ticket sales — I don't
  just build the agent, I know why a business should pay for it.

> Vibe coder by method: I own the architecture and the outcome,
  AI tools handle the keystrokes.
```

---

### `> ls current_focus/`

<div align="center">
<img src="https://animatedsvg.vercel.app/generate?lines=SAAVIBUDDY&animation=glitch&color=39FF14,00FFFF&bg_color=000000&font=JetBrains+Mono&size=34&width=420&height=90" width="40%"/>
</div>

- 🧠 **[SAAVIBUDDY](https://saavibuddy.space)** — my enterprise AI stack: infra, live agent demos, and a growing product suite, shipped with React + Vite + Tailwind + FastAPI.
- 🤖 Production agentic workflows for coaching & education clients — CRM-integrated AI workforces, not just chatbots.
- 🧪 Constantly stress-testing RAG architectures and guardrail stacks before they touch a client's data.

---

### `> ./run_stats.sh`

<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=YOUR-GITHUB-USERNAME&show_icons=true&theme=chartreuse-dark&bg_color=000000&title_color=39FF14&icon_color=00FF88&text_color=c9d1d9&border_color=1a3a1a&hide_border=false" width="48%"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR-GITHUB-USERNAME&layout=compact&theme=chartreuse-dark&bg_color=000000&title_color=39FF14&text_color=c9d1d9&border_color=1a3a1a&hide_border=false" width="38%"/>
</div>

<div align="center">
<img src="https://streak-stats.demolab.com?user=YOUR-GITHUB-USERNAME&theme=dark&background=000000&stroke=39FF14&ring=39FF14&fire=00FF88&currStreakLabel=39FF14&border=1a3a1a" width="60%"/>
</div>

> Swap `YOUR-GITHUB-USERNAME` (5 spots above) for your real GitHub handle or the cards will render empty.

---

### `> git log --graph --decorate` (contribution snake)

Drop this as `.github/workflows/snake.yml` in a repo to get an animated snake eating your contribution graph, auto-updated daily:

```yaml
name: generate snake
on:
  schedule:
    - cron: "0 0 * * *"
  push:
    branches: [ main ]
  workflow_dispatch: {}

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

Then embed it:

```markdown
![snake](https://raw.githubusercontent.com/YOUR-GITHUB-USERNAME/YOUR-GITHUB-USERNAME/output/github-contribution-grid-snake-dark.svg)
```

---

### `> whoami --connect`

<p align="center">
  <a href="https://saavibuddy.space"><img src="https://img.shields.io/badge/SAAVIBUDDY-000000?style=for-the-badge&logo=vercel&logoColor=39FF14"/></a>
  <a href="#"><img src="https://img.shields.io/badge/LinkedIn-000000?style=for-the-badge&logo=linkedin&logoColor=00FFFF"/></a>
  <a href="#"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=00FFFF"/></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:003300,100:000000&height=120&section=footer&animation=fadeIn"/>
</div>
