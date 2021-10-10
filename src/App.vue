<template>
  <div class="container mx-auto my-auto py-52">
    <div class="flex flex-wrap w-2/5 mx-auto">
      <div class="flex-1 z-20">
        <div
          class="
            flex flex-col
            bg-primary
            pt-10
            shadow-2xl
            transform
            translate-x-6
            -translate-y-6
          "
        >
          <div
            class="
              text-4xl text-white
              mx-auto
              font-sans font-medium
              tracking-wide
              mb-6
            "
          >
            Receipt
          </div>
          <div
            class="
              text-sm text-white
              mx-auto
              font-sans font-medium
              tracking-wide
              pb-12
            "
          >
            Order Summary
          </div>
          <div class="flex flex-col">
            <img src="./assets/1.png" />
          </div>
        </div>
      </div>
      <div class="flex-1 z-10">
        <div class="flex flex-col bg-white pt-10 shadow-xl">
          <div class="flex mx-auto my-4 w-1/2">
            <div class="flex-auto"><img src="./assets/Vector.png" /></div>
            <div class="flex-auto my-auto">
              <p class="text-right font-sans text-gray-500">28-07-2019</p>
            </div>
          </div>
          <div class="flex mx-auto my-4 w-1/2">
            <p class="text-left font-sans text-gray-500 my-auto"> Wagamama </p>
            <p class="flex-auto text-right font-sans text-gray-500">$34</p>
          </div>
          <div class="flex mx-auto my-4 w-1/2">
            <p class="text-left font-sans text-gray-500 my-auto"> Pizza O Italia </p>
            <p class="flex-auto text-right font-sans text-gray-500">$50</p>
          </div>
          <div class="flex mx-auto my-4 w-1/2">
            <p class="text-left font-sans text-gray-500 my-auto"> Delivery Fee </p>
            <p class="flex-auto text-right font-sans text-gray-500">$6</p>
          </div>
          
          <div class="h-36">
          </div>
          <div class="z-10 flex mx-auto my-4 w-1/2">
            <p class="text-left font-sans text-gray-500 my-auto"> Total </p>
            <p class="flex-auto text-4xl text-gray-600 text-right font-sans">$90</p>
          </div>
          <div class="z-10 flex mx-auto my-1 w-1/2">
            <p class="text-left font-sans text-gray-400 my-auto"> Customer Support </p>
            <p class="flex-auto text-2xl text-gray-400 text-right font-sans">></p>
          </div>
          <div class="z-10 flex mx-auto my-1 w-1/2">
            <p class="text-left font-sans text-gray-400 my-auto"> Track your food </p>
            <p class="flex-auto text-2xl text-gray-400 text-right font-sans">></p>
          </div>
          
          <div class="z-0 flex bg-blend-normal transform translate-y-2 mx-auto"
          >
            <img src="./assets/Rectangle.png"/>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>
