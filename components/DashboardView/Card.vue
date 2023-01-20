<template>
  <div class="w-full shadow">
    <header>
      <slot name="header" />
      <div class="flex fex-row items-center justify-between">
        <h3>
          <slot name="title" />
        </h3>

        <div class="flex flex-row gap-x-2">
          <slot name="actions" />
        </div>
      </div>
    </header>

    <div>
      <slot name="content" />
    </div>

    <footer>
      <slot name="footer" />
    </footer>
  </div>
</template>
