<template>
  <section class="relative text-gray-700 body-font">
    <div class="container flex flex-wrap px-5 py-24 mx-auto sm:flex-no-wrap">
      <div
        class="relative flex items-end justify-start p-10 overflow-hidden bg-gray-300 rounded-lg lg:w-2/3 md:w-1/2 sm:mr-10"
      >
        <iframe
          class="absolute inset-0"
          style="filter: grayscale(1) contrast(1.2) opacity(0.4);"
          title="map"
          marginheight="0"
          marginwidth="0"
          scrolling="no"
          src="https://maps.google.com/maps?width=100%&amp;height=600&amp;hl=en&amp;q=%C4%B0zmir+(My%20Business%20Name)&amp;ie=UTF8&amp;t=&amp;z=14&amp;iwloc=B&amp;output=embed"
          width="100%"
          height="100%"
          frameborder="0"
        ></iframe>
        <div class="relative flex flex-wrap py-6 bg-white">
          <div class="px-6 lg:w-1/2">
            <h2
              class="text-sm font-medium tracking-widest text-gray-900 title-font"
            >
              ADDRESS
            </h2>
            <p class="leading-relaxed">
              PO Box 327 Ventura Ca 93002
            </p>
          </div>
          <div class="px-6 mt-4 lg:w-1/2 lg:mt-0">
            <h2
              class="text-sm font-medium tracking-widest text-gray-900 title-font"
            >
              EMAIL
            </h2>
            <a class="leading-relaxed text-indigo-500">ed@niceweb.page</a>
            <h2
              class="mt-4 text-sm font-medium tracking-widest text-gray-900 title-font"
            >
              PHONE
            </h2>
            <p class="leading-relaxed">805-861-6375</p>
          </div>
        </div>
      </div>
      <div
        class="flex flex-col w-full mt-8 bg-white lg:w-1/3 md:w-1/2 md:ml-auto md:py-8 md:mt-0"
      >
        <h2 class="mb-1 text-lg font-medium text-gray-900 title-font">
          Feedback
        </h2>
        <p class="mb-5 leading-relaxed text-gray-600">
          Get ahold of me using this form below and I will get right back with
          you.
        </p>
        <form
          name="contact"
          action="/thank-you"
          netlify-honeypot="bot-field"
          method="post"
          netlify
        >
          <input type="hidden" name="form-name" value="contact" />
          <p class="hidden">
            <label>Don’t fill this out: <input name="bot-field"/></label>
            <input type="hidden" name="form-name" value="contact" />
          </p>

          <p class="hidden">
            <label>Don’t fill this out: <input name="bot-field"/></label>
          </p>
          <input
            class="px-4 py-2 mb-4 text-base bg-white border border-gray-400 rounded focus:outline-none focus:border-indigo-500"
            placeholder="Name"
            type="text"
          />
          <input
            class="px-4 py-2 mb-4 text-base bg-white border border-gray-400 rounded focus:outline-none focus:border-indigo-500"
            placeholder="Email"
            type="email"
          />
          <textarea
            class="h-32 px-4 py-2 mb-4 text-base bg-white border border-gray-400 rounded resize-none focus:outline-none focus:border-indigo-500"
            placeholder="Message"
          ></textarea>
          <button
            class="px-6 py-2 text-lg text-white bg-indigo-500 border-0 rounded focus:outline-none hover:bg-indigo-600"
          >
            Button
          </button>
        </form>
        <p class="mt-3 text-xs text-gray-500">
          Chicharrones blog helvetica normcore iceland tousled brook viral
          artisan.
        </p>
      </div>
    </div>
  </section>
</template>
<style scoped>
.hidden {
  display: none;
}
</style>
