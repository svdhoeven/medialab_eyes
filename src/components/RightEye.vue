<template>
  <section v-bind:class="className"></section>
</template>

<script>
    export default {
        data () {
            return {
                className: 'nkjrjoq'
            }
        }
    }
</script>

<style scoped>
  section {
    background-image: url(../assets/eyes/right/default.svg);
    width: 50%;
    height: 100%;
    background-size: 500px 500px;
    background-position: center;
    background-repeat: no-repeat;
  }

  section.begging {
    background-image: url(../assets/eyes/right/begging.svg);
  }

  section.blink {
    background-image: url(../assets/eyes/right/blink.svg);
  }

  section.happy {
    background-image: url(../assets/eyes/right/happy.svg);
  }

  section.heart {
    background-image: url(../assets/eyes/right/heart.svg);
  }

  section.tired {
    background-image: url(../assets/eyes/right/tired.svg);
  }

</style>
