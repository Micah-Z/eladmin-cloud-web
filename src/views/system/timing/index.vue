<template>
  <elFrame :src="jobApi" />
</template>
<script>
import { mapGetters } from 'vuex'
import elFrame from '@/components/Iframe/index'
export default {
  name: 'Timing',
  components: { elFrame },
  computed: {
    ...mapGetters([
      'jobApi'
    ])
  }
}
</script>
