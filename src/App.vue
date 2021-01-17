<template>
  <div id="app">
    <el-row>
      <el-carousel type="card" height="25vh" class="center-component">
        <el-carousel-item>
          <div style="position:absolute; left:50%; top:50%; transform: translate(-50%,-50%);">
            <a href="https://wiki.mayidance.cn">
              <h2> Dance Wiki </h2>
            </a>
          </div>
        </el-carousel-item>
        <el-carousel-item>
          <div style="position:absolute; left:50%; top:50%; transform: translate(-50%,-50%);">
            <a href="https://media.mayidance.cn">
              <h2> Media Cloud </h2>
            </a>
          </div>
        </el-carousel-item>
        <el-carousel-item>
          <div style="position:absolute; left:50%; top:50%; transform: translate(-50%,-50%);">
            <h2> 🚧 Ticket in May </h2>
          </div>
        </el-carousel-item>
      </el-carousel>
    </el-row>
    <el-row class="footer">
      💃 ©2021 mayidance.cn <br/>
      京 ICP 备 2021001415 号
    </el-row>
  </div>
</template>

<script>

export default {
  name: 'App',
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.center-component {
  position: fixed;
  top: 55%;
  left: 50%;
  width: 80%;
  height: 50%;
  -webkit-transform: translateX(-50%) translateY(-50%);
}

.el-carousel__item {
  background: #6699ff;
  opacity: 0.5;
  -webkit-transition: ease 500ms;
  -moz-transition: ease 500ms;
  -ms-transition: ease 500ms;
  -o-transition: ease 500ms;
  transition: ease 500ms;
  border-radius: 1vh;
}

.el-carousel__item.is-active {
  opacity: 0.95;
}

.el-card {
  margin: 0 auto;
  width: 100%;
  height: 100%;
}

.el-card__body {
  height: 100%;
}

.footer {
  position: fixed;
  top: 112%;
  left: 50%;
  width: 80%;
  height: 50%;
  -webkit-transform: translateX(-50%) translateY(-50%);
}
</style>
