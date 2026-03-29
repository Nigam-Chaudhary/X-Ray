# ⚡ X-Ray — Advanced Repository Diagnostic Tool

> **"Scan your GitHub repositories like an X-Ray for hidden bottlenecks."**

DX-Ray is a powerful engineering health scanner that leverages the GitHub API to analyze project performance, team velocity, and CI/CD health. It provides actionable insights to help developers optimize their workflow and improve engineering efficiency.

---

## 🚀 Live Demo

🔗 **Check it out here:**
👉 https://x-ray-git-main-nigam-chaudharys-projects.vercel.app

---

## ✨ Key Features

* 🛡️ **Full Health Score**
  Get a real-time engineering efficiency score (0–100%) based on multiple performance indicators.

* 🚀 **CI/CD Analytics**
  Track build durations, monitor pipeline success rates, and detect frequent failures.

* ⏱️ **PR Velocity**
  Measure average Pull Request merge time and identify bottlenecks in code reviews.

* 🧠 **Team Cognitive Load**
  Analyze contributor workload and context switching across repositories.

* 📦 **Dependency Audit**
  Detect outdated dependencies, stale documentation, and potential risks.

* 🛠️ **Actionable Fixes**
  Get intelligent suggestions to improve performance and maintain code quality.

---

## 🏗️ Tech Stack

* **Framework:** Next.js 15 (App Router)
* **Styling:** Tailwind CSS
* **Animations:** Framer Motion + Lucide React
* **API Integration:** GitHub REST API via `@octokit/rest`

---

## 🛠️ Local Setup & Installation

Follow these steps to run DX-Ray locally:

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Nigam-Chaudhary/X-Ray.git
cd dx-ray
```

### 2️⃣ Install Dependencies

```bash
npm install
```

> (All required packages are included in `package.json`)

### 3️⃣ Setup Environment Variables

Create a `.env.local` file in the root directory and add:

```env
GITHUB_TOKEN=your_github_personal_access_token_here
```

> ⚠️ Make sure your token has `repo` and `workflow` access.

### 4️⃣ Run Development Server

```bash
npm run dev
```

Open 👉 http://localhost:3000

---

## 🔬 How It Works

DX-Ray evaluates repositories across four core pillars:

* ⚡ **Velocity** → PR creation to merge time
* 🧪 **Quality** → CI/CD success rates
* 🧹 **Maintenance** → Code & documentation freshness
* 👥 **Team Health** → Workload distribution among contributors

Each metric contributes to the final **Health Score**.

---

## 📊 Example Use Cases

* Identify slow PR review cycles
* Detect unstable CI pipelines
* Monitor team productivity trends
* Improve open-source project health

---

## 🛡️ Security & Privacy

* Your GitHub token is used only for API access
* No data is stored or shared externally
* All analysis runs securely on your environment

---

## 📌 Roadmap

* [ ] GitHub App Integration
* [ ] Multi-repo dashboard
* [ ] AI-powered suggestions
* [ ] Historical trend graphs

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create your feature branch
3. Commit your changes
4. Push and open a PR

---

## 🛡️ License

Distributed under the **MIT License**.
See `LICENSE` for more information.

---

## ⭐ Support

If you find this project useful:

👉 Give it a **⭐ Star**
👉 Share it with other developers

---

## 👨‍💻 Author

**Built with 🔥 by Nigam**

