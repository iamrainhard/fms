<template>
  <div
    class="flex flex-col justify-center items-center min-h-screen bg-gray-100"
  >
    <div
      class="flex flex-col w-full bg-white shadow-md border border-gray-200 rounded-lg max-w-md px-4 py-8 sm:px-6 md:px-8 lg:px-10 dark:bg-gray-800 dark:border-gray-700"
    >
      <form class="space-y-6" action="#">
        <h3 class="text-xl font-medium text-gray-900 dark:text-white">
          Sign in to our platform
        </h3>
        <div>
          <label
            for="email"
            class="text-sm font-medium text-gray-900 block mb-2 dark:text-gray-300"
            >Your email</label
          >
          <div class="relative">
            <div
              class="inline-flex items-center justify-center absolute left-0 top-0 h-full w-10 text-gray-400"
            >
              <i class="fas fa-at text-blue-500">
                <font-awesome-icon icon="fas fa-at"></font-awesome-icon>
              </i>
            </div>
            <input
              type="email"
              name="email"
              id="email"
              class="pl-10 pr-4 py-2 bg-gray-50 border border-gray-300 text-gray-900 sm:text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-600 dark:border-gray-500 dark:placeholder-gray-400 dark:text-white"
              placeholder="name@company.com"
              required=""
            />
          </div>
          <span class="text-red-200 italic font-light text-xs">error</span>
        </div>
        <div>
          <label
            for="password"
            class="text-sm font-medium text-gray-900 block mb-2 dark:text-gray-300"
            >Your password</label
          >
          <div class="relative">
            <div
              class="inline-flex items-center justify-center absolute left-0 top-0 h-full w-10 text-gray-400"
            >
              <i class="fas fa-at text-blue-500">
                <font-awesome-icon icon="fas fa-lock"></font-awesome-icon>
              </i>
            </div>
            <input
              type="password"
              name="password"
              id="password"
              placeholder="••••••••"
              class="pl-10 pr-4 py-2 bg-gray-50 border border-gray-300 text-gray-900 sm:text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-600 dark:border-gray-500 dark:placeholder-gray-400 dark:text-white"
              required=""
            />
          </div>
          <span class="text-red-200 italic font-light text-xs">error</span>
        </div>
        <div class="flex items-start">
          <div class="flex items-start">
            <div class="flex items-center h-5">
              <input
                id="remember"
                aria-describedby="remember"
                type="checkbox"
                class="bg-gray-50 border border-gray-300 focus:ring-3 focus:ring-blue-300 h-4 w-4 rounded dark:bg-gray-700 dark:border-gray-600 dark:focus:ring-blue-600 dark:ring-offset-gray-800"
                required=""
              />
            </div>
            <div class="text-sm ml-3">
              <label
                for="remember"
                class="font-medium text-gray-900 dark:text-gray-300"
                >Remember me</label
              >
            </div>
          </div>
          <a
            href="#"
            class="text-sm text-blue-700 hover:underline ml-auto dark:text-blue-500"
            >Forgot Password?</a
          >
        </div>
        <button
          type="submit"
          class="w-full text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
        >
          Login to your account
        </button>
        <div class="text-sm font-medium text-gray-500 dark:text-gray-300">
          Not registered?
          <nuxt-link
            to="/register"
            class="text-blue-700 hover:underline dark:text-blue-500"
          >
            Create account
          </nuxt-link>
        </div>
      </form>
    </div>
  </div>
</template>
