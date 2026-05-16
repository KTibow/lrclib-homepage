<template>
  <div class="bg-indigo-50 rounded overflow-hidden shadow-lg dark:bg-slate-900">
    <h2 class="text-xl bg-indigo-200 p-4 dark:bg-slate-800 dark:text-slate-100"><slot name="title" /></h2>
    <div class="p-4">
      <div class="bg-indigo-200 rounded flex p-1 gap-1 mb-8 dark:bg-slate-800">
        <div class="bg-indigo-700 rounded p-1 font-bold uppercase text-white dark:bg-indigo-500"><slot name="method" /></div>
        <div class="p-1 grow dark:text-slate-100"><slot name="route" /></div>
      </div>
      <div class="prose prose-indigo dark:prose-invert">
        <slot name="description" />
      </div>
    </div>
  </div>
</template>
