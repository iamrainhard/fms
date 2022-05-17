<template>
  <div class="flex flex-col justify-center items-center min-h-screen">
    <div
      class="flex flex-col w-full bg-white shadow-md border border-gray-200 rounded-lg max-w-md px-4 py-8 sm:px-6 md:px-8 lg:px-10 dark:bg-gray-800 dark:border-gray-700"
    >
      <form class="space-y-6" action="#">
        <h3 class="text-xl font-medium text-gray-900 dark:text-white">
          Register an account
        </h3>
        <div>
          <label
            for="name"
            class="text-sm font-medium text-gray-900 block mb-2 dark:text-gray-300"
            >Full Name</label
          >
          <div class="relative">
            <div
              class="inline-flex items-center justify-center absolute left-0 top-0 h-full w-10 text-gray-400"
            >
              <i class="fas fa-at text-blue-500">
                <font-awesome-icon icon="fas fa-user"></font-awesome-icon>
              </i>
            </div>
            <input
              type="text"
              name="name"
              id="name"
              class="pl-10 pr-4 py-2 bg-gray-50 border border-gray-300 text-gray-900 sm:text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-600 dark:border-gray-500 dark:placeholder-gray-400 dark:text-white"
              placeholder="John Doe"
              required=""
            />
          </div>
        </div>
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
        </div>
        <div>
          <label
            for="password_confirmation"
            class="text-sm font-medium text-gray-900 block mb-2 dark:text-gray-300"
            >Confirm Password</label
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
              name="password_confirmation"
              id="confirm_password"
              placeholder="••••••••"
              class="pl-10 pr-4 py-2 bg-gray-50 border border-gray-300 text-gray-900 sm:text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-600 dark:border-gray-500 dark:placeholder-gray-400 dark:text-white"
              required=""
            />
          </div>
        </div>
        <button
          type="submit"
          class="w-full text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
        >
          Register your account
        </button>
        <div class="text-sm font-medium text-gray-500 dark:text-gray-300">
          Already registered?
          <nuxt-link
            to="/login"
            class="text-blue-700 hover:underline dark:text-blue-500"
          >
            Login to your account
          </nuxt-link>
        </div>
      </form>
    </div>
  </div>
</template>
