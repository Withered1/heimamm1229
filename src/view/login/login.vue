<template>
  <div class="login">
      <div class="left"></div>
      <div class="right">
          <img src="@/assets/img/login_banner_ele.png" alt="">
      </div>
  </div>
</template>

<script>
export default {
name:"login"
}
</script>

<style lang="less">
.login {
  /* 弹性盒子布局 */
  display: flex;
  /* 水平布局 */
  justify-content: space-around;
  /* 垂直居中 */
  align-items: center;
  height: 100%;
  background: linear-gradient(
    225deg,
    rgba(20, 147, 250, 1),
    rgba(1, 198, 250, 1)
  );
  .left {
    width: 478px;
    height: 550px;
    padding: 42px;
    background-color: #f5f5f5;
    .title {
      display: flex;
      align-items: center;
      .titleName {
        font-size: 24px;
        font-weight: 400;
        color: rgba(12, 12, 12, 1);
        margin: 0 15px;
      }
      .titleName2 {
        font-size: 22px;
        font-weight: 400;
        color: rgba(12, 12, 12, 1);
        margin: 0 15px;
      }
    }
    // 表单布局
    .form {
      padding-top: 30px;
      .code {
        width: 100%;
        height: 40px;
        padding-top: 3px;
        border: 1px dashed #ccc;
      }
      .color1 {
        color: #3296fa;
      }
      .btn {
        width: 100%;
      }
      .btn:last-child {
        margin-top: 26px;
      }
    }
  }
}
</style>