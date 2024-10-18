<template>
  <footer class="bg-gray-800 text-gray-300 py-8">
    <div class="container mx-auto px-4 sm:px-6 lg:px-8">
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <!-- Company Info -->
        <div>
          <h2 class="text-white text-lg font-semibold mb-4">Your Company</h2>
          <p class="text-sm">
            Providing the best services since 2024. We are committed to offering the highest quality solutions to meet your needs.
          </p>
        </div>

        <!-- Links Section -->
        <div>
          <h2 class="text-white text-lg font-semibold mb-4">Quick Links</h2>
          <ul class="space-y-2">
            <li><a href="#" class="hover:text-white text-sm">About Us</a></li>
            <li><a href="#" class="hover:text-white text-sm">Services</a></li>
            <li><a href="#" class="hover:text-white text-sm">Projects</a></li>
            <li><a href="#" class="hover:text-white text-sm">Contact</a></li>
          </ul>
        </div>

        <!-- Social Media -->
        <div>
          <h2 class="text-white text-lg font-semibold mb-4">Follow Us</h2>
          <ul class="flex space-x-4">
            <li><a href="#" class="hover:text-white"><i class="fab fa-facebook fa-lg"></i></a></li>
            <li><a href="#" class="hover:text-white"><i class="fab fa-twitter fa-lg"></i></a></li>
            <li><a href="#" class="hover:text-white"><i class="fab fa-linkedin fa-lg"></i></a></li>
            <li><a href="#" class="hover:text-white"><i class="fab fa-instagram fa-lg"></i></a></li>
          </ul>
        </div>
      </div>

      <div class="border-t border-gray-700 mt-8 pt-4 text-center text-sm text-gray-500">
        &copy; 2024 Your Company. All rights reserved.
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'AppFooter',
}
</script>
