<template>
  <div>
    <div class="flex flex-col h-screen items-center">
      <div class="flex mt-12 text-xl h-1/4">
        <h1>Sitio en construcción</h1>
      </div>
      <MoovereLogo />
      <div class="flex">
        <div class="mx-auto">
          <font-awesome-icon
            class="m-5 text-mint text-4xl"
            :icon="['fas', 'phone']"
          />
          <font-awesome-icon
            class="m-5 text-mint text-4xl"
            :icon="['fab', 'whatsapp']"
          />
          <font-awesome-icon
            class="m-5 text-mint text-4xl"
            :icon="['fas', 'map-marked-alt']"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>
