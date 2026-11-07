<div align="center">

# Constantine Lekkos

<img src="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&weight=500&size=20&pause=1400&color=7CC4FF&center=true&vCenter=true&width=620&lines=Software+Engineer+%2B+Biomedical+Engineer%2C+MEng;Full-stack+systems+in+.NET%2C+TypeScript+and+Rust;Researching+physics-informed+neural+networks;Curious+about+quantum+computing" alt="Software Engineer and Biomedical Engineer, MEng" />

Software engineer building production systems.<br/>
Biomedical engineer researching physics-informed neural networks.

[![Website](https://img.shields.io/badge/ecco.dev-leccode.github.io-7CC4FF?style=flat-square&labelColor=0A1022&logo=githubpages&logoColor=white)](https://leccode.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Constantine_Lekkos-7CC4FF?style=flat-square&labelColor=0A1022&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/constantine-lekkos/)
[![Email](https://img.shields.io/badge/Email-costas.lekkos%40gmail.com-7CC4FF?style=flat-square&labelColor=0A1022&logo=gmail&logoColor=white)](mailto:costas.lekkos@gmail.com)

</div>

---

### About

<img align="right" src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExeGpvdWtyMTlhNDRxeHh4c3U1MDF2Njh5OWtweW56OWk5MmEzN20zMiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/78XCFBGOlS6keY1Bil/giphy.gif" width="220" alt="Cat typing on a keyboard" />

- 🔬 **Researching:** MPhil in Computer Science & Informatics. Physics-informed neural networks, quantum computing and hardware for bioinformatics.
- 💼 **Building:** 4+ years of backend and full-stack systems for banking, healthcare and logistics.
- 🦀 **Learning:** Rust, one async worker at a time.
- ✍️ **Writing:** science and tech notes on [my blog](https://leccode.github.io/blog/).

### Tech stack

<p align="center">
  <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=cs,dotnet,rust,nodejs,py&perline=10" alt="C#, .NET, Rust, Node.js, Python" /></a><br/>
  <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,angular,vue,tailwind,html,css&perline=10" alt="TypeScript, JavaScript, React, Next.js, Angular, Vue, Tailwind CSS, HTML, CSS" /></a><br/>
  <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=postgres,mongodb,docker,aws,linux,git,postman,arduino,sklearn,matlab&perline=10" alt="PostgreSQL, MongoDB, Docker, AWS, Linux, Git, Postman, Arduino, scikit-learn, MATLAB" /></a>
</p>

<p align="center"><sub>Also: SQL Server, Blazor, pandas, REST APIs, Clean Architecture, SOLID</sub></p>

### Featured work

| Project | What it is | Stack |
|:--|:--|:--|
| [DNA/RNA Knowledgebase](https://github.com/leccode/nucleic-acids-api) | Store and manage nucleic acid sequences ([UI](https://github.com/leccode/nucleic-acids-ui)) | .NET · SQL Server · Vue |
| [GitHub Dashboard](https://github.com/leccode/github-dashboard) | Explore any profile through the GitHub API | React · Vite · Tailwind |
| [Feedback Fusion](https://github.com/leccode/feedback-fusion) | Project built alongside a guided video tutorial | See repo |
| [Physics-Informed Neural Networks](https://leccode.github.io/blog/physics-informed-neural-networks/) | Article: embedding physical laws into training | Deep learning |

### Science notes

<div align="center">

| Concept | Expression |
|:--|:--|
| Probability density | $P(x,t) = \lvert\Psi(x,t)\rvert^2 = \Psi^\ast(x,t)\,\Psi(x,t)$ |
| Normalization | $\int_{-\infty}^{\infty} \lvert\Psi(x,t)\rvert^2\,dx = 1$ |
| Qubit state | $`\ket{\psi} = \alpha\ket{0} + \beta\ket{1}`$ |
| Neuron | $\hat{y} = \sigma(w^\top x + b)$ |
| PINN loss | $\mathcal{L} = \mathcal{L}_{\text{data}} + \lambda\,\mathcal{L}_{\text{physics}}$ |

</div>

<details>
<summary><b>🛠️ Dev notes: Git and Next.js workflow</b></summary>

<br/>

**Git: new project**

```bash
git init
git remote add origin <repo-url>
git pull origin main --allow-unrelated-histories   # only if the remote already has files
git branch -M main
git add .
git commit -m "Initial commit"
git push -u origin main
```

**Git: useful extras**

```bash
git update-git-for-windows      # update Git on Windows
git config --list               # all settings (--system / --global to filter)
```

**Next.js stack with pnpm**

| Tool | Notes |
|:--|:--|
| [Next.js](https://nextjs.org/) + [Tailwind CSS](https://tailwindcss.com/) | Tailwind comes preconfigured with `create-next-app` |
| [shadcn/ui](https://ui.shadcn.com/) | If prompted, run `pnpm approve-builds` and approve `sharp` and `unrs-resolver` |
| [React Hook Form](https://react-hook-form.com/) + [Zod](https://zod.dev/) | Connect them with `pnpm i @hookform/resolvers` |
| [Convex](https://www.convex.dev/) | `pnpm dlx convex dev` to set up; approve `esbuild` if prompted |
| [Better Auth](https://better-auth.com/) | `pnpm i @convex-dev/better-auth` and `pnpm add better-auth@1.3.34 --save-exact`; see the [Convex integration guide](https://better-auth.com/docs/integrations/convex) |

**Convex tips**

```bash
pnpm dlx convex login                                     # if dev asks you to log in, stop dev, log in, restart
pnpm dlx convex import --table tasks sampleData.jsonl     # load sample data
```

</details>

---

<p align="center"><sub>Open to interesting projects and research collaborations. Say hi at <a href="mailto:costas.lekkos@gmail.com">costas.lekkos@gmail.com</a>.</sub></p>
