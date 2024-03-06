<template>
  <div>
   <div>
    <NounsBlockie :input="userAddress" />
  </div>
  </div>
</template>

<script>
import Vue from 'vue';

import { NounsBlockie } from 'vue-nouns-blockie';
console.log("Vue ", Vue)
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