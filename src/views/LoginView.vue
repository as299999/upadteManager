<template>
  <div class="page">
    <div class="form">
      <div class="title">登录</div>
      <div class="row">
        <div class="label">用户名:</div>
        <div class="input"><input placeholder="请输入用户名" /></div>
      </div>
      <div class="row">
        <div class="label">密码:</div>
        <div class="input"><input placeholder="请输入密码" type="password" /></div>
      </div>
      <div class="btn">登录</div>
    </div>
  </div>
</template>

<style scoped lang="less">
  .page {
    background: rgba(0, 238, 255, 0.5);
    height: 100vh;
    overflow: hidden;
    .form {
      width: 500px;
      margin: 250px auto 0;
      background: #fff;
      border-radius: 20px;
      padding: 20px 30px;
      box-sizing: border-box;
      .title { 
        font-size: 30px;
        font-weight: bold;
        text-align: center;
      }
      .row {
        display: flex;
        align-items: center;
        margin-top: 20px;
        height: 30px;
        .label {
          width: 80px;
        }
        .input {
          flex: 1;
          input {
            width: 100%;
            border: none;
            outline: none;
            border-bottom: 1px solid #000;
          }
        }
      }
      .btn {
        margin-top: 20px;
        color: #fff;
        height: 40px;
        line-height: 40px;
        text-align: center;
        border-radius: 5px;
        background: rgba(0, 238, 255, 1);
        cursor: pointer;
      }
    }
  }
</style>
