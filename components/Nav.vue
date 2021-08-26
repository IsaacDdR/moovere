<template>
  <div class="px-4 py-5 w-full fixed shadow">
    <div class="relative flex items-center justify-between">
      <a
        href="/"
        aria-label="Company"
        title="Company"
        class="inline-flex items-center"
      >
        <nuxt-img sizes="sm:50vw md:15vw" src="movere-title.png" />
      </a>
      <ul class="flex items-center hidden space-x-8 lg:flex">
        <li>
          <a
            href="/"
            aria-label="Our product"
            title="Our product"
            class="
              font-medium
              tracking-wide
              text-gray-700
              transition-colors
              duration-200
              hover:text-deep-purple-accent-400
            "
            >Product</a
          >
        </li>
        <li>
          <a
            href="/"
            aria-label="Our product"
            title="Our product"
            class="
              font-medium
              tracking-wide
              text-gray-700
              transition-colors
              duration-200
              hover:text-deep-purple-accent-400
            "
            >Features</a
          >
        </li>
        <li>
          <a
            href="/"
            aria-label="Product pricing"
            title="Product pricing"
            class="
              font-medium
              tracking-wide
              text-gray-700
              transition-colors
              duration-200
              hover:text-deep-purple-accent-400
            "
            >Pricing</a
          >
        </li>
        <li>
          <a
            href="/"
            aria-label="About us"
            title="About us"
            class="
              font-medium
              tracking-wide
              text-gray-700
              transition-colors
              duration-200
              hover:text-deep-purple-accent-400
            "
            >About us</a
          >
        </li>
      </ul>
      <ul class="flex items-center hidden space-x-8 lg:flex">
        <li>
          <a href="tel:5628348062">
            <font-awesome-icon
              class="text-2xl mx-5 text-mint"
              :icon="['fas', 'phone']"
            />
          </a>
          <a href="tel:5628348062">
            <font-awesome-icon
              class="text-3xl mx-5 text-mint"
              :icon="['fab', 'whatsapp']"
            />
          </a>
        </li>
      </ul>
      <div class="lg:hidden">
        <a href="tel:5628348062">
          <font-awesome-icon
            class="text-2xl mx-5 text-mint"
            :icon="['fas', 'phone']"
          />
        </a>
        <a href="tel:5628348062">
          <font-awesome-icon
            class="text-3xl mx-5 text-mint"
            :icon="['fab', 'whatsapp']"
          />
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      isMenuOpen: false,
    }
  },
}
</script>
