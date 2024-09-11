<template>
  <nav class="w-full bg-emerald-600 px-20 py-3">
    <div class="flex justify-between">
      <!-- Left -->
      <div class="flex justify-center items-center gap-5">
        <!-- Logo -->
        <div>
          <div
            class="w-20 h-20 bg-red-400 rounded-md flex justify-center items-center"
          >
            <h1 class="font-bold">
              <span class="text-6xl">N</span><span class="text-xl">IT</span>
            </h1>
          </div>
        </div>
        <!-- Bran Name -->
        <div>
          <h1 class="font-bold text-xl">NIT Cambodia</h1>
          <p class="font-medium">Company shop | 15 brands</p>
        </div>
        <!-- Search Bar -->
        <div>
          <div class="flex h-10 justify-center items-center">
            <input
              class="w-72 px-3 h-10 rounded-l-md border border-r-stone"
              type="text"
              name="search"
              placeholder="Enter for search"
            />
            <!-- Logo search -->
            <img
              class="h-6 bg-white px-2 py-2 box-content rounded-r-md cursor-pointer"
              src="./../../assets/Img ICON/search Icon.png"
              alt="Search"
              title="Search "
            />
          </div>
        </div>
      </div>

      <!-- Right -->
      <div class="flex justify-center items-center gap-2">
        <!-- List of languages -->
        <div>
          <select id="lag" name="lag" class="px-2 py-2 rounded-md font-bold">
            <option value="eng">English</option>
            <option value="kh">Khmer</option>
            <option value="thai">Thai</option>
            <option value="viet">Vietnamist</option>
          </select>
        </div>
        <!-- Ring Icon -->
        <div>
          <img src="./../../assets/Img ICON/bell Icon.png" class="w-6" alt="bell">
        </div>
        <!-- Cart Icon -->
        <div>
          <img src="./../../assets/Img ICON/cart Icon.png" class="w-6" alt="bell">
        </div>
        <!-- Personal info cart -->
        <div class="flex justify-center items-center gap-2">
            <div>
              <h1 class="font-bold">Vathana Sroeun</h1>
              <h2>Not Single | 23ys</h2>
            </div>
            <div class="bg-white px-2 py-2 rounded-full flex justify-center">
              <img src="./../../assets/Img ICON/boy Person.png" class="w-9" alt="person">
            </div>
        </div>
      </div>
    </div>
  </nav>
</template>
<script setup></script>
