<template>
  <div class="di">bb</div>
</template>
<script>
import Slider from 'base/slider/slider'
import { getRecommend, getDiscList } from 'api/recommend'
import { ERR_OK } from 'api/config'

export default {

  methods: {
    _getRecommend() {
      getRecommend().then((res) => {
        if (res.code === ERR_OK) {
          console.log(res.data.slider)
        }
      })
    }
  },
  created() {
    this._getRecommend()
  },
}

</script>
<style scoped lang="less">
</style>
