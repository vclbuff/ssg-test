<template>
  <div>
    カウンター {{ counter }}
    <button @click="inc">
      プラス
    </button>
  </div>
</template>

<script>
export default {
  data () {
    return {
      counter: 0
    }
  },
  methods: {
    inc () {
      this.counter = this.counter + 1
    }
  }
}
</script>
