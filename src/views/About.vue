<template>
  <div class="about">
    <mt-header title="标题过长会隐藏后面的内容啊哈哈哈哈">
      <router-link to="/" slot="left">
        <mt-button icon="back">返回</mt-button>
      </router-link>
      <mt-button icon="more" slot="right"></mt-button>
    </mt-header>
    <div class="fontTest">
      字体测试
    </div>
  </div>
</template>

<style lang="less" scoped>
.fontTest {
  width: 10rem;
  height: 5rem;
  text-align: center;
  font-size: 0.2133rem;
}
</style>

