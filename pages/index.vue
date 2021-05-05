<template>
  <div class="text-gray-400 font-body">
    <div>
      <div>
        <nav>
          <div>
            <h1>
              <a href="/" class="font-bold uppercase p-4 border-b"
                >Food Mania</a
              >
            </h1>
          </div>
          <ul class="text-gray-700 font-bold">
            <li>
              <a href="#">
                <span>Home</span>
              </a>
            </li>
            <li>
              <a href="#">
                <span>About</span>
              </a>
            </li>
            <li>
              <a href="#">
                <span>Contact</span>
              </a>
            </li>
          </ul>
        </nav>
      </div>

      <main class="px-16 py-6 bg-gray-100">
        <div class="flex justify-center md:justify-end">
          <a href="#" class="text-primary">Log in</a>
          <a href="#" class="text-primary">Sign up</a>
        </div>

        <header>
          <h2 class="text-gray-700 text-6xl font-semibold">Recipes</h2>
          <h3 class="text-2xl font-semibold">For Food Mania</h3>
        </header>

        <div>
          <h4 class="font-bold pb-2 mt-12 border-b">Latest Recipes</h4>

          <div>
            <!-- cards go here -->
            <div class="card">
              <img
                src="~/assets/classic-beef.jpg"
                class="w-full object-cover h-32 sm:h-48"
                alt="stew"
              />
              <div class="m-4">
                <span class="font-bold">Beef chini Stew </span>
                <span class="block text-gray-500 text-sm"
                  >Recipe by keka ferdousi</span
                >
              </div>
              <div>
                <span
                  class="badge"
                  >25 mins</span
                >
              </div>
            </div>
          </div>

          <h4 class="font-bold pb-2 mt-12 border-b">Most Popular</h4>

          <div class="mt-8">
            <!-- cards go here -->
          </div>
        </div>

        <div class="flex justify-center">
          <div class="bg-secondary-100 text-secondary-200">Load more</div>
        </div>
      </main>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
</style>
