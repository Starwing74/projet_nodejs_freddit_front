<template>
  <form @submit.prevent="onSignup()">
    <div class="bg-white rounded px-8 pt-6 pb-8 mb-4 flex flex-col">
      <div class="mb-4">
        <label class="block text-grey-darker text-sm font-bold mb-2" for="username">
          Username
        </label>
        <input class="shadow appearance-none border rounded w-full py-2 px-3 text-grey-darker" id="username" type="text"
               placeholder="Username">
      </div>
      <div class="mb-4">
        <label class="block text-grey-darker text-sm font-bold mb-2" for="email">
          Email
        </label>
        <input class="shadow appearance-none border rounded w-full py-2 px-3 text-grey-darker" id="email" type="email"
               placeholder="Email">
      </div>
      <div class="mb-6">
        <label class="block text-grey-darker text-sm font-bold mb-2" for="password">
          Password
        </label>
        <input class="shadow appearance-none border border-red rounded w-full py-2 px-3 text-grey-darker mb-3"
               id="password" type="password" placeholder="******************">
        <p class="text-red text-xs italic">Please choose a password.</p>
      </div>
      <div class="mb-6">
        <label class="block text-grey-darker text-sm font-bold mb-2" for="password">
          Confirm Password
        </label>
        <input class="shadow appearance-none border border-red rounded w-full py-2 px-3 text-grey-darker mb-3"
               id="passwordConfirm" type="password" placeholder="******************">
        <p class="text-red text-xs italic">Please confirm your password.</p>
      </div>
      <div class="flex items-center justify-between">
        <button class="bg-blue hover:bg-blue-dark text-white font-bold py-2 px-4 rounded" type="button">
          Sign Up
        </button>
        <router-link to="/login" class="inline-block align-baseline font-bold text-sm text-blue hover:text-blue-darker" href="#">
          Already signed up? Log in!
        </router-link>
      </div>
    </div>
  </form>
</template>

<script>

</script>
