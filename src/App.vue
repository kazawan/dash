<template>
  <div class="w-full h-[100vh] grid grid-cols-12 transition-all">
    <div
      class="w-full h-full col-span-2 bg-gray-900 font-bold border-gray-300 border-r-2 pt-2 select-none cursor-pointer"
    >
      <div class="flex flex-col border-gray-100 border-b-2 pb-2">
        <ul class="w-full px-2">
          <li
            class="justify-start items-start mb-2 text-lg text-green-500 hover:bg-gray-100 hover:text-green-600"
          >
            <Box16Filled class="w-6 inline-block text-green-500" /> kazawan
          </li>
        </ul>
        <ul class="w-full px-4">
          <li onclick="my_modal_2.showModal()"
            class="w-full justify-start items-start text-sm text-gray-500 hover:bg-slate-400 mb-1 hover:border-r-4 border-green-400"
          >
            <Search28Filled class="w-6 inline-block" /> 搜索 <kbd class="kbd kbd-xs bg-slate-100">ctrl</kbd> + <kbd class="  kbd kbd-xs bg-slate-100">Y</kbd>
            
          </li>
          <li
            class="w-full justify-start items-start text-sm text-gray-500 hover:bg-slate-400 mb-1 hover:border-r-4 border-green-400"
          >
            <WeatherCloudy24Filled class="w-6 inline-block" /> 天气
          </li>
          <li
            class="w-full justify-start items-start text-sm text-gray-500 hover:bg-slate-400 mb-1 hover:border-r-4 border-green-400"
          >
            <CalendarWorkWeek16Filled class="w-6 inline-block" /> Planer
          </li>
          <li
            class="w-full justify-start items-start text-sm text-gray-500 hover:bg-slate-400 mb-1 hover:border-r-4 border-green-400"
          >
            <AppsList20Filled class="w-6 inline-block" /> 代办
          </li>
          <li
            class="w-full justify-start items-start text-sm text-gray-500 hover:bg-slate-400 mb-1 hover:border-r-4 border-green-400"
          >
            <BookNumber16Filled class="w-6 inline-block" /> 文档
          </li>
        </ul>
      </div>
      <ul class="w-full px-4 mt-2 text-gray-100">
        <li class="text-green-500">
          <BinFull20Regular class="w-6 inline-block" /> NAS 容量
        </li>
        <li class="text-xs mt-2">
          外接硬盘容量
          <progress
            class="progress progress-success w-full"
            value="10"
            max="100"
          ></progress>
        </li>
        <li class="text-xs mt-2">
          本地硬盘容量
          <progress
            class="progress progress-success w-full"
            value="60"
            max="100"
          ></progress>
        </li>
      </ul>
    </div>
   

    <div class="w-full h-full bg-slate-200 col-span-10 flex justify-center items-center">
      <div class=" w-4/5 h-full text-center flex">
        <div class="w-full h-full flex flex-col justify-center items-center">
          <h1 class="text-6xl font-bold text-gray-700">Kazawan</h1>
          <h2 class="text-2xl font-bold text-gray-500">A simple dashboard</h2>
        </div>    
      </div>
      <dialog id="my_modal_2" class="modal  ">
        <div class="modal-box bg-gray-200  rounded-md p-0  h-16 ">
          <input type="text" class=" bg-transparent w-full outline-none px-2 py-1 " placeholder="Search...">
        </div>
        <form method="dialog" class="modal-backdrop">
          <button>close</button>
        </form>
      </dialog>
    </div>

    
    
    
  </div>
</template>

<script setup>
import { ref, watchEffect } from "vue";

import {
  Box16Filled,
  Search28Filled,
  WeatherCloudy24Filled,
  BookNumber16Filled,
  CalendarWorkWeek16Filled,
  AppsList20Filled,
  BinFull20Regular,
} from "@vicons/fluent";
import { useMagicKeys } from '@vueuse/core'
//ctrl + k onpen search modal

const { ctrl, y} = useMagicKeys()
watchEffect(() => {
  if (ctrl.value && y.value)
    my_modal_2.showModal()
})










</script>


