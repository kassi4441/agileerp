<script setup lang="ts"></script>

<template>
  <nav class="bg-white border-gray-200 px-2 sm:px-4 rounded dark:bg-gray-900 shadow">
    <div class="container flex flex-wrap items-center justify-between mx-auto">
      <div class="flex flex-row items-center gap-x-4">
        <IconMenu />

        <h2>Tableau de bord</h2>

        <ul class="flex flex-row gap-x-5 ml-4 items-center">
          <UiNavbarItem title="Acceuil" :is-active="true" />
          <UiNavbarItem title="Opportinités" :is-active="true" />
          <UiNavbarItem title="Compte" :is-active="true" />

          <!-- <li class="text-purBlue border-b-3 border-purBlue pt-3.5 pb-2.5">
            <NuxtLink>
              Acceuil
            </NuxtLink>
          </li>
          <li class="py-3.5">
            <NuxtLink>
              Opportinités
            </NuxtLink>
          </li>
          <li class="py-1.5 my-2 px-3.5 font-bold rounded cursor-default bg-coolBlue text-purBlue">
            <NuxtLink>
              Compte
            </NuxtLink>
          </li> -->
        </ul>
      </div>

      <div class="flex flex-row gap-x-4 items-center">
        <div class="i-carbon-notification-filled" />
        <div class="i-carbon-help-filled" />
        <IconSetting />

        <button id="user-menu-button" type="button" class="flex mr-3 text-sm bg-gray-800 rounded-full md:mr-0 focus:ring-4 focus:ring-gray-300 dark:focus:ring-gray-600" aria-expanded="false" data-dropdown-toggle="user-dropdown" data-dropdown-placement="bottom">
          <span class="sr-only">Open user menu</span>
          <img class="w-8 h-8 rounded-full" src="/avatar/userprofile.png" alt="user photo">
        </button>
      </div>
    </div>
  </nav>
</template>
