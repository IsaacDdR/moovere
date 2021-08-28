<template>
  <div>
    <div class="flex flex-col h-screen items-center">
      <div class="flex mt-12 text-xl h-1/4">
        <h1>Sitio en construcción</h1>
      </div>
      <MoovereLogo />
      <div class="flex">
        <div class="mx-auto">
          <a href="tel:8127439088">
            <font-awesome-icon
              class="m-5 text-mint text-4xl"
              :icon="['fas', 'phone']"
            />
          </a>
          <a
            href="https://api.whatsapp.com/send?phone=528134421227&text=Me%20gustar%C3%ADa%20saber%20m%C3%A1s%20de%20Moovere"
          >
            <font-awesome-icon
              class="m-5 text-mint text-4xl"
              :icon="['fab', 'whatsapp']"
          /></a>
          <a href="https://goo.gl/maps/hWHtrHtzrXgypbSm7">
            <font-awesome-icon
              class="m-5 text-mint text-4xl"
              :icon="['fas', 'map-marked-alt']"
            />
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>
