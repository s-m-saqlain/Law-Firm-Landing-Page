<script setup></script>

<template>
  <div>
    <p class="text-[#6A7282] font-semibold uppercase text-center">
      What We Are Expert At
    </p>
    <p class="text-center text-4xl font-bold">Legal Practices Area</p>

    <div class="sm:grid grid-cols-3 gap-6 pt-14 lg:px-32 sm:px-[22px] px-5">
      <div class="practice-box" v-for="(item, index) in practices" :key="index">
        <div>
          <img :src="item.img" class="mx-auto w-96" />
          <p class="text-xl font-bold uppercase text-center py-4">
            {{ item.title }}
          </p>
          <p
            class="text-center text-sm font-semibold text-gray-600 leading-relaxed px-2"
          >
            {{ item.text }}
          </p>
          <p
            class="text-center text-[#A94445] uppercase py-4 hover:underline cursor-pointer"
          >
            Learn More →
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import Cooperative from "../assets/images/cooperative.png";
import RealState from "../assets/images/realstate.png";
import HealthCare from "../assets/images/healthcare.png";
import Insurance from "../assets/images/insurance.png";
import Construction from "../assets/images/construction.png";
import Ecommerce from "../assets/images/ecommerce.png";

const practices = [
  {
    img: Cooperative,
    title: "Corporate & Securities",
    text: "We can provide corporate governance, helping clients manage the responsibilities of running a corporation in financial field.",
  },
  {
    img: RealState,
    title: "Real Estate Law",
    text: "We can provide corporate governance, helping clients manage the responsibilities of running a corporation in financial field.",
  },
  {
    img: HealthCare,
    title: "Health Care Law",
    text: "We can provide corporate governance, helping clients manage the responsibilities of running a corporation in financial field.",
  },
  {
    img: Insurance,
    title: "Insurance Law",
    text: "We can provide corporate governance, helping clients manage the responsibilities of running a corporation in financial field.",
  },
  {
    img: Construction,
    title: "Construction & Engineering",
    text: "We can provide corporate governance, helping clients manage the responsibilities of running a corporation in financial field.",
  },
  {
    img: Ecommerce,
    title: "Ecommerce Law",
    text: "We can provide corporate governance, helping clients manage the responsibilities of running a corporation in financial field.",
  },
];
</script>

<style scoped>
@keyframes zoomInBox {
  from {
    transform: scale(1);
  }
  to {
    transform: scale(1.05);
  }
}

.practice-box {
  transition: transform 0.4s ease;
}

.practice-box:hover {
  animation: zoomInBox 0.4s forwards;
  cursor: pointer;
  background-color: #fafafa;
  border-radius: 10px;
  box-shadow: 0 10px 20px rgba(169, 68, 69, 0.2);
}

.practice-box {
  cursor: pointer;
  background-color: #fafafa;
  border-radius: 10px;
  box-shadow: 0 10px 20px rgba(169, 68, 69, 0.2);
}
</style>
