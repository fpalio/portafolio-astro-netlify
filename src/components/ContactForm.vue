<script setup>
import { ref } from 'vue';

const name = ref('');
const email = ref('');
const message = ref('');
</script>

<template>
    <form name="Contact-Portafolio"
    action="https://formspree.io/f/xeqwapgo"
    method="POST"
    class="bg-[#081710] p-6 rounded-lg">
    <input type="hidden" name="form-name" value="Contact-Portafolio" />
        <div class="mb-4">
          <label class="block text-[#3BA576] font-medium mb-2" for="name">
            Name
          </label>
          <input
            name="name"
            class="w-full border text-[#3BA576] bg-[#081710] p-2 rounded-lg"
            id="name"
            type="text"
            v-model="name"
          />
        </div>
        <div class="mb-4">
          <label class="block text-[#3BA576] font-medium mb-2" for="email">
            Email
          </label>
          <input
            name="email"
            class="w-full border text-[#3BA576] bg-[#081710] p-2 rounded-lg"
            id="email"
            type="email"
            v-model="email"
          />
        </div>
        <div class="mb-4">
          <label class="block text-[#3BA576] font-medium mb-2" for="message">
            Message
          </label>
          <textarea
            name="Message"
            class="w-full border text-[#3BA576] bg-[#081710] p-2 rounded-lg"
            id="message"
            rows="5"
            v-model="message"
          ></textarea>
        </div>
        <div class="flex items-center justify-between">
          <button
            type="submit"
            class="border-2 border-[#3BA576] text-[#3BA576] py-2 px-4 rounded-lg hover:bg-[#3BA576] hover:text-black"
          >
            Submit
          </button>
        </div>
      </form>
</template>
