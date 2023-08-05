<script setup lang="ts">
import { OhVueIcon, addIcons } from "oh-vue-icons";
import { BiGrid3X3GapFill, MdArrowdropdownTwotone } from "oh-vue-icons/icons";

addIcons(BiGrid3X3GapFill, MdArrowdropdownTwotone);

</script>


<template>
  <div>
    <div class="flex justify-between items-center max-w-7xl m-auto h-16 bg-slate-100 px-3 text-gray-600">
      <div class="flex items-center">
        <div class="text-2xl font-bold text-blue-500 mr-4">Informaniak</div>
        <div class="flex w-96 justify-around  items-stretch font-bold">
          <div class="w-3/12">
            Product
          </div>
          <div class="w-3/12">A propos</div>
          <div class="w-3/12">Support</div>
        </div>
      </div>
      <div class="flex items-center gap-5 ">
        <div class="flex align-middle bg-slate-200 rounded-sm p-2 font-bold">
          <div>FR</div>
          <div>
            <OhVueIcon name="md-arrowdropdown-twotone"></OhVueIcon>
          </div>
        </div>
        <div class="gap-2 flex items-center text-xs">
          <div class="text-center rounded-2xl bg-blue-500 text-white w-16 ">HT</div>
          <div class="text-center ">TTC</div>
        </div>
        <OhVueIcon name="bi-grid-3x3-gap-fill" />
        <div class="flex gap-3 items-center font-bold">
          <div class="p-3 text-blue-500">Inscription</div>
          <div class="bg-blue-500 p-5 text-white">Connexion</div>
        </div>
      </div>
    </div>
  </div>
</template>
