<script setup lang="ts">
// Aquí podrías agregar lógica para manejar el envío del formulario si lo necesitas
</script>

<template>
  <section class="mt-4 mb-4">
    <div class="max-w-7xl mx-auto px-4">
      <div class="mb-10 text-center">
        <h2 class="text-3xl font-bold text-gray-800">Contact Us</h2>
        <p class="text-gray-600 mt-2">Estamos aquí para ayudarte con cualquier duda sobre la biblioteca.</p>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
        <div class="bg-white p-6 rounded-xl shadow-sm border border-gray-200">
          <h3 class="text-xl font-semibold text-gray-800 mb-6">Get in Touch</h3>
          
          <div class="space-y-4">
            <div class="flex items-start">
              <div class="flex-shrink-0 bg-blue-100 p-3 rounded-lg text-blue-600">
                <i class="fas fa-envelope"></i>
              </div>
              <div class="ml-4">
                <p class="text-sm font-medium text-gray-900">Email</p>
                <p class="text-sm text-gray-600">support@library.com</p>
              </div>
            </div>

            <div class="flex items-start">
              <div class="flex-shrink-0 bg-green-100 p-3 rounded-lg text-green-600">
                <i class="fas fa-phone"></i>
              </div>
              <div class="ml-4">
                <p class="text-sm font-medium text-gray-900">Phone</p>
                <p class="text-sm text-gray-600">+1 (555) 000-0000</p>
              </div>
            </div>
          </div>
        </div>

        <div class="bg-white p-6 rounded-xl shadow-sm border border-gray-200">
          <form class="space-y-4">
            <div>
              <label class="block text-sm font-medium text-gray-700">Name</label>
              <input type="text" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-blue-500 focus:ring-blue-500 bg-gray-50 border p-2" placeholder="Your Name">
            </div>
            <div>
              <label class="block text-sm font-medium text-gray-700">Message</label>
              <textarea rows="4" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-blue-500 focus:ring-blue-500 bg-gray-50 border p-2" placeholder="How can we help?"></textarea>
            </div>
            <button type="submit" class="w-full bg-blue-600 text-white py-2 px-4 rounded-md hover:bg-blue-700 transition duration-200 font-medium">
              Send Message
            </button>
          </form>
        </div>
      </div>
    </div>
  </section>
</template>