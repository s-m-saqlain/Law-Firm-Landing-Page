<template>
  <div>
    <div
      class="mt-12 relative py-32 bg-cover bg-center bg-no-repeat bg-[url('../assets/images/reviews.png')]"
    >
      <h1 class="text-3xl text-white font-bold text-center">
        Reviews From Our Clients
      </h1>
      <p class="text-center font-semibold text-white px-[350px] pt-4">
        Far far away, behind the word mountains, far from the countries Vokalia
        and Consonantia, there live the blind texts. Separated they live in
        Bookmarks grove right at the coast of the Semantics, a large language
        ocean. A small river named.
      </p>

      <div class="flex justify-center items-center gap-32 pt-8">
        <div>
          <h1 class="text-4xl text-white text-center font-bold">885+</h1>
          <p class="text-white font-bold">Client Consultations</p>
        </div>
        <div>
          <h1 class="text-4xl text-white text-center font-bold">85%</h1>
          <p class="text-white font-bold">Successful Cases</p>
        </div>
        <div>
          <h1 class="text-4xl text-white text-center font-bold">9mlns</h1>
          <p class="text-white font-bold">Recovered Cost for Clients</p>
        </div>
        <div>
          <h1 class="text-4xl text-white text-center font-bold">27+</h1>
          <p class="text-white font-bold">Recovered Cost for Clients</p>
        </div>
      </div>

      <div
        class="absolute left-1/2 -bottom-[390px] transform -translate-x-1/2 z-10 bg-white w-[480px] rounded-lg shadow-lg"
      >
        <h1 class="text-xl font-bold text-center pt-4">Free Consultation</h1>
        <p class="text-sm text-gray-700 text-center font-semibold px-10 py-4">
          Law is a complicated matter. It can cause you big problems if you
          ignore it. Let us help you!
        </p>

        <div class="flex justify-center items-center gap-8">
          <input
            name="text"
            placeholder="Name"
            class="px-2 py-1.5 border rounded-[6px]"
          />
          <input
            name="text"
            placeholder="Phone"
            class="px-2 py-1.5 border rounded-[6px]"
          />
        </div>

        <input
          name="text"
          placeholder="Cooperation Law"
          class="my-4 w-[430px] mx-6 px-2 py-1.5 border rounded-[6px]"
        />
        <input
          name="email"
          placeholder="Email"
          class="w-[430px] mx-6 px-2 py-1.5 border rounded-[6px]"
        />
        <textarea
          id="w3review"
          name="w3review"
          rows="4"
          class="border w-[430px] mx-6 my-4 px-2 rounded-[6px]"
          placeholder="Message"
        ></textarea>

        <div class="flex justify-center mb-6">
          <button
            class="py-2 w-[430px] bg-[#A36B31] text-[#FFFFE7] font-semibold rounded-[4px]"
          >
            SUBMIT NOW
          </button>
        </div>
      </div>
    </div>

    <div
      class="h-screen bg-cover bg-center bg-no-repeat bg-[url('../assets/images/form.png')]"
    ></div>
  </div>
</template>
