<template>
  <div>
   <div>
    <NounsBlockie :input="userAddress" />
  </div>
  </div>
</template>

<script>
import { NounsBlockie } from 'vue-nouns-blockie';

export default {
  components: {
    NounsBlockie
  },
  data() {
    return {
      userAddress: '0x...'
    };
  }
}
</script>