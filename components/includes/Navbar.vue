<template>
  <div class="flex justify-between shadow-md p-4 bg-gray-900">
    <div class="flex justify-evenly">
      <ul>
        <li class="inline-flex ml-4 text-white">
          <router-link to="/portfolio">Home</router-link>
        </li>
        <li class="inline-flex menu-bar">
          <a href="#projects">Project</a>
        </li>
        <li class="inline-flex menu-bar">
          <router-link to="/about">About Me</router-link>
        </li>
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
</template>

<script>
export default {};
</script>

<style>
</style>