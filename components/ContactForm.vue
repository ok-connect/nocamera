<template>
  <div id="contact-us" class="py-24 px-5">
    <div class="max-w-4xl mx-auto">
      <h1 class="text-5xl font-bold text-gray-800">Have Questions?</h1>
      <h2 class="text-4xl font-bold text-blue-500 mt-3">We have answers</h2>
      <div class="mt-7">
        <form
          name="contact-us"
          method="post"
          data-netlify="true"
          data-netlify-honeypot="bot-field"
        >
          <input type="hidden" name="form-name" value="contact-us" />
          <div class="space-y-6">
            <div>
              <label>Name</label>
              <input
                type="text"
                name="name"
                required
                class="shadow-sm focus:ring-indigo-500 focus:border-indigo-500 mt-1 block w-full sm:text-sm border-gray-300 rounded-md"
              />
            </div>
            <div>
              <label>Email</label>
              <input
                type="email"
                name="email"
                required
                class="shadow-sm focus:ring-indigo-500 focus:border-indigo-500 mt-1 block w-full sm:text-sm border-gray-300 rounded-md"
              />
            </div>
            <div>
              <label>How can we help?</label>
              <textarea
                name="message"
                required
                rows="10"
                class="shadow-sm focus:ring-indigo-500 focus:border-indigo-500 mt-1 block w-full sm:text-sm border-gray-300 rounded-md"
              ></textarea>
            </div>
            <div>
              <button
                type="submit"
                class="text-lg inline-flex justify-center py-2 px-7 border border-transparent shadow-sm font-medium rounded-md text-white bg-blue-600 hover:bg-blue-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-blue-500"
              >
                Send
              </button>
            </div>
          </div>
        </form>
      </div>
    </div>
  </div>
</template>
