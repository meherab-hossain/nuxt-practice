<template>
  <div class="bg-gray-800 font-body">
    <div class="">
      <div class="flex justify-between shadow-md p-4 bg-gray-900">
        <div class="flex justify-evenly">
          <ul>
            <li class="inline-flex ml-4 text-white"><a>Home</a></li>
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
      <div class="md:flex ml-4">
        <p class="text-xl text-white mt-20">Hi There,<br/> I'm <strong class="text-yellow-400">Meherab Hossain</strong><br/> <strong class="text-green-400">Junior Front End Developer</strong><br/>
          Programmer | Web Developer | Engineer  <br/>
          I am a <strong class="text-green-300">self-motivated</strong> learner love to dive <br/> into different areas of my
          interest and do experiment with it.
        </p class="text-xl">
        <div class="mt-14">
            <img
          src="~/assets/meherab.png"
          class="border object-fill h-64 w-64  rounded-full ml-4 border-gray-100 shadow-sm"
          alt="stew"
        />
        </div>
      </div>
      <section id="projects" class="ml-4 mr-4">
        <h4 class="font-bold pb-2 mt-12 border-yellow-600 border-b text-white">
          Recent Projects
        </h4>
        <div class="mt-8 grid md:grid-cols-3 gap-10">
          <!-- card starts here-->
          <div class="card hover:shadow-lg bg-gray-800">
            <img
              src="~/assets/forum.jpg"
              class="w-full object-cover h-32 sm:h-48"
              alt="stew"
            />
            <div class="font-body text-white ml-4 mt-4 tracking-wider">
              <h5 class="text-green-500">Real Time Single Page Forum</h5>
              <h4 class="text-yellow-400">(Front-End)</h4>
              <p>It's a vue js based forum where questions can be asked.</p>
            </div>
            <div class="p-4">
              <p class="btn bg-gray-500 text-center">
                <a
                  href="https://github.com/meherab-hossain/real-time-spa-forum-frontend"
                  target="_blank"
                  >Github Link</a
                >
              </p>
            </div>
          </div>
          <!-- card ends here-->

          <div class="card hover:shadow-lg bg-gray-800">
            <img
              src="~/assets/forum.jpg"
              class="w-full object-cover h-32 sm:h-48"
              alt="stew"
            />
            <div class="font-body text-white ml-4 mt-4 tracking-wider">
              <h5 class="text-green-500">Real Time Single Page Forum</h5>
              <h4 class="text-yellow-400">(Back-End)</h4>
              <p>It's a vue js based forum where questions can be asked.</p>
            </div>
            <div class="p-4">
              <p class="btn bg-gray-500 text-center">
                <a
                  href="https://github.com/meherab-hossain/real-time-spa-forum"
                  target="_blank"
                  >Github Link</a
                >
              </p>
            </div>
          </div>
          <!-- card ends here-->

          <div class="card hover:shadow-lg bg-gray-800">
            <img
              src="~/assets/forum.jpg"
              class="w-full object-cover h-32 sm:h-48"
              alt="stew"
            />
            <div
              class="font-body text-white ml-4 mt-4 tracking-wider"
            >
              <h5 class="text-green-500">React E-Bazar</h5>
              <h4 class="text-yellow-400">(Front-End)</h4>
              <p>It's a React js based e-bazar where anyone can do shopping</p>
            </div>
            <div class="p-4">
              <p class="btn bg-gray-500 text-center">
                <a
                  href="https://github.com/meherab-hossain/react-e-bazar"
                  target="_blank"
                  >Github Link</a
                >
              </p>
            </div>
          </div>
          <!-- card ends here-->
        </div>
      </section>
      <section id="all-projects">
        <div class="m-2 bg-red-600 text-center pb-2">View All Projects</div>
      </section>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>