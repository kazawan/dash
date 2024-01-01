<template>
  <div class="w-full h-full grid grid-cols-12 transition-all">
    <div
      class="w-full h-full col-span-2 bg-gray-900 font-bold border-gray-100/30 border-r-2 pt-2 select-none cursor-pointer"
    >
      <div class="flex flex-col border-gray-100/30 border-b-2 pb-2">
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
      class="relative w-full h-full bg-gray-800 col-span-10 flex flex-col justify-center items-center overflow-y-scroll"
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
        <div class="w-4/6 min-h-4/6 h-fit bg-gray-800 tracking-widest ">
          <p>
            恰恰与流行观念相反，Lorem
            Ipsum并不是简简单单的随机文本。它追溯于一篇公元前45年的经典拉丁著作，从而使它有着两千多年的岁数。弗吉尼亚州Hampden-Sydney大学拉丁系教授Richard
            McClintock曾在Lorem
            Ipsum段落中注意到一个涵义十分隐晦的拉丁词语，“consectetur”，通过这个单词详细查阅跟其有关的经典文学著作原文，McClintock教授发掘了这个不容置疑的出处。Lorem
            Ipsum始于西塞罗(Cicero)在公元前45年作的“de Finibus Bonorum et
            Malorum”（善恶之尽）里1.10.32
            和1.10.33章节。这本书是一本关于道德理论的论述，曾在文艺复兴时期非常流行。Lorem
            Ipsum的第一行”Lorem ipsum dolor sit amet..”节选于1.10.32章节。
            以下展示了自1500世纪以来使用的标准Lorem Ipsum段落，西塞罗笔下“de
            Finibus Bonorum et Malorum”章节1.10.32 ，
            1.10.33的原著作，以及其1914年译自H. Rackham的英文版本。
          </p>
          <p>
            恰恰与流行观念相反，Lorem
            Ipsum并不是简简单单的随机文本。它追溯于一篇公元前45年的经典拉丁著作，从而使它有着两千多年的岁数。弗吉尼亚州Hampden-Sydney大学拉丁系教授Richard
            McClintock曾在Lorem
            Ipsum段落中注意到一个涵义十分隐晦的拉丁词语，“consectetur”，通过这个单词详细查阅跟其有关的经典文学著作原文，McClintock教授发掘了这个不容置疑的出处。Lorem
            Ipsum始于西塞罗(Cicero)在公元前45年作的“de Finibus Bonorum et
            Malorum”（善恶之尽）里1.10.32
            和1.10.33章节。这本书是一本关于道德理论的论述，曾在文艺复兴时期非常流行。Lorem
            Ipsum的第一行”Lorem ipsum dolor sit amet..”节选于1.10.32章节。
            以下展示了自1500世纪以来使用的标准Lorem Ipsum段落，西塞罗笔下“de
            Finibus Bonorum et Malorum”章节1.10.32 ，
            1.10.33的原著作，以及其1914年译自H. Rackham的英文版本。
          </p>
          <p>
            恰恰与流行观念相反，Lorem
            Ipsum并不是简简单单的随机文本。它追溯于一篇公元前45年的经典拉丁著作，从而使它有着两千多年的岁数。弗吉尼亚州Hampden-Sydney大学拉丁系教授Richard
            McClintock曾在Lorem
            Ipsum段落中注意到一个涵义十分隐晦的拉丁词语，“consectetur”，通过这个单词详细查阅跟其有关的经典文学著作原文，McClintock教授发掘了这个不容置疑的出处。Lorem
            Ipsum始于西塞罗(Cicero)在公元前45年作的“de Finibus Bonorum et
            Malorum”（善恶之尽）里1.10.32
            和1.10.33章节。这本书是一本关于道德理论的论述，曾在文艺复兴时期非常流行。Lorem
            Ipsum的第一行”Lorem ipsum dolor sit amet..”节选于1.10.32章节。
            以下展示了自1500世纪以来使用的标准Lorem Ipsum段落，西塞罗笔下“de
            Finibus Bonorum et Malorum”章节1.10.32 ，
            1.10.33的原著作，以及其1914年译自H. Rackham的英文版本。
          </p>
          <p>
            恰恰与流行观念相反，Lorem
            Ipsum并不是简简单单的随机文本。它追溯于一篇公元前45年的经典拉丁著作，从而使它有着两千多年的岁数。弗吉尼亚州Hampden-Sydney大学拉丁系教授Richard
            McClintock曾在Lorem
            Ipsum段落中注意到一个涵义十分隐晦的拉丁词语，“consectetur”，通过这个单词详细查阅跟其有关的经典文学著作原文，McClintock教授发掘了这个不容置疑的出处。Lorem
            Ipsum始于西塞罗(Cicero)在公元前45年作的“de Finibus Bonorum et
            Malorum”（善恶之尽）里1.10.32
            和1.10.33章节。这本书是一本关于道德理论的论述，曾在文艺复兴时期非常流行。Lorem
            Ipsum的第一行”Lorem ipsum dolor sit amet..”节选于1.10.32章节。
            以下展示了自1500世纪以来使用的标准Lorem Ipsum段落，西塞罗笔下“de
            Finibus Bonorum et Malorum”章节1.10.32 ，
            1.10.33的原著作，以及其1914年译自H. Rackham的英文版本。
          </p>
          <p>
            恰恰与流行观念相反，Lorem
            Ipsum并不是简简单单的随机文本。它追溯于一篇公元前45年的经典拉丁著作，从而使它有着两千多年的岁数。弗吉尼亚州Hampden-Sydney大学拉丁系教授Richard
            McClintock曾在Lorem
            Ipsum段落中注意到一个涵义十分隐晦的拉丁词语，“consectetur”，通过这个单词详细查阅跟其有关的经典文学著作原文，McClintock教授发掘了这个不容置疑的出处。Lorem
            Ipsum始于西塞罗(Cicero)在公元前45年作的“de Finibus Bonorum et
            Malorum”（善恶之尽）里1.10.32
            和1.10.33章节。这本书是一本关于道德理论的论述，曾在文艺复兴时期非常流行。Lorem
            Ipsum的第一行”Lorem ipsum dolor sit amet..”节选于1.10.32章节。
            以下展示了自1500世纪以来使用的标准Lorem Ipsum段落，西塞罗笔下“de
            Finibus Bonorum et Malorum”章节1.10.32 ，
            1.10.33的原著作，以及其1914年译自H. Rackham的英文版本。
          </p>
          <p>
            恰恰与流行观念相反，Lorem
            Ipsum并不是简简单单的随机文本。它追溯于一篇公元前45年的经典拉丁著作，从而使它有着两千多年的岁数。弗吉尼亚州Hampden-Sydney大学拉丁系教授Richard
            McClintock曾在Lorem
            Ipsum段落中注意到一个涵义十分隐晦的拉丁词语，“consectetur”，通过这个单词详细查阅跟其有关的经典文学著作原文，McClintock教授发掘了这个不容置疑的出处。Lorem
            Ipsum始于西塞罗(Cicero)在公元前45年作的“de Finibus Bonorum et
            Malorum”（善恶之尽）里1.10.32
            和1.10.33章节。这本书是一本关于道德理论的论述，曾在文艺复兴时期非常流行。Lorem
            Ipsum的第一行”Lorem ipsum dolor sit amet..”节选于1.10.32章节。
            以下展示了自1500世纪以来使用的标准Lorem Ipsum段落，西塞罗笔下“de
            Finibus Bonorum et Malorum”章节1.10.32 ，
            1.10.33的原著作，以及其1914年译自H. Rackham的英文版本。
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
