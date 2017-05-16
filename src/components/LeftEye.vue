<template>
  <section v-bind:class="className"></section>
</template>

<script>
export default {
  data () {
    return {
        className: 'blink'
    }
  }
}
</script>

<style scoped>

  section {
    background-image: url(../assets/eyes/left/default.svg);
  }

  section.begging {
    background-image: url(../assets/eyes/left/begging.svg);
  }

  section.blink {
    background-image: url(../assets/eyes/left/blink.svg);
  }

  section.happy {
    background-image: url(../assets/eyes/left/happy.svg);
  }

  section.heart {
    background-image: url(../assets/eyes/left/heart.svg);
  }

  section.tired {
    background-image: url(../assets/eyes/left/tired.svg);
  }

</style>
