<script setup lang="ts"></script>

<template>
  <div>
    <UiNavbarDashboard />

    <main class="m-6 p-3 shadow">
      <div class="flex flex-row gap-x-6 justify-between items-center">
        <DashboardViewCard>
          <template #title>
            Overview
          </template>

          <template #content>
            Le corps
          </template>
        </DashboardViewCard>

        <DashboardViewCard>
          <template #title>
            Overview
          </template>

          <template #content>
            Le corps
          </template>
        </DashboardViewCard>
      </div>

      <div class="grid grid-cols-12 flex-row mt-6 gap-x-6 justify-between items-center">
        <DashboardViewCard class="col-span-4">
          <template #title>
            Overview
          </template>

          <template #content>
            Le corps
          </template>
        </DashboardViewCard>

        <DashboardViewCard class="col-span-8">
          <template #title>
            Overview
          </template>

          <template #content>
            Le corps
          </template>
        </DashboardViewCard>
      </div>
    </main>
  </div>
</template>
