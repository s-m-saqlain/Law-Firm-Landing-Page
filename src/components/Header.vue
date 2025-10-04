<template>
  <div class="w-full text-white">
    <section class="relative">
      <div class="bg-[#111315] border-b border-white/10">
        <div class="mx-auto max-w-6xl px-4 py-3">
          <div class="sm:flex sm:h-10 items-center justify-between text-sm">
            <div class="flex items-center gap-6">
              <div class="flex items-center gap-2">
                <Mobile />
                <span>+234-345-678</span>
              </div>
              <div class="flex items-center gap-2">
                <Email />
                <span>info@email.com</span>
              </div>
              <div class="sm:block hidden">Mon - Fri: 08:00 - 17:00</div>
            </div>
            <div class="sm:hidden text-center sm:py-0 py-2">Mon - Fri: 08:00 - 17:00</div>
            <div class="flex items-center gap-2">
              <button class="bg-[#A36B31] text-white rounded-full p-2">
                <Facebook />
              </button>
              <button class="bg-[#A36B31] text-white rounded-full p-2">
                <LinkedIn />
              </button>
              <button
                class="bg-[#A36B31] text-white font-semibold py-2 px-4 rounded-[10px]"
              >
                FREE CONSULTANT
              </button>
            </div>
          </div>
        </div>
      </div>

      <header
        class="relative bg-[#0E0F12]/80 backdrop-blur supports-[backdrop-filter]:bg-[#0E0F12]/60 sticky top-0 z-30"
      >
        <div class="mx-auto max-w-6xl px-4">
          <div class="flex h-16 items-center justify-between">
            <a href="#" class="flex items-center gap-3">
              <span
                class="inline-flex h-9 w-9 items-center justify-center rounded-full bg-[#D08A3A] text-black font-bold"
                >FI</span
              >
              <div class="leading-tight">
                <div class="font-semibold tracking-wide">Firm Inc</div>
                <div class="text-xs text-white/70">Enterprise</div>
              </div>
            </a>
            <nav class="hidden md:flex items-center gap-8">
              <a
                class="text-sm text-white/80 hover:text-white transition"
                href="#"
                >Home</a
              >
              <a
                class="text-sm text-white/80 hover:text-white transition"
                href="#"
                >Pages</a
              >
              <a
                class="text-sm text-white/80 hover:text-white transition"
                href="#"
                >Attorney</a
              >
              <a
                class="text-sm text-white/80 hover:text-white transition"
                href="#"
                >Practice Area</a
              >
              <a
                class="text-sm text-white/80 hover:text-white transition"
                href="#"
                >Case Study</a
              >
              <a
                class="text-sm text-white/80 hover:text-white transition"
                href="#"
                >Blog</a
              >
              <a
                class="text-sm text-white/80 hover:text-white transition"
                href="#"
                >Contact</a
              >
            </nav>

            <button
              class="md:hidden inline-flex h-9 w-9 items-center justify-center rounded-md border border-white/10 text-white"
              @click="mobileOpen = !mobileOpen"
              aria-label="Toggle menu"
            >
              <svg
                v-if="!mobileOpen"
                class="h-5 w-5"
                viewBox="0 0 24 24"
                fill="none"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="1.5"
                  d="M3 6h18M3 12h18M3 18h18"
                />
              </svg>
              <svg
                v-else
                class="h-5 w-5"
                viewBox="0 0 24 24"
                fill="none"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="1.5"
                  d="M6 18L18 6M6 6l12 12"
                />
              </svg>
            </button>
          </div>
        </div>

        <div
          v-if="mobileOpen"
          class="md:hidden border-t border-white/10 bg-[#0E0F12]"
        >
          <nav class="mx-auto max-w-6xl px-4 py-4 flex flex-col gap-3">
            <a class="text-sm text-white/90" href="#">Home</a>
            <a class="text-sm text-white/90" href="#">Pages</a>
            <a class="text-sm text-white/90" href="#">Attorney</a>
            <a class="text-sm text-white/90" href="#">Practice Area</a>
            <a class="text-sm text-white/90" href="#">Case Study</a>
            <a class="text-sm text-white/90" href="#">Blog</a>
            <a class="text-sm text-white/90" href="#">Contact</a>
          </nav>
        </div>
      </header>
      <div
        class="relative h-[520px] w-full bg-cover bg-center"
        :style="{
          backgroundImage: `url('https://hebbkx1anhila5yf.public.blob.vercel-storage.com/Capture1.PNG-GXFAWpDsq1P5Tui5NpCGbz76Vwx6d7.png')`,
        }"
        role="img"
        aria-label="Modern office buildings background"
      >
        <div class="absolute inset-0 bg-black/60"></div>
        <div
          class="absolute inset-0 bg-gradient-to-b from-black/20 via-black/40 to-black/70"
        ></div>

        <div
          class="relative z-10 mx-auto flex h-full max-w-6xl items-center px-4"
        >
          <div class="mx-auto">
            <p
              class="mb-3 text-2xl text-center uppercase tracking-[0.2em] text-[#D08A3A]"
            >
              WELCOME TO
            </p>
            <h1
              class="text-balance text-center text-4xl font-bold sm:text-5xl leading-tight"
            >
              FIRM INC
              <span class="block text-center text-white/90">ENTERPRISE</span>
            </h1>
            <p class="mt-4 text-white text-center">
              We are a leading law firm in financial & business industry. With
              more than
            </p>
            <p class="text-white text-center">than 20 years of experience.</p>
            <div class="mt-6 flex justify-center items-center gap-3 mb-44">
              <a
                href="#"
                class="inline-flex items-center justify-center rounded-md bg-[#D08A3A] text-white px-5 py-2.5 text-sm font-semibold hover:bg-[#bb7d35] transition"
              >
                Contact Now
              </a>
            </div>
          </div>
        </div>
        <div class="pointer-events-none absolute inset-x-0 -bottom-24 z-20">
          <div class="mx-auto max-w-6xl px-4">
            <div
              class="pointer-events-auto grid gap-6 md:grid-cols-[1.2fr,1fr]"
            >
              <div class="rounded-lg bg-[#D08A3A] p-6 text-black shadow-xl">
                <div class="flex items-start justify-between gap-4">
                  <h3 id="about" class="text-2xl font-bold text-white">
                    About Firm Inc
                  </h3>
                </div>
                <p class="mt-3 text-white font-semibold">
                  We can provide corporate governance, helping clients manage
                  the responsibilities of running a corporation in financial
                  issues. Our corporate lawyers are experienced in all business
                  structures.
                </p>
                <div class="mt-4 flex items-center gap-6">
                  <div class="text-left">
                    <div class="text-[2rem] text-white font-signature">
                      Paul Smith
                    </div>
                    <div class="font-semibold text-white">
                      CEO & Founder of Firm Inc
                    </div>
                  </div>
                </div>
              </div>
              <div
                class="overflow-hidden rounded-lg border border-white/10 bg-white/5 backdrop-blur"
              >
                <img
                  src="https://images.unsplash.com/photo-1555371363-7dfc2f7c6b35?q=80&w=1400&auto=format&fit=crop"
                  alt="Justicfe statue and law books"
                  class="h-full w-full object-cover"
                />
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="h-32"></div>
    </section>
  </div>
</template>

<script setup>
import { ref } from "vue";
import Mobile from "../assets/svgs/mobile.vue";
import Email from "../assets/svgs/email.vue";
import Facebook from "../assets/svgs/facebook.vue";
import LinkedIn from "../assets/svgs/linkedin.vue";

const mobileOpen = ref(false);
</script>

<style scoped>
.font-signature {
  font-family: ui-script, "Segoe Script", "Bradley Hand", "Comic Sans MS",
    cursive;
  letter-spacing: 0.5px;
}
</style>
