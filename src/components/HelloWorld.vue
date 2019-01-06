<template>
  <div class="hello">
    <h1>Book name: {{ msg }}</h1>
  </div>
</template>

<script>

import { VeryDeepBook } from '../models/VeryDeepBook'

export default {
  data () {
    return {
      msg: new VeryDeepBook().getName()
    }
  }
}
</script>
