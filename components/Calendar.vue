<template>
  <div class="container">
    <section class="row">
      <div class="row__left">
        <h1>Getting Started in Community</h1>
        <p>Scan the code to attend</p>
      </div>
      <qrcode
        :options="{
          color: {
            dark: '#75DBCD',
            light: '#2E282A',
          },
          width: 300,
        }"
        value="https://calendar.google.com/event?action=TEMPLATE&tmeid=MXBxOGg5NThwa2JocjBoZThwczc4dWpoam0gdGV5ZW5pa2UxQG0&tmsrc=teyenike1%40gmail.com"
      ></qrcode>
    </section>
    <footer>
      <address>Teri &copy; 2022 | Built with Nuxt.js</address>
    </footer>
  </div>
</template>

<script>
import VueQrcode from "@chenfengyuan/vue-qrcode";

export default {
  components: {
    qrcode: VueQrcode,
  },
};
</script>
