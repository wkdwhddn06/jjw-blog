<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      <span class="accent">Vue</span> 기본 레이아웃을 변형해서 만들어보고 있어요
    </p>

    <div class="profile-contanier">
      <div class="profile-img"><img src="../assets/logo.png"/></div>
      <div class="profile-card">
        <div class="profile-content">
          장 종 우<br>
          <span class="light">South Korea<br>한국디지털미디어고등학교<br>아이유를 좋아합니다!</span>
          <div class="profile-content-footer light">
            <i class="fab fa-github"></i><a href="https://github.com/wkdwhddn06">github.com/wkdwhddn06</a><br>
            <i class="fab fa-facebook"></i><a href="https://www.facebook.com/jang1006">www.facebook.com/jang1006</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'Profile',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello {
  font-family: 'Noto Sans KR', sans-serif;
}

.profile-card {
  background: #fff;
  border-radius: 2px;
  position: absolute; 
  display: inline-block;
  height: 500px;
  width: 350px;
  box-shadow: 0 19px 38px rgba(0,0,0,0.30), 0 15px 12px rgba(0,0,0,0.22);

  z-index: 1;
  top: 300px;
  left: 0;
  margin-left: auto;
  margin-right: auto;
  left: 0;
  right: 0;
}

.profile-img {
  position: absolute;
  z-index: 2;
  left: 0;
  margin-top: 40px;
  margin-left: auto;
  margin-right: auto;
  left: 0;
  right: 0;
}

.profile-container {
  position: relative;
  margin: 100px auto 0;
  width: 350px;
  height: 700px;
  float: left;
}

.profile-content {
  color: #595959;
  font-size: 24px;
  font-weight: 900;
  margin-top: 90px;
}

.profile-content-footer {
  margin-top: 160px;
  margin-left: 18px;
  text-align: left;
}

i {
  padding-left: 12px;
  padding-right: 12px;
  color: #adadad;
}

img {
  width: 120px;
  height: auto;
  border-radius: 50%;
}

h1 {
  font-weight: 700;
  font-size: 4em;
  margin-top: 30px;
}

p {
  padding: 0px;
  margin: 10px;
}

a {
  color: #adadad;
  font-weight: 500;
  text-decoration: none;
}

a:visited {
  color: #adadad;
  text-decoration: none;
}

a:hover {
  color: #E81A50;
  text-decoration: none;
}
</style>
