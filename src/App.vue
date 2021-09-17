<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <label class="block text-sm font-medium text-gray-700">
    testing
  </label>
  <div class="mt-1 flex rounded-md shadow-sm">
    <!--              <span-->
    <!--                  class="inline-flex items-center px-3 rounded-l-md border border-r-0 border-gray-300 bg-gray-50 text-gray-500 sm:text-sm">-->
    <!--                workcation.com/-->
    <!--              </span>-->
    <input
        
        class="border-gray-300 focus:ring-green-600 block w-full overflow-hidden cursor-pointer border text-gray-800 bg-white rounded-md shadow-sm focus:outline-none focus:ring-2 focus:border-transparent"
        aria-describedby="view_model_avatar_help" name="view_model[avatar]" type="file"
    >
<!--    <input :id="fieldName||fieldN" :value="modelValue" @input="valueChange" :placeholder="placeholder"-->
<!--           :type="type||'text'"-->
<!--           class="flex-1 focus:ring-green-500 focus:border-green-500 block w-full min-w-0 rounded-md sm:text-sm border-gray-300"/>-->
  </div>
</template>

<style>
::file-selector-button {
  @apply text-gray-800 bg-gray-300 hover:bg-gray-200
  font-medium text-sm cursor-pointer
  border-0 border-r border-solid border-gray-300
  py-2 pl-8 pr-4 rounded-none;
  margin-inline-start: -1rem;
  margin-inline-end: 1rem;
}
::-webkit-file-upload-button {
  @apply text-gray-800 bg-gray-300 hover:bg-gray-200
  font-medium text-sm cursor-pointer
  border-0 border-r border-solid border-gray-300
  py-2 pl-8 pr-4 rounded-none;
  margin-inline-start: -1rem;
  margin-inline-end: 1rem;
}
</style>
