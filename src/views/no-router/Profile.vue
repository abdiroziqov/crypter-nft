<template>
  <div class="relative">
    <Navbar />

    <div class="relative mb-32">
      <img
        class="min-h-[300px] md:min-h-[232px] w-full"
        src="@/assets/image/profile-back.png"
        alt=""
      />
      <div class="flex gap-4 absolute bottom-[50%] ml:bottom-[12%] right-[7%]">
        <div
          class="hover:border-[#3772FF] duration-300 cursor-pointer items-center flex gap-3 py-3 px-4 border-2 border-solid border-[#777E91] rounded-[90px]"
        >
          <p class="font-bold text-sm text-[#FCFCFD]">Edit cover photo</p>
          <i
            ><svg
              width="16"
              height="16"
              viewBox="0 0 16 16"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M7.9987 2.66683C6.69721 2.66683 5.49747 2.77417 4.5345 2.90135C3.66785 3.01581 3.01434 3.66931 2.89988 4.53597C2.7727 5.49894 2.66536 6.69867 2.66536 8.00016C2.66536 9.30165 2.7727 10.5014 2.89988 11.4644C3.01434 12.331 3.66785 12.9845 4.5345 13.099C5.49747 13.2262 6.69721 13.3335 7.9987 13.3335C9.30019 13.3335 10.4999 13.2262 11.4629 13.099C12.3295 12.9845 12.9831 12.331 13.0975 11.4644C13.2247 10.5014 13.332 9.30165 13.332 8.00016C13.332 6.69867 13.2247 5.49894 13.0975 4.53597C12.9831 3.66931 12.3295 3.01581 11.4629 2.90135C10.4999 2.77417 9.30019 2.66683 7.9987 2.66683ZM4.35992 1.57949C2.89539 1.77291 1.77145 2.89686 1.57803 4.36139C1.44505 5.36822 1.33203 6.62768 1.33203 8.00016C1.33203 9.37265 1.44505 10.6321 1.57803 11.6389C1.77145 13.1035 2.89539 14.2274 4.35992 14.4208C5.36675 14.5538 6.62621 14.6668 7.9987 14.6668C9.37118 14.6668 10.6306 14.5538 11.6375 14.4208C13.102 14.2274 14.2259 13.1035 14.4194 11.6389C14.5523 10.6321 14.6654 9.37265 14.6654 8.00016C14.6654 6.62768 14.5523 5.36822 14.4194 4.36139C14.2259 2.89686 13.102 1.77291 11.6375 1.57949C10.6306 1.44652 9.37118 1.3335 7.9987 1.3335C6.62621 1.3335 5.36675 1.44652 4.35992 1.57949Z"
                fill="#FCFCFD"
              />
              <path
                d="M6.00041 7.33317C6.73679 7.33317 7.33374 6.73622 7.33374 5.99984C7.33374 5.26346 6.73679 4.6665 6.00041 4.6665C5.26403 4.6665 4.66707 5.26346 4.66707 5.99984C4.66707 6.73622 5.26403 7.33317 6.00041 7.33317Z"
                fill="#FCFCFD"
              />
              <path
                d="M12.0813 8.47137L13.2775 9.66758C13.2362 10.2917 13.176 10.8709 13.1095 11.3852L11.1385 9.41418C10.8781 9.15382 10.456 9.15383 10.1957 9.41417L8.74795 10.8619C7.9669 11.6429 6.70057 11.6429 5.91952 10.8619L5.80514 10.7475C5.54479 10.4872 5.12268 10.4872 4.86233 10.7475L3.25629 12.3536C3.07024 12.1013 2.94576 11.7985 2.90158 11.464C2.87749 11.2816 2.8541 11.0907 2.83203 10.8922L3.91953 9.8047C4.70057 9.02365 5.9669 9.02365 6.74795 9.8047L6.86233 9.91908C7.12268 10.1794 7.54479 10.1794 7.80514 9.91908L9.25286 8.47136C10.0339 7.69032 11.3002 7.69032 12.0813 8.47137Z"
                fill="#FCFCFD"
              /></svg
          ></i>
        </div>
        <router-link
          to="/edit-profile"
          class="hover:border-[#3772FF] duration-300 cursor-pointer items-center flex gap-3 py-3 px-4 border-2 border-solid border-[#777E91] rounded-[90px]"
        >
          <button class="font-bold text-sm text-[#FCFCFD]">Edit profile</button>
          <i
            ><svg
              width="16"
              height="16"
              viewBox="0 0 16 16"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M2 14.6667C2 14.2985 2.29848 14 2.66667 14H13.3333C13.7015 14 14 14.2985 14 14.6667C14 15.0349 13.7015 15.3333 13.3333 15.3333H2.66667C2.29848 15.3333 2 15.0349 2 14.6667Z"
                fill="#FCFCFD"
              />
              <path
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M11.1381 2.08084C10.8777 1.82049 10.4556 1.82049 10.1953 2.08084L9.6095 2.66661L12 5.05713L12.5858 4.47137C12.8461 4.21102 12.8461 3.78891 12.5858 3.52856L11.1381 2.08084ZM4.6095 7.66661L8.66669 3.60942L11.0572 5.99994L7.00002 10.0571L4.6095 7.66661ZM3.66669 8.60942L3.33333 8.94277V11.3333H5.72386L6.05721 10.9999L3.66669 8.60942ZM9.25245 1.13803C10.0335 0.356984 11.2998 0.356984 12.0809 1.13803L13.5286 2.58575C14.3096 3.3668 14.3096 4.63313 13.5286 5.41418L6.66667 12.2761C6.41662 12.5262 6.07748 12.6666 5.72386 12.6666H3.33333C2.59695 12.6666 2 12.0697 2 11.3333V8.94277C2 8.58915 2.14048 8.25001 2.39052 7.99996L9.25245 1.13803Z"
                fill="#FCFCFD"
              /></svg
          ></i>
        </router-link>
      </div>
    </div>
    <div class="container md:flex gap-16 relative">
      <Profil />
      <Profiltab />
    </div>
    <div class="loader flex justify-center my-20">
      <img src="@/assets/icon/load-more.png" alt="" />
    </div>
    <Footer />
  </div>
</template>

<script setup>
import Navbar from "@/components/NavbarTwo";
import Profil from "@/components/Profil";
import Footer from "@/components/Footer";
import Profiltab from "@/components/No-router/ProfileTab";
</script>

<style>
.loader:hover img {
  animation: loader 1.5s linear infinite;
}
@keyframes loader {
  from {
    transform: rotate(0deg);
  }
  to {
    transform: rotate(360deg);
  }
}
</style>
