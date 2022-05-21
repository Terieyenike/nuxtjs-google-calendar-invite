<template>
  <div>

    <p class="text-2xl">QR code with calendar invite</p>
    <qrcode :options="{
      color: {
        dark: '#FFC72C',
        light: '#DA291C',
      },
      width: 300
    }" value="https://calendar.google.com/event?action=TEMPLATE&tmeid=X2Nscjc4YmJoZXNyNWtsM2pjcDlqOGkyY2NwMTRpcGEwY2xyNmFyamtlY242b3Q5ZWRsZ2cgdGV5ZW5pa2UxQG0&tmsrc=teyenike1%40gmail.com
"></qrcode>
  </div>
</template>

<script>
import VueQrcode from "@chenfengyuan/vue-qrcode";

export default {
  components: {
    qrcode: VueQrcode,
  },
}
</script>
