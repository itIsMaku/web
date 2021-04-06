<template>
  <div
    class="bg-radical w-full h-full min-h-screen min-w-screen flex justify-center items-center"
  >
    <div class="max-w-2xl w-full mx-4">
      <div class="flex flex-col">
        <img
          src="https://cdn.discordapp.com/avatars/543845318962184223/b5822f2d14fc738a5cb497ce54d4beef.png"
          class="w-24 h-24 rounded-3xl"
          data-aos="fade-up"
          data-aos-delay="300"
        />
        <div class="my-8">
          <h1
            class="text-radical-title font-bold text-4xl sm:text-5xl md:text-7xl xl:8xl 2xl:9xl"
            data-aos="fade-up"
            data-aos-delay="400"
          >
            Maku
          </h1>
          <div
            class="text-gray-100 font-medium text-xl sm:text-2xl md:text-4xl xl:5xl 2xl:6xl inline-flex items-center"
            data-aos="fade-up"
            data-aos-delay="500"
          >
            <transition
              enter-active-class="transition ease-out duration-300 transform"
              enter-from-class="opacity-0 scale-95"
              enter-to-class="opacity-100 scale-100"
              leave-active-class="transition ease-in duration-75 transform"
              leave-from-class="opacity-100 scale-100"
              leave-to-class="opacity-0 scale-95"
              mode="out-in"
            >
              <component :is="state.text" />
            </transition>
          </div>
        </div>
        <div
          class="flex text-gray-100 text-2xl items-center"
          data-aos="fade-up"
          data-aos-delay="600"
        >
          <icon-link href="https://github.com/itIsMaku">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="w-10 h-10 xl:h-12 xl:w-12"
              viewBox="0 0 24 24"
              fill="none"
              stroke="currentColor"
              stroke-width="1.5"
              stroke-linecap="round"
              stroke-linejoin="round"
            >
              <path
                d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"
              />
            </svg>
          </icon-link>
          <icon-link href="#">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="w-10 h-10 xl:h-12 xl:w-12"
              viewBox="0 0 24 24"
              fill="none"
              stroke="currentColor"
              stroke-width="1.5"
              stroke-linecap="round"
              stroke-linejoin="round"
            >
              <path
                d="M23 3a10.9 10.9 0 0 1-3.14 1.53 4.48 4.48 0 0 0-7.86 3v1A10.66 10.66 0 0 1 3 4s-4 9 5 13a11.64 11.64 0 0 1-7 2c9 5 20 0 20-11.5a4.5 4.5 0 0 0-.08-.83A7.72 7.72 0 0 0 23 3z"
              />
            </svg>
          </icon-link>
          <icon-link href="#">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="w-10 h-10 xl:h-12 xl:w-12"
              viewBox="0 0 24 24"
              fill="none"
              stroke="currentColor"
              stroke-width="1.5"
              stroke-linecap="round"
              stroke-linejoin="round"
            >
              <rect x="2" y="2" width="20" height="20" rx="5" ry="5" />
              <path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z" />
              <line x1="17.5" y1="6.5" x2="17.51" y2="6.5" />
            </svg>
          </icon-link>
          <icon-link href="#">
            <svg
              aria-hidden="true"
              class="h-10 w-10 xl:h-12 xl:w-12"
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 448 512"
            >
              <path
                fill="currentColor"
                d="M297.216 243.2c0 15.616-11.52 28.416-26.112 28.416-14.336 0-26.112-12.8-26.112-28.416s11.52-28.416 26.112-28.416c14.592 0 26.112 12.8 26.112 28.416zm-119.552-28.416c-14.592 0-26.112 12.8-26.112 28.416s11.776 28.416 26.112 28.416c14.592 0 26.112-12.8 26.112-28.416.256-15.616-11.52-28.416-26.112-28.416zM448 52.736V512c-64.494-56.994-43.868-38.128-118.784-107.776l13.568 47.36H52.48C23.552 451.584 0 428.032 0 398.848V52.736C0 23.552 23.552 0 52.48 0h343.04C424.448 0 448 23.552 448 52.736zm-72.96 242.688c0-82.432-36.864-149.248-36.864-149.248-36.864-27.648-71.936-26.88-71.936-26.88l-3.584 4.096c43.52 13.312 63.744 32.512 63.744 32.512-60.811-33.329-132.244-33.335-191.232-7.424-9.472 4.352-15.104 7.424-15.104 7.424s21.248-20.224 67.328-33.536l-2.56-3.072s-35.072-.768-71.936 26.88c0 0-36.864 66.816-36.864 149.248 0 0 21.504 37.12 78.08 38.912 0 0 9.472-11.52 17.152-21.248-32.512-9.728-44.8-30.208-44.8-30.208 3.766 2.636 9.976 6.053 10.496 6.4 43.21 24.198 104.588 32.126 159.744 8.96 8.96-3.328 18.944-8.192 29.44-15.104 0 0-12.8 20.992-46.336 30.464 7.68 9.728 16.896 20.736 16.896 20.736 56.576-1.792 78.336-38.912 78.336-38.912z"
              />
            </svg>
          </icon-link>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent, h, onMounted, reactive, VNode } from "vue";
import IconLink from "./components/IconLink.vue";
import AOS from "aos";

import "aos/dist/aos.css";

const component = (node: VNode) => ({ setup: () => () => node });

const texts = {
  JavaDeveloper: component(h("span", "Java Developer")),
  CoffeeLover: component(h("span", "☕ Coffee Lover")),
  QPlay: component(h("span", "Developer at QPlay.cz")),
  TypeScript: component(h("span", "Future TypeScript king")),
};

export default defineComponent({
  name: "Root",
  components: { ...texts, IconLink },
  setup() {
    const keys = Object.keys(texts);

    const state = reactive({
      key: 0,
      text: keys[0],
    });

    const key = (): number => {
      const itm = state.key + 1;
      if (itm > keys.length - 1) return 0;
      return itm;
    };

    const changeStateKey = () => {
      state.key = key();
      state.text = keys[state.key];
    };

    onMounted(() => setInterval(() => changeStateKey(), 3000));

    AOS.init({
      easing: "ease-in-out",
      duration: 500,
    });

    return {
      state,
    };
  },
});
</script>
