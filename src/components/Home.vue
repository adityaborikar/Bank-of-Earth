<script setup lang="ts">
import Header from "./Header.vue";
import Paragraph from "./Paragraph.vue";
</script>

<template>
  <!-- NAVBAR -->
  <div class="bg-indigo-800">
    <div class="container mx-auto px-36 max-w-container">
      <div class="navbar text-white bg-indigo-800 flex items-center justify-between">
        <div class="w-1/2 flex justify-start">
          <a class="btn btn-ghost normal-case text-xl">
            <img class="mr-2" width="50" src="../assets/mastercard.png" alt="" />
            <Header msg="Bank of Earth" />
          </a>
        </div>
        <div class="w-1/2 flex justify-end">
          <ul class="menu menu-horizontal p-0">
            <li><a>Home</a></li>
            <li><a>Services</a></li>
            <li><a>Contact</a></li>
            <li><a>About</a></li>
          </ul>
        </div>
      </div>
    </div>

    <div class="container mx-auto px-36 max-w-container">
      <div class="flex items-center justify-between h-[65vh] lg:h-[85vh]">
        <div class="w-1/2">
          <p class="text-[45px] font-bold mb-0 pb-0 text-white">
            The Britest bank card
          </p>
          <p class="text-[45px] font-bold pt-0 text-white">in your wallet</p>

          <p class="text-white">
            Our Card is the best option if your looking for high-quality and
            <br />
            reliable bankinng service. We provide reliable service to you.
          </p>
          <div class="mt-7">
            <button class="btn rounded-full bg-indigo-900">Book a card</button>
            <button class="btn rounded-full btn-outline text-white bg-indigo-800 ml-4">
              Read more
            </button>
          </div>
        </div>
        <div>
          <img width="500" src="../assets/creditCard.png" alt="" />
        </div>
      </div>
    </div>
  </div>

  <!-- CARDS -->
  <div class="container mx-auto px-36 max-w-container">
    <div class="flex z-10 mt-[-60px] justify-evenly gap-5">
      <!-- CARD 1 -->
      <div class="card w-1/3 bg-base-100 shadow-xl">
        <div class="card-body flex">
          <div class="flex">
            <div class="bg-slate-100 rounded-full w-20 h-20 mt-4 flex justify-evenly items-center">
              <img width="40" src="../assets/credit-card.png" />
            </div>
            <div class="card-title no-flex ml-10">
              <Header class="text-[15px] font-normal" msg="More than"></Header>
              <Header class="text-[50px] my-4" msg="32000"></Header>
              <Header class="text-[15px] font-normal" msg="Issued cards"></Header>
            </div>
          </div>
          <Paragraph
            paragraphMsg="If you are looking for high-quality and reliable banking service. Our Bank Card is the best option." />
        </div>
      </div>

      <!-- CARD 2 -->
      <div class="card w-1/3 bg-base-100 shadow-xl">
        <div class="card-body">
          <div class="flex">
            <div class="bg-slate-100 rounded-full w-20 h-20 mt-4 flex justify-evenly items-center">
              <img width="40" src="../assets/indian-rupee.png" />
            </div>
            <div class="card-title no-flex ml-10">
              <Header class="text-[15px] font-normal" msg="Upto" />
              <Header class="text-[50px] my-4" msg="25%" />
              <Header class="text-[15px] font-normal" msg="Cashback" />
            </div>
          </div>
          <Paragraph
            paragraphMsg="If you are looking for high-quality and reliable banking service. Our Bank Card is the best option." />
        </div>
      </div>

      <!-- CARD 3 -->
      <div class="card w-1/3 bg-base-100 shadow-xl">
        <div class="card-body">
          <div class="flex">
            <div class="bg-slate-100 rounded-full w-20 h-20 mt-4 flex justify-evenly items-center">
              <img width="40" src="../assets/money-graph-with-up-arrow.png" />
            </div>
            <div class="card-title no-flex ml-10">
              <Header class="text-[15px] font-normal" msg="Upto" />
              <Header class="text-[50px] font-bold my-4" msg="40%" />
              <Header class="text-[15px] font-normal" msg="Fixed Deposit" />
            </div>
          </div>
          <Paragraph
            paragraphMsg="If you are looking for high-quality and reliable banking service. Our Bank Card is the best option." />
        </div>
      </div>
    </div>
  </div>

  <!-- PARAGRAPH -->
  <div class="container mx-auto px-36 max-w-container">
    <div class="flex mt-20 mb-20">
      <div class="w-[60%]">
        <p class="font-bold text-[30px]">
          Our Bank founded in 2015 to introduce the new <br />level of financial
          service. We are still <br />dedicated to the success of our clients.
        </p>
        <p class="mt-10">
          Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nemo
          voluptate omnis a vitae sapiente iusto distinctio reprehenderit,
          molestias quam praesentium itaque at, id quidem, dolor ipsum delectus
          minus iure officia!
        </p>
        <button class="btn rounded-full bg-indigo-800 mt-10">Learn More</button>
      </div>
      <div>
        <img class="justify-center rounded-lg" width="500" src="../assets/laptop.avif" alt="" />
      </div>
    </div>
  </div>
</template>
