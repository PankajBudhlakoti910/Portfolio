<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Pankaj Budhlakoti — Portfolio</title>
  <!-- Tailwind via CDN (good for quick demo in Codespace/GitHub Pages) -->
  <script src="https://cdn.tailwindcss.com"></script>
  <meta name="description" content="Personal portfolio - copy and paste to GitHub / Codespaces" />
</head>
<body class="bg-slate-50 text-slate-800 antialiased">
  <header class="bg-white/80 backdrop-blur sticky top-0 z-40 shadow-sm">
    <div class="max-w-6xl mx-auto px-6 py-4 flex items-center justify-between">
      <div class="flex items-center space-x-4">
        <div class="w-10 h-10 rounded-full bg-gradient-to-tr from-indigo-500 to-cyan-400 flex items-center justify-center text-white font-bold">PB</div>
        <div>
          <h1 class="text-lg font-semibold">Pankaj Budhlakoti</h1>
          <p class="text-sm text-slate-500">Junior Data Analyst / Automation & Power BI</p>
        </div>
      </div>
      <nav class="space-x-4 text-sm">
        <a href="#about" class="hover:underline">About</a>
        <a href="#projects" class="hover:underline">Projects</a>
        <a href="#skills" class="hover:underline">Skills</a>
        <a href="#contact" class="hover:underline">Contact</a>
      </nav>
    </div>
  </header>

  <main class="max-w-6xl mx-auto px-6 py-12 space-y-12">
    <!-- Hero -->
    <section class="grid md:grid-cols-2 gap-8 items-center">
      <div>
        <h2 class="text-4xl font-extrabold leading-tight">Hi, I'm Pankaj 👋</h2>
        <p class="mt-4 text-lg text-slate-600">I build data pipelines, automate repetitive tasks, and create clear dashboards in Power BI and BigQuery. I love turning messy spreadsheets into actionable insights.</p>

        <div class="mt-6 flex items-center space-x-3">
          <a href="#projects" class="inline-flex items-center gap-2 bg-indigo-600 text-white px-4 py-2 rounded-lg shadow hover:bg-indigo-700">View Projects</a>
          <a href="mailto:pankaj.budhlakoti@clicflyer.com" class="text-sm text-slate-600 hover:underline">pankaj.budhlakoti@clicflyer.com</a>
        </div>

        <div class="mt-6 grid grid-cols-2 gap-3 sm:grid-cols-4">
          <div class="p-3 bg-white rounded-lg shadow-sm text-center">
            <div class="text-xs text-slate-500">Tools</div>
            <div class="font-semibold">Power BI</div>
          </div>
          <div class="p-3 bg-white rounded-lg shadow-sm text-center">
            <div class="text-xs text-slate-500">Data</div>
            <div class="font-semibold">BigQuery</div>
          </div>
          <div class="p-3 bg-white rounded-lg shadow-sm text-center">
            <div class="text-xs text-slate-500">Languages</div>
            <div class="font-semibold">SQL, Python</div>
          </div>
          <div class="p-3 bg-white rounded-lg shadow-sm text-center">
            <div class="text-xs text-slate-500">Automation</div>
            <div class="font-semibold">Python + Email</div>
          </div>
        </div>
      </div>

      <div class="bg-gradient-to-tr from-indigo-50 to-cyan-50 rounded-2xl p-6 shadow-lg">
        <div class="rounded-lg overflow-hidden bg-white p-6">
          <h3 class="font-semibold">Quick snapshot</h3>
          <ul class="mt-4 space-y-3 text-sm text-slate-600">
            <li>📊 Weekly automated reports (Power BI + BigQuery)</li>
            <li>✉️ Python scripts that send Excel reports via email</li>
            <li>🔁 Automation to reduce manual QC workload</li>
            <li>📈 Built dashboards for e‑commerce & retail analytics</li>
          </ul>
          <div class="mt-6 text-sm text-slate-500">Want this page customized with your real projects & links? Scroll to Contact.</div>
        </div>
      </div>
    </section>

    <!-- About -->
    <section id="about" class="bg-white rounded-2xl p-6 shadow-sm">
      <h3 class="text-2xl font-semibold">About me</h3>
      <p class="mt-3 text-slate-600">I am a Junior Data Analyst with experience in data processing, building BI reports, and automating repeatable tasks. I enjoy writing SQL queries, working with BigQuery and Power BI, and creating Python scripts that make teammates' lives easier.</p>
      <div class="mt-4 grid sm:grid-cols-2 gap-4">
        <div>
          <h4 class="font-medium">Education</h4>
          <p class="text-sm text-slate-600 mt-1">B.Com (Hons), Kumaun University (Expected July 2025)</p>
        </div>
        <div>
          <h4 class="font-medium">Availability</h4>
          <p class="text-sm text-slate-600 mt-1">Open to freelance projects and collaboration. Based in India (IST timezone).</p>
        </div>
      </div>
    </section>

    <!-- Projects -->
    <section id="projects">
      <div class="flex items-center justify-between mb-4">
        <h3 class="text-2xl font-semibold">Selected projects</h3>
        <a href="#contact" class="text-sm text-indigo-600 hover:underline">Want me to add your project?</a>
      </div>

      <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-6">
        <!-- Project 1 -->
        <article class="bg-white p-5 rounded-lg shadow-sm">
          <h4 class="font-semibold">UAE Nesto Data Pipeline</h4>
          <p class="text-sm text-slate-600 mt-2">Automated extraction + transformation in BigQuery and generated weekly Excel reports that are emailed to stakeholders.</p>
          <p class="mt-3 text-xs text-slate-500">Tech: BigQuery, Python, GCP service account</p>
          <div class="mt-4 flex items-center justify-between text-sm">
            <a href="#" class="text-indigo-600 hover:underline">View repo</a>
            <span class="text-slate-400">Aug 2025</span>
          </div>
        </article>

        <!-- Project 2 -->
        <article class="bg-white p-5 rounded-lg shadow-sm">
          <h4 class="font-semibold">Power BI QC Dashboards</h4>
          <p class="text-sm text-slate-600 mt-2">Designed dashboards for quality checks and to monitor refresh times. Implemented measures to show last refresh in IST.</p>
          <p class="mt-3 text-xs text-slate-500">Tech: Power BI, DAX</p>
          <div class="mt-4 flex items-center justify-between text-sm">
            <a href="#" class="text-indigo-600 hover:underline">View report</a>
            <span class="text-slate-400">Jul 2025</span>
          </div>
        </article>

        <!-- Project 3 -->
        <article class="bg-white p-5 rounded-lg shadow-sm">
          <h4 class="font-semibold">Retailer Match Automation</h4>
          <p class="text-sm text-slate-600 mt-2">Matched retailers between Google Sheets and Excel files and generated mismatch alerts via email with unmatched names highlighted.</p>
          <p class="mt-3 text-xs text-slate-500">Tech: Python, pandas, Google Sheets API</p>
          <div class="mt-4 flex items-center justify-between text-sm">
            <a href="#" class="text-indigo-600 hover:underline">View script</a>
            <span class="text-slate-400">Sep 2025</span>
          </div>
        </article>

      </div>
    </section>

    <!-- Skills -->
    <section id="skills" class="bg-white p-6 rounded-2xl shadow-sm">
      <h3 class="text-2xl font-semibold">Skills</h3>
      <div class="mt-4 grid sm:grid-cols-2 lg:grid-cols-4 gap-4 text-sm">
        <div class="p-4 bg-slate-50 rounded-lg">SQL (BigQuery)</div>
        <div class="p-4 bg-slate-50 rounded-lg">Power BI & DAX</div>
        <div class="p-4 bg-slate-50 rounded-lg">Python (pandas, smtplib)</div>
        <div class="p-4 bg-slate-50 rounded-lg">Git & GitHub</div>
        <div class="p-4 bg-slate-50 rounded-lg">Data QC & Automation</div>
        <div class="p-4 bg-slate-50 rounded-lg">Excel & VBA</div>
        <div class="p-4 bg-slate-50 rounded-lg">Linux & Shell</div>
        <div class="p-4 bg-slate-50 rounded-lg">Reporting & Dashboards</div>
      </div>
    </section>

    <!-- Contact -->
    <section id="contact" class="bg-gradient-to-r from-indigo-50 to-cyan-50 p-6 rounded-2xl shadow-sm">
      <h3 class="text-2xl font-semibold">Contact</h3>
      <p class="mt-3 text-slate-600">Want this portfolio customised with your real projects, GitHub links and a downloadable CV? Send an email or create an issue in your repo and I'll help update it.</p>

      <div class="mt-4 flex flex-col sm:flex-row gap-4">
        <a href="mailto:pankaj.budhlakoti@clicflyer.com?subject=Portfolio%20Update" class="inline-block px-4 py-3 bg-indigo-600 text-white rounded-lg">Email me</a>
        <a href="https://github.com/" target="_blank" class="inline-block px-4 py-3 border border-indigo-600 rounded-lg text-indigo-600">View GitHub</a>
      </div>

      <div class="mt-6 text-sm text-slate-500">Tip: Replace placeholder text with your real projects and link each "View repo" to the corresponding GitHub repository.</div>
    </section>

  </main>

  <footer class="py-6">
    <div class="max-w-6xl mx-auto px-6 text-sm text-center text-slate-500">© { new Date().getFullYear() } Pankaj Budhlakoti — Built with ❤️ • <a href="#" class="underline">Download CV</a></div>
  </footer>

  <!-- Small helper script to replace the footer year (no build needed) -->
  <script>
    try {
      var el = document.querySelector('footer div');
      if (el) el.innerHTML = el.innerHTML.replace('{ new Date().getFullYear() }', new Date().getFullYear());
    } catch (e) { console.warn(e); }
  </script>
</body>
</html>
