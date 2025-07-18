---
title: Babar Ali - Freelance AI Engineer
email: babarburiro@gmail.com
baseurl: ""
url: "https://bababuriro.github.io"
theme: minima
---

{% include head.html %}
{% include header.html %}

<body class="bg-gray-900 text-gray-100 font-sans">
<header class="bg-gradient-to-br from-gray-800 to-gray-900 py-20 shadow-xl">
  <div class="container mx-auto px-6 text-center animate-fade-in">
    <h1 class="text-5xl md:text-7xl font-extrabold tracking-tight">Babar Ali</h1>
    <p class="text-2xl mt-4 text-gray-400">Freelance AI Engineer | LLM Systems | Python & Automation</p>
    <a href="mailto:babarburiro@gmail.com" class="mt-8 inline-block bg-blue-600 hover:bg-blue-700 text-white font-semibold py-3 px-8 rounded-full transition-transform transform hover:scale-105">Hire Me</a>
  </div>
</header>

<main class="space-y-24 py-16 px-6 max-w-5xl mx-auto">
  <section class="animate-slide-up">
    <h2 class="text-4xl font-bold mb-6 text-white">Highlighted Projects</h2>
    <div class="space-y-6">
      <div class="bg-gray-800 p-6 rounded-xl shadow hover:shadow-blue-500/40 transition-shadow">
        <h3 class="text-2xl font-semibold text-white">Slack LLM Bot Platform</h3>
        <p class="text-gray-300">Developed a full-stack Slack integration with user-isolated bots powered by LangGraph and RAG. Each agent handles threaded conversations and document access, integrated into a Django backend.</p>
      </div>
      <div class="bg-gray-800 p-6 rounded-xl shadow hover:shadow-blue-500/40 transition-shadow">
        <h3 class="text-2xl font-semibold text-white">Sports Prediction Pipeline</h3>
        <p class="text-gray-300">Built a time-to-failure model for basketball outcomes using Python and AWS. Data scraped daily and processed through a serverless pipeline, visualized in real-time dashboards for betting analysis.</p>
      </div>
      <div class="bg-gray-800 p-6 rounded-xl shadow hover:shadow-blue-500/40 transition-shadow">
        <h3 class="text-2xl font-semibold text-white">ERP Fleet Tracker (ERPNext)</h3>
        <p class="text-gray-300">Implemented a vehicle and trip logging system inside ERPNext. Allowed dynamic report generation and fleet management for a large transport team. Used Frappe framework and integrated custom scripts for daily log summaries.</p>
      </div>
      <div class="bg-gray-800 p-6 rounded-xl shadow hover:shadow-blue-500/40 transition-shadow">
        <h3 class="text-2xl font-semibold text-white">FTP to Oracle Apex Automation</h3>
        <p class="text-gray-300">Built a parser that downloads, reads, and summarizes log files from remote FTP servers and feeds them into an Oracle Apex dashboard. Deployed using Python with schedule-based execution for client reporting.</p>
      </div>
      <div class="bg-gray-800 p-6 rounded-xl shadow hover:shadow-blue-500/40 transition-shadow">
        <h3 class="text-2xl font-semibold text-white">Questgator</h3>
        <p class="text-gray-300">Designed and published Questgator, an LLM-powered aggregator for research, job, and grant opportunities. The project led to two academic publications and international recognition.</p>
      </div>
    </div>
  </section>
</main>

<style>
@keyframes fade-in {
  from { opacity: 0; }
  to { opacity: 1; }
}
@keyframes slide-up {
  from { transform: translateY(20px); opacity: 0; }
  to { transform: translateY(0); opacity: 1; }
}
.animate-fade-in { animation: fade-in 1s ease-in-out both; }
.animate-slide-up { animation: slide-up 1s ease-in-out both; }
body { background-color: #111827; color: #f3f4f6; }
</style>
</body>
