<template>
  <div class="bg-gray-800 font-body">
    <div>
      <Navbar></Navbar>
      <div class="md:flex ml-4">
        <p class="text-xl text-white mt-20">
          Hi There,<br />
          I'm <strong class="text-yellow-400">Meherab Hossain</strong><br />
          <strong class="text-green-400">Junior Front End Developer</strong
          ><br />
          Programmer | Web Developer | Engineer <br />
          I am a <strong class="text-green-300">self-motivated</strong> learner
          love to dive <br />
          into different areas of my interest and do experiment with it.<br />
          <Span class="btn bg-gray-600 text-white"
            ><a
              href="https://www.facebook.com/meherab.hossain.79/"
              target="_blank"
              >Hire Me</a
            ></Span
          >
          <Span class="btn bg-gray-600 text-white">
            <router-link to="/about">More About Me</router-link>
          </Span>
        </p>
        <div class="mt-14">
          <img
            src="~/assets/meherab.png"
            class="border object-fill h-64 w-64 rounded-full ml-4 border-gray-100 shadow-sm"
            alt="meherab"
          />
        </div>
      </div>
      <section id="projects" class="ml-4 mr-4">
        <h4 class="font-bold pb-2 mt-12 border-yellow-600 border-b text-white">
          Recent Projects
        </h4>
        <div class="flex flex-wrap">
          <div class="p-4 sm:w-1/2 lg:w-1/3">
            <div class="shadow-lg rounded-lg overflow-hidden">
              <img
                class="lg:h-72 md:h-48 w-full object-cover object-center"
                src="~/assets/forum.jpg"
                alt="blog"
              />
              <div
                class="p-6 font-body tracking-wider hover:bg-indigo-700 hover:text-white transition duration-300 ease-in"
              >
                <h2 class="text-base font-medium text-indigo-300 mb-1">
                  Real Time Single Page Forum.
                </h2>
                <h1 class="text-2xl text-yellow-400 font-semibold mb-3">
                  (Front-End)
                </h1>
                <p class="leading-relaxed mb-3 font-bold text-white">
                  It's a vue js based forum where questions can be asked.
                </p>
                <div class="flex items-center flex-wrap">
                  <a
                    href="https://github.com/meherab-hossain/real-time-spa-forum-frontend"
                    target="_blank"
                    class="text-indigo-300 inline-flex items-center md:mb-2 lg:mb-0"
                    >Github Link
                  </a>
                </div>
              </div>
            </div>
          </div>
          <div class="p-4 sm:w-1/2 lg:w-1/3">
            <div
              class="h-full hover:shadow-lg shadow-lg rounded-lg overflow-hidden"
            >
              <img
                class="lg:h-72 md:h-48 w-full object-cover object-center"
                src="~/assets/forum.jpg"
                alt="forum"
              />
              <div
                class="p-6 font-body tracking-wider hover:bg-indigo-700 hover:text-white transition duration-300 ease-in"
              >
                <h2 class="text-base font-medium text-indigo-300 mb-1">
                  Real Time Single Page Forum
                </h2>
                <h1 class="text-2xl text-yellow-400 font-semibold mb-3">
                  (Back-End)
                </h1>
                <p class="leading-relaxed mb-3 font-bold text-white">
                  It's a vue js based forum where questions can be asked.
                </p>
                <div class="flex items-center flex-wrap">
                  <a
                    href="https://github.com/meherab-hossain/real-time-spa-forum"
                    target="_blank"
                    class="text-indigo-300 inline-flex items-center md:mb-2 lg:mb-0"
                    >Github Link
                  </a>
                </div>
              </div>
            </div>
          </div>
          <div class="p-4 sm:w-1/2 lg:w-1/3">
            <div
              class="h-full hover:shadow-lg shadow-lg rounded-lg overflow-hidden"
            >
              <img
                class="lg:h-72 md:h-48 w-full object-cover object-center"
                src="~/assets/forum.jpg"
                alt="forum"
              />
              <div
                class="p-6 font-body tracking-wider hover:bg-indigo-700 hover:text-white transition duration-300 ease-in"
              >
                <h2 class="text-base font-medium text-indigo-300 mb-1">
                  React E-Bazar
                </h2>
                <h1 class="text-2xl text-yellow-400 font-semibold mb-3">
                  (Back-End)
                </h1>
                <p class="leading-relaxed mb-3 font-bold text-white">
                  It's a React js based e-bazar where anyone can do shopping
                </p>
                <div class="flex items-center flex-wrap">
                  <a
                    href="https://github.com/meherab-hossain/react-e-bazar"
                    target="_blank"
                    class="text-indigo-300 inline-flex items-center md:mb-2 lg:mb-0"
                    >Github Link
                  </a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
      <section id="all-projects">
        <div class="m-2 bg-red-600 text-center pb-2">View All Projects</div>
      </section>
    </div>
  </div>
</template>

<script>
import Navbar from "~/components/includes/Navbar.vue";
export default {
  components: {
    Navbar,
  },
};
</script>

<style>
</style>