<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Lucas Paes Januzi - Resume</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Space+Grotesk:wght@500;600&display=swap" rel="stylesheet">
  <style>
    body { font-family: 'Inter', system-ui, sans-serif; }
    .title-font { font-family: 'Space Grotesk', sans-serif; }
    .accent { color: #00d4ff; }
    .section-title { position: relative; }
    .section-title:after {
      content: '';
      position: absolute;
      width: 60px;
      height: 3px;
      background: #00d4ff;
      bottom: -4px;
      left: 0;
    }
  </style>
</head>
<body class="bg-zinc-950 text-zinc-100 leading-relaxed">
  <div class="max-w-4xl mx-auto bg-white text-zinc-900 shadow-2xl min-h-[297mm] p-10">
    
    <!-- HEADER -->
    <div class="border-b border-zinc-200 pb-6 mb-8">
      <div class="flex justify-between items-start">
        <div>
          <h1 class="title-font text-5xl font-semibold tracking-tight">Lucas Paes Januzi</h1>
          <p class="text-2xl text-zinc-600 mt-1">Technical Lead • Full-Stack Software Engineer</p>
          <div class="flex gap-2 mt-3 text-sm">
            <span class="bg-zinc-100 text-zinc-700 px-3 py-1 rounded-full font-medium">JS • C# • TypeScript • React • .NET • Node.js</span>
          </div>
        </div>
        <div class="text-right text-sm">
          <p class="mb-1">📍 Belo Horizonte, MG, Brazil</p>
          <p class="mb-1">📱 +55 (31) 99100-2330</p>
          <a href="https://linkedin.com/in/lucas-paes-januzi" target="_blank" style="text-wrap: nowrap;">🔗 linkedin.com/in/lucas-paes-januzi</a>
        </div>
      </div>
    </div>

    <!-- ABOUT ME -->
    <div class="mb-10">
      <h2 class="section-title text-xl font-semibold mb-4">About Me</h2>
      <p class="text-zinc-600 text-[15.2px] leading-relaxed">
        Software Engineer and <strong>Tech Lead</strong> passionate about transforming complex challenges into agile, scalable, and user-centered solutions.
        Graduated in Computer Science from COTEMIG and Full-Stack specialist from Trybe.
      </p>
      <p class="text-zinc-600 text-[15.2px] leading-relaxed mt-4">
        In recent years, I have led the development of <strong>facial and fingertip biometry SDKs</strong>, AI-powered microservices for interpreting medical orders, and advanced automations through reverse engineering — drastically reducing execution time and generating significant financial gains.
      </p>
      <p class="text-zinc-600 text-[15.2px] leading-relaxed mt-4">
        <strong>Specialist in web crawlers and routine automations.</strong> I work end-to-end (frontend, backend, and architecture) with a strong focus on performance, user experience, and technical leadership.
      </p>
    </div>

    <!-- EXPERIENCE -->
    <div class="mb-10">
      <h2 class="section-title text-xl font-semibold mb-5">Professional Experience</h2>
      
      <div class="mb-8">
        <div class="flex justify-between">
          <div>
            <p class="font-semibold">Technical Lead (Frontend) & Full-Stack Developer</p>
            <p class="text-teal-600">IconCode • Brazil</p>
          </div>
          <p class="text-zinc-500 text-sm">Aug/2022 – Present • 3 years and 9 months</p>
        </div>
        <ul class="list-disc ml-5 mt-3 text-zinc-600 text-[15px] space-y-2">
          <li>Led the complete frontend lifecycle (UI/UX, components, testing, deployment, and performance) using React.js, Next.js, AngularJS, and TypeScript.</li>
          <li>Designed and developed facial and fingertip biometry SDKs for patient identification in partner portals.</li>
          <li>Architected intelligent microservices using AI to read and structure medical orders.</li>
          <li>Developed advanced automations through reverse engineering, drastically reducing execution time and increasing client productivity and financial results.</li>
          <li>Provided team mentoring, code review, and strategic architectural decisions.</li>
        </ul>
      </div>

      <div class="text-zinc-500 text-sm mb-8">
        <strong>Legal Intern</strong> • Inocêncio de Paula - Judicial Administrator • 2019 – 2021<br>
        Developed strong analytical skills and complex problem-solving abilities (applied today in coding and stakeholder communication).
      </div>

      <div class="text-zinc-500 text-sm">
        <strong>IT Support</strong> • BHS, Samp and Promed • 2017 – 2018<br>
        Solid foundation in problem-solving under pressure and customer-first approach.
      </div>
    </div>

    <!-- EDUCATION -->
    <div class="mb-10">
      <h2 class="section-title text-xl font-semibold mb-4">Education</h2>
      <div class="grid grid-cols-2 gap-6 text-sm">
        <div>
          <p class="font-semibold">Full-Stack Web Developer</p>
          <p class="text-teal-600">Trybe • 2022 – 2023</p>
        </div>
        <div>
          <p class="font-semibold">Bachelor's Degree in Law</p>
          <p class="text-zinc-500">Faculdades Milton Campos • 2018 – 2021</p>
        </div>
        <div>
          <p class="font-semibold">Computer Science Technician</p>
          <p class="text-zinc-500">COTEMIG • 2015 – 2017</p>
        </div>
      </div>
    </div>

    <!-- SKILLS -->
    <div>
      <h2 class="section-title text-xl font-semibold mb-4">Technical Skills</h2>
      <div class="grid grid-cols-3 gap-3 text-sm">
        <div class="bg-zinc-100 px-4 py-3 rounded-2xl">React.js • Next.js</div>
        <div class="bg-zinc-100 px-4 py-3 rounded-2xl">TypeScript • JavaScript</div>
        <div class="bg-zinc-100 px-4 py-3 rounded-2xl">C# • .NET 6/7</div>
        <div class="bg-zinc-100 px-4 py-3 rounded-2xl">Node.js • AngularJS</div>
        <div class="bg-zinc-100 px-4 py-3 rounded-2xl">SQL • PostgreSQL</div>
        <div class="bg-zinc-100 px-4 py-3 rounded-2xl">Azure • Git • CI/CD</div>
        <div class="bg-zinc-100 px-4 py-3 rounded-2xl">Web Crawlers & Automations</div>
        <div class="bg-zinc-100 px-4 py-3 rounded-2xl">AI Microservices</div>
        <div class="bg-zinc-100 px-4 py-3 rounded-2xl">Reverse Engineering</div>
      </div>
      <p class="text-xs text-zinc-400 mt-4">Technical Leadership • Mentoring • Scrum • Kanban • SOLID • Automated Testing</p>
    </div>

  </div>
</body>
</html>
