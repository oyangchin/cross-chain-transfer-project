<script setup lang="ts">
</script>

<template>
  <div class="flex">
    <!-- Source Region -->
  
      <div class="flex-5 p-8 mx-auto bg-white rounded-sm shadow-md ">
        <h2 class="font-semibold leading-7 text-gray-900 text-lg">SOURCE</h2>
        <p class="mt-1 text-sm leading-6 text-gray-600">請選擇要轉出的錢包與幣別</p>
        <div class="mt-10 grid grid-cols-1 gap-x-6 gap-y-8 sm:grid-cols-6">
          <div class="col-span-full">
            <label for="country" class="block text-sm font-medium leading-6 text-gray-900">From this network</label>
            <div class="mt-2">
              <select id="country" name="country" autocomplete="country-name" class="block w-full rounded-md border-0 py-1.5 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:max-w-xs sm:text-sm sm:leading-6">
                <option>United States</option>
                <option>Canada</option>
                <option>Mexico</option>
              </select>
            </div>
          </div>

          <div class="col-span-full">
            <label for="country" class="block text-sm font-medium leading-6 text-gray-900">Currency</label>
            <div class="mt-2">
              <select id="country" name="country" autocomplete="country-name" class="block w-full rounded-md border-0 py-1.5 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:max-w-xs sm:text-sm sm:leading-6">
                <option>United States</option>
                <option>Canada</option>
                <option>Mexico</option>
              </select>
            </div>
          </div>

          <div class="col-span-full">
            <label for="first-name" class="block text-sm font-medium leading-6 text-gray-900">You send</label>
            <div class="relative mt-2 rounded-md shadow-sm">
              <div class="pointer-events-none absolute inset-y-0 left-0 flex items-center pl-3">
                <span class="text-gray-500 sm:text-sm">$</span>
              </div>
              <input type="text" name="price" id="price" class="block w-full rounded-md border-0 py-1.5 pl-7 pr-12 text-gray-900 ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6" placeholder="0.00" aria-describedby="price-currency">
            </div>
          </div>

          <div class="col-span-full border-b-2 border-blue-500">
            <fieldset>
              <legend class="text-sm font-semibold leading-6 text-gray-900">Your Balance</legend>
              <p class="mt-1 text-sm leading-6 text-gray-600">999</p>
            </fieldset>
          </div>
        </div>
      </div>
    
    <!-- Transfer Button Region -->
    <div class="flex-2 p-8 col-span-full align-center">
      <div class="mt-2 flex items-center gap-x-3">
        <button type="button" class="rounded-md bg-white px-2.5 py-1.5 text-sm font-semibold text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 hover:bg-gray-50">Transfer</button>
      </div>
    </div>
    <!-- Destination Region -->
    <div class="flex-5 p-8 mx-auto bg-white rounded-sm shadow-md">
      <h2 class="font-semibold leading-7 text-gray-900 text-lg">DESTINATION</h2>
      <p class="mt-1 text-sm leading-6 text-gray-600">請選擇要轉入的錢包與幣別</p>
      <div class="mt-10 grid grid-cols-1 gap-x-6 gap-y-8 sm:grid-cols-6">
        <div class="col-span-full">
          <label for="country" class="block text-sm font-medium leading-6 text-gray-900">To this network</label>
          <div class="mt-2">
            <select id="country" name="country" autocomplete="country-name" class="block w-full rounded-md border-0 py-1.5 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:max-w-xs sm:text-sm sm:leading-6">
              <option>United States</option>
              <option>Canada</option>
              <option>Mexico</option>
            </select>
          </div>
        </div>

        <div class="col-span-full">
          <label for="country" class="block text-sm font-medium leading-6 text-gray-900">Currency</label>
          <div class="mt-2">
            <select id="country" name="country" autocomplete="country-name" class="block w-full rounded-md border-0 py-1.5 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:max-w-xs sm:text-sm sm:leading-6">
              <option>United States</option>
              <option>Canada</option>
              <option>Mexico</option>
            </select>
          </div>
        </div>

        <div class="col-span-full">
          <label for="first-name" class="block text-sm font-medium leading-6 text-gray-900">You receive</label>
          <div class="relative mt-2 rounded-md shadow-sm">
            <div class="pointer-events-none absolute inset-y-0 left-0 flex items-center pl-3">
              <span class="text-gray-500 sm:text-sm">$</span>
            </div>
            <input type="text" name="price" id="price" class="block w-full rounded-md border-0 py-1.5 pl-7 pr-12 text-gray-900 ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6" placeholder="0.00" aria-describedby="price-currency">
          </div>
        </div>

        <div class="col-span-full border-b-2 border-blue-500">
          <fieldset>
            <legend class="text-sm font-semibold leading-6 text-gray-900">Your Balance</legend>
            <p class="mt-1 text-sm leading-6 text-gray-600">999</p>
          </fieldset>
        </div>
      </div>
    </div>

    
  </div>
</template>

<style scoped>
.align-center {
  align-self: center;
}

</style>
