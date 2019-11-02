<template>
  <div class="nav">
    <div class="main-nav">
      <div class="logo-wrap">
        <img src="../assets/logo.png" class="logo" alt>
      </div>

      <div class="user-wraps">
        <input type="text">
        <div class="badges">
          <div class="badge">12</div>
          <div class="badge">12</div>
        </div>
        <span class="username">Jon Doe</span>
        <div class="user-photo">
          <img src="https://randomuser.me/api/portraits/men/61.jpg" alt>
        </div>
      </div>
    </div>
    <div class="sub-nav">
      <ul>
        <li>uyvuviuviu</li>
        <li>viuviuviu</li>
        <li>viuviuvi</li>
        <li>viuviuv</li>
        <li>iuviuviu</li>
        <li>viuviuv</li>
        <li>iuviuvi</li>
      </ul>
    </div>
  </div>
</template>
<script>
export default {
    
}
</script>
<style lang="scss" scoped>
.nav {
  .main-nav {
    height: 60px;
    background-color: #d71b11;
    color: #fff;
    position: relative;
    .logo-wrap {
      background-color: #fff;
      width: 150px;
      height: 100%;
      padding-right: 60px;
      border-radius: 0 50px 50px 0;
      position: absolute;
      left: 0;
      display: inline-block;
      .logo {
        float: right;
        height: 70%;
        vertical-align: middle;
      }
    }
    .user-wraps {
      display: block;
      position: absolute;
      right: 50px;
      height: 60px;
      line-height: 60px;
      background-color: #d71b11;
      input {
        width: 250px;
        height: 40px;
        border-radius: 50px;
        border: 0;
        background-color: #fad9c5;
      }
      .badges {
        width: 70px;
        height: 40px;
        padding: 0 12px 0 20px;
        display: inline-block;
        .badge {
          background-color: #272727;
          color: #fff;
          font-size: 10px;
          display: inline;
          margin: -20px 12px 0 0;
          border-radius: 50%;
          padding: 2px;
        }
      }
      .user-photo {
        width: 40px;
        height: 40px;
        border-radius: 50%;
        margin: 0 0 0 12px;
        display: inline-block;
        overflow: hidden;
        vertical-align: middle;
        img {
          width: 100%;
        }
      }
    }
  }
  .sub-nav {
    background-color: #cd4216;
    height: 60px;
    color: #fff;
    padding-left: 50px;
    ul {
      padding: 0;
      list-style: none;
      float: left;
      li {
        display: inline;
        color: #fff;
        margin: 0 15px;
      }
    }
  }
}
</style>
