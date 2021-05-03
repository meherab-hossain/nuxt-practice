<template>
  <div class="container">
    <div>
      <div>
        <nav>
          <div>
            <h1>
              <a href="/">Food Mania</a>
            </h1>
          </div>
          <ul>
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

      <main>
        <div>
          <a href="#">Log in</a>
          <a href="#">Sign up</a>
        </div>

        <header>
          <h2>Recipes</h2>
          <h3>For Food Mania</h3>
        </header>

        <div>
          <h4>Latest Recipes</h4>

          <div>
            <!-- cards go here -->
            <div>
              <img
                src="~/assets/classic-beef.jpg"
                class="sm:w-48 h-28"
                alt="stew"
              />
              <div>
                <span>Beef chini Stew </span>
                <span>Recipe by keka ferdousi</span>
              </div>
            </div>
          </div>

          <h4>Most Popular</h4>

          <div>
            <!-- cards go here -->
          </div>
        </div>

        <div>
          <div>Load more</div>
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
