<template>
  <div class="max-w-3xl py-12 mx-auto">
   <h1>This is ne5 Portal</h1>
  </div>
</template>

<script>
import { Dialog } from 'frappe-ui'

export default {
  name: 'Home',
  data() {
    return {
      showDialog: false,
    }
  },
  resources: {
    ping: {
      url: 'ping',
    },
  },
  components: {
    Dialog,
  },
}
</script>
