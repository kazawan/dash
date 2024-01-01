<template>
  <div class="w-full h-full grid grid-cols-12 transition-all">
    <div
      class="w-full h-full col-span-2 bg-gray-900 font-bold border-gray-300 border-r-2 pt-2 select-none cursor-pointer"
    >
      <div class="flex flex-col border-gray-100 border-b-2 pb-2">
        <ul class="w-full px-2">
          <li
            class="justify-start items-start mb-2 text-lg text-green-500 hover:bg-gray-100 hover:text-green-600"
          >
            <Box16Filled class="w-6 inline-block text-green-500" /> kazawan.io
          </li>
        </ul>
        <ul class="w-full px-4">
          <itembar onclick="my_modal_2.showModal()">
            <Search28Filled class="w-6 inline-block" /> 搜索
            <kbd class="kbd kbd-xs bg-slate-100">ctrl</kbd> +
            <kbd class="kbd kbd-xs bg-slate-100">Y</kbd>
          </itembar>

          <itembar>
            <WeatherCloudy24Filled class="w-6 inline-block" /> 天气
          </itembar>

          <itembar>
            <CalendarWorkWeek16Filled class="w-6 inline-block" /> Planer
          </itembar>

          <itembar>
            <AppsList20Filled class="w-6 inline-block" /> 代办
          </itembar>

          <itembar>
            <BookNumber16Filled class="w-6 inline-block" /> 文档
          </itembar>
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

    <div
      class="relative w-full h-full bg-gray-800 col-span-10 flex flex-col justify-center items-center  overflow-y-scroll"
    >
      <div
        id="hero"
        class="relative w-full h-1/6 bg-[url('https://images.pexels.com/photos/2378278/pexels-photo-2378278.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2')] bg-cover flex justify-center"
      >
        <div class="w-4/6 text-6xl text-gray-300 absolute bottom-[-20px]">
          <span> 🏖️ </span>
          <span> Kazawan.io </span>
        </div>
      </div>

      <div
        id="content"
        class="w-full h-5/6 bg-gray-800 p-10 flex justify-center"
      >
        <div class="w-4/6 min-h-4/6 h-fit bg-gray-800 ">
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras non
            ipsum eget nisl tincidunt efficitur. Quisque lorem metus,
            sollicitudin id mi id, sodales condimentum diam. Class aptent taciti
            sociosqu ad litora torquent per conubia nostra, per inceptos
            himenaeos. Curabitur vulputate tellus libero, non gravida sem
            fringilla at. Donec imperdiet arcu eu porta vulputate. Nunc augue
            odio, sagittis ac tristique quis, ornare a turpis. Suspendisse
            tempus imperdiet dolor. Integer ac est eget lectus faucibus viverra.
            Vestibulum malesuada, augue ac tempor interdum, nisi lacus semper
            dui, ullamcorper sollicitudin ex tortor sed risus. Nunc eget leo vel
            erat blandit sollicitudin id eu ipsum. Suspendisse ut molestie
            purus. Phasellus ornare ante sagittis quam posuere tempor. Sed
            pretium ex purus, eget dignissim arcu scelerisque nec. Phasellus
            eget lectus at dui pharetra tincidunt a nec lacus. Vivamus tristique
            ligula quis ultricies fermentum. Aenean id ultrices diam.
          </p>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras non
            ipsum eget nisl tincidunt efficitur. Quisque lorem metus,
            sollicitudin id mi id, sodales condimentum diam. Class aptent taciti
            sociosqu ad litora torquent per conubia nostra, per inceptos
            himenaeos. Curabitur vulputate tellus libero, non gravida sem
            fringilla at. Donec imperdiet arcu eu porta vulputate. Nunc augue
            odio, sagittis ac tristique quis, ornare a turpis. Suspendisse
            tempus imperdiet dolor. Integer ac est eget lectus faucibus viverra.
            Vestibulum malesuada, augue ac tempor interdum, nisi lacus semper
            dui, ullamcorper sollicitudin ex tortor sed risus. Nunc eget leo vel
            erat blandit sollicitudin id eu ipsum. Suspendisse ut molestie
            purus. Phasellus ornare ante sagittis quam posuere tempor. Sed
            pretium ex purus, eget dignissim arcu scelerisque nec. Phasellus
            eget lectus at dui pharetra tincidunt a nec lacus. Vivamus tristique
            ligula quis ultricies fermentum. Aenean id ultrices diam.
          </p>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras non
            ipsum eget nisl tincidunt efficitur. Quisque lorem metus,
            sollicitudin id mi id, sodales condimentum diam. Class aptent taciti
            sociosqu ad litora torquent per conubia nostra, per inceptos
            himenaeos. Curabitur vulputate tellus libero, non gravida sem
            fringilla at. Donec imperdiet arcu eu porta vulputate. Nunc augue
            odio, sagittis ac tristique quis, ornare a turpis. Suspendisse
            tempus imperdiet dolor. Integer ac est eget lectus faucibus viverra.
            Vestibulum malesuada, augue ac tempor interdum, nisi lacus semper
            dui, ullamcorper sollicitudin ex tortor sed risus. Nunc eget leo vel
            erat blandit sollicitudin id eu ipsum. Suspendisse ut molestie
            purus. Phasellus ornare ante sagittis quam posuere tempor. Sed
            pretium ex purus, eget dignissim arcu scelerisque nec. Phasellus
            eget lectus at dui pharetra tincidunt a nec lacus. Vivamus tristique
            ligula quis ultricies fermentum. Aenean id ultrices diam.
          </p>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras non
            ipsum eget nisl tincidunt efficitur. Quisque lorem metus,
            sollicitudin id mi id, sodales condimentum diam. Class aptent taciti
            sociosqu ad litora torquent per conubia nostra, per inceptos
            himenaeos. Curabitur vulputate tellus libero, non gravida sem
            fringilla at. Donec imperdiet arcu eu porta vulputate. Nunc augue
            odio, sagittis ac tristique quis, ornare a turpis. Suspendisse
            tempus imperdiet dolor. Integer ac est eget lectus faucibus viverra.
            Vestibulum malesuada, augue ac tempor interdum, nisi lacus semper
            dui, ullamcorper sollicitudin ex tortor sed risus. Nunc eget leo vel
            erat blandit sollicitudin id eu ipsum. Suspendisse ut molestie
            purus. Phasellus ornare ante sagittis quam posuere tempor. Sed
            pretium ex purus, eget dignissim arcu scelerisque nec. Phasellus
            eget lectus at dui pharetra tincidunt a nec lacus. Vivamus tristique
            ligula quis ultricies fermentum. Aenean id ultrices diam.
          </p>
        </div>
      </div>

      <dialog id="my_modal_2" class="modal">
        <div class="modal-box bg-gray-200 rounded-md p-0 h-16">
          <input
            type="text"
            class="bg-transparent w-full outline-none px-2 py-1"
            placeholder="Search..."
          />
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
import itembar from "./components/sidebaritem.vue";


import {
  Box16Filled,
  Search28Filled,
  WeatherCloudy24Filled,
  BookNumber16Filled,
  CalendarWorkWeek16Filled,
  AppsList20Filled,
  BinFull20Regular,
} from "@vicons/fluent";
import { useMagicKeys } from "@vueuse/core";
//ctrl + k onpen search modal

const { ctrl, y } = useMagicKeys();
watchEffect(() => {
  if (ctrl.value && y.value) my_modal_2.showModal();
});
</script>
