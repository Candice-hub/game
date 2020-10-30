<template>
  <div>
    <div class="picOne" style="margin-bottom:40px">
      <img src="../assets/加一游官网素材/官网图片1.png" class="bgImg" />
    </div>

    <div class="picTwo" style="margin-bottom:40px">
      <img src="../assets/加一游官网素材/官网图片2.png" class="bgImg" />
    </div>

    <div class="picThree" style="margin-bottom:40px">
      <img src="../assets/加一游官网素材/官网图片3.png" class="bgImg" />
    </div>

    <div class="picFour" style="margin-bottom:40px">
      <img src="../assets/加一游官网素材/官网图片4.png" class="bgImg" />
    </div>

    <div class="picFive" style="margin-bottom:40px">
      <img src="../assets/加一游官网素材/官网图片5.png" class="bgImg" />
    </div>

    <div class="picSix">
      <img src="../assets/加一游官网素材/官网图片6.png" class="bgImg" />
    </div>

    <div class="d-flex justify-center align-center" style="color:#fff;height:45px">
      <div class="d-flex">
        <!-- <div
          class="mr-3"
          style="cursor:pointer"
          @click="go(1)"
        >
          粤公网安备
        </div> -->
        <div
          style="cursor:pointer"
          @click="go(2)"
        >
          粤ICP备20058821号
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    go (state) {
      if (state === 1) {
        window.open('http://www.beian.gov.cn/portal/registerSystemInfo?recordcode=44011102002666')
      } else if (state === 2) {
        window.open('http://beian.miit.gov.cn/')
      }
    }
  }
}
</script>

<style scoped>
.bgImg {
  width: 100%;
}
</style>