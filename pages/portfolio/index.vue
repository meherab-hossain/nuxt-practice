<template>
  <div class="bg-gray-500">
    <div class="">
      <div class="flex justify-between shadow-md  p-4  bg-gray-500">
        <div class="flex justify-evenly">
          <ul>
            <li class="inline-flex text-white"><a>Home</a></li>
            <li class="inline-flex menu-bar">
              <a href="#projects">Project</a>
            </li>
            <li class="inline-flex menu-bar"><a>About Me</a></li>
            <li class="inline-flex menu-bar"><a>Contact</a></li>
            <li class="inline-flex menu-bar"><a>Resume</a></li>
          </ul>
        </div>
        <div class="flex justify-evenly">
          <div class="menu-bar">Linkdin</div>
          <div class="menu-bar">github</div>
          <div class="menu-bar mr-4">facebook</div>
        </div>
      </div>
      <div class="flex mt-16 ml-4">
        <div class="">
          I am a self-motivated learner love to dive into different areas of my
          interest and do experiment with it
        </div>
        <img
          src="~/assets/meherab.png"
          class="border object-fill h-64 w-64 rounded-full border-gray-100 shadow-sm"
          alt="stew"
        />
      </div>
      <section id="projects">
        <div class="h-60">projects</div>
      </section>
      <section id="all-projects">
        <div class="h-60"> View All Projects</div>
      </section>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>