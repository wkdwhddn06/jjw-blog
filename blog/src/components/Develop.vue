<template>
    <span>
        <h1 id="develop">DEVELOP</h1>
        <p>
        지금까지 <span class="accent">개발</span>기록 (아직 초보지만)
        </p>

        <div class="develop-container">
            <div class="develop-item big">
                길라잡이<p class="light">당신만의 길잡이입니다<br>2018 정보올림피아드 은상</p>
            </div>
            <div class="develop-item big">
                디미청원<p class="light">디미고인들을 위한 신문고<br>안드로이드 앱 개발을 맡았습니다.</p>
            </div>
            <div class="develop-item big">
                AIM<p class="light">숨은 보석들의 갤러리<br>개발 중 입니다.</p>
            </div>
        </div> 
    </span>
</template>

<style scoped>

#develop {
  margin-top: 700px;
}

.develop-container {
    margin: 10%;
    margin-top: 5%;
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: space-between;
}

.develop-item {
    width: 480px;
    height: 400px;
    margin-bottom: 40px;
    font-size: 36px;
}

.develop-item:hover{
    color: #E81A50;
}

</style>
