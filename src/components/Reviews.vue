<template>
  <div>
    <div
      class="py-32 bg-cover bg-center bg-no-repeat bg-[url('../assets/images/reviews.png')]"
    >
      <h1 class="text-3xl text-[#FFFFFF] font-bold text-center">
        Reviews From Our Clients
      </h1>
      <p class="text-center font-semibold text-[#FFFFFF] px-[350px] pt-4">
        Far far away, behind the word mountains, far from the countries Vokalia
        and Consonantia, there live the blind texts. Separated they live in
        Bookmarks grove right at the coast of the Semantics, a large language
        ocean. A small river named.
      </p>
      <div class="flex justify-center items-center gap-32 pt-8">
        <div>
          <h1 class="text-4xl text-[#FFFFFF] text-center font-bold">885+</h1>
          <p class="text-[#FFFFFF] font-bold">Client Consultations</p>
        </div>
        <div>
          <h1 class="text-4xl text-[#FFFFFF] text-center font-bold">85%</h1>
          <p class="text-[#FFFFFF] font-bold">Successful Cases</p>
        </div>
        <div>
          <h1 class="text-4xl text-[#FFFFFF] text-center font-bold">9mlns</h1>
          <p class="text-[#FFFFFF] font-bold">Recovered Cost for Clients</p>
        </div>
        <div>
          <h1 class="text-4xl text-[#FFFFFF] text-center font-bold">27+</h1>
          <p class="text-[#FFFFFF] font-bold">Recovered Cost for Clients</p>
        </div>
      </div>
    </div>

    <div
      class="bg-cover bg-center bg-no-repeat bg-[url('../assets/images/form.png')] pt-10"
    >
      <div class="bg-[#FFFFFF] w-[480px] mx-auto rounded-lg">
        <h1 class="text-xl font-bold text-center pt-8">Free Consultation</h1>
        <p class="text-sm text-gray-700 text-center font-semibold px-10 py-4">
          Law is complicate matter. It can cause you a big problem if you ignore
          it. Let us help you!
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
          cols="50"
          class="border w-[430px] mx-6 my-4 px-2 rounded-[6px]"
          placeholder="Message"
        ></textarea>
        <div class="flex justify-center">
          <button
            class="py-2 w-[430px] bg-[#A36B31] text-[#FFFFE7] font-semibold rounded-[4px]"
          >
            SUBMIT NOW
          </button>
        </div>
      </div>
    </div>
  </div>
</template>
