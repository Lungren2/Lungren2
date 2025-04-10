<!-- Tailwind CDN -->
<script src="https://cdn.tailwindcss.com"></script>
<!-- Custom theme colors -->
<script>
  tailwind.config = {
    theme: {
      extend: {
        colors: {
          primary: '#2f6bba',
          accent: '#ae74c8',
        },
        fontFamily: {
          code: ['Fira Code', 'monospace'],
        },
      },
    },
  };
</script>

<!-- Fira Code font -->
<link href="https://fonts.googleapis.com/css2?family=Fira+Code:wght@400;500;700&display=swap" rel="stylesheet">

<div class="bg-gray-100 text-gray-800 font-code p-8 rounded-xl max-w-6xl mx-auto">

  <!-- Header Section -->
  <div class="grid grid-cols-1 sm:grid-cols-[150px_1fr] items-center gap-6 mb-10">
    <img src="https://avatars.githubusercontent.com/u/60567681?v=4" alt="Profile" class="rounded-full w-[150px] border-4 border-primary" />
    <div>
      <h1 class="text-4xl font-bold text-primary">Lungren2</h1>
      <p class="text-lg mt-1">Software Developer | Web Specialist | Crafting Clean Code ✨</p>
    </div>
  </div>

  <!-- Tech Stack -->
  <div class="grid grid-cols-4 sm:grid-cols-8 gap-6 justify-items-center mb-12">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JS" class="w-10" title="JavaScript" />
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="TS" class="w-10" title="TypeScript" />
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" alt="React" class="w-10" title="React" />
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" alt="Node.js" class="w-10" title="Node.js" />
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="C#" class="w-10" title="C#" />
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" class="w-10" title="Python" />
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" alt="Docker" class="w-10" title="Docker" />
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" alt="Git" class="w-10" title="Git" />
  </div>

  <!-- GitHub Stats -->
  <div class="text-center mb-12">
    <img src="https://github-readme-stats.vercel.app/api?username=Lungren2&show_icons=true&bg_color=f4f6fa&title_color=2f6bba&icon_color=ae74c8&text_color=1e1e1e&border_color=ffffff" alt="GitHub Stats" class="mx-auto" />
  </div>

  <!-- GitHub Trophies -->
  <div class="text-center">
    <img src="https://github-profile-trophy.vercel.app/?username=Lungren2&theme=flat&title=ae74c8&margin-w=10&margin-h=10" alt="GitHub Trophies" class="mx-auto" />
  </div>
</div>
