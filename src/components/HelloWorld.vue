<template>
  <div class="hello">
    <div>
      <div class="row">
        <div class="column">
          <h2>About me</h2>
          <h3
            class="me"
          >I am like art and design, I have experience of being a photographer and made a website which selling an image, I am interested to work in frontend developer. No matter what happens, I am always willing to take responsibility.</h3>
          <h3 class="imgline"></h3>
        </div>
      </div>
      <div class="row1">
        <div class="columnp" >
          
          <h2>Design skill</h2>
          <ul>
            <li>
              <img src="../assets/fm.png" alt="f" />
            </li>
            <li>
              <img src="../assets/ph.png" alt="f" />
            </li>
            <li>
              <img src="../assets/ai.png" alt="f" />
            </li>
            <li>
              <img src="../assets/dv.png" alt="f" />
            </li>
            <li>
              <img src="../assets/pc.png" alt="f" />
            </li>
          </ul>
        </div>
      </div>
      <div class="row1">
        <div class="columnp">
          <h2>Programming skill</h2>
          <ul>
            <li>
              <img class="im2" src="../assets/ht.png" alt="f" />
            </li>
            <li>
              <img class="im3" src="../assets/css.jpg" alt="f" />
            </li>
            <li>
              <img class="im4" src="../assets/js.png" alt="f" />
            </li>
            <li>
              <img class="im4" src="../assets/re.png" alt="f" />
            </li>
            <li>
              <img class="im5" src="../assets/node.png" alt="f" />
            </li>
            <li>
              <img class="im5" src="../assets/my.png" alt="f" />
            </li>
          </ul>
        </div>
      </div>
    </div>
    <h3>Contact</h3>
    <ul>
      <li class='space'>
        <a href="https://www.facebook.com/Chutinun25Tim" target="_blank" rel="noopener">Facebook</a>
      </li>
      <li class='space'>
        <a href="https://github.com/chutinunbelltan25" target="_blank" rel="noopener">Github</a>
      </li>
      <li class='space'>
        <a
          href="https://gitlab.com/fResult/CC4-MAID-PRO/tree/develop/frontend-maid-pro/src/pages"
          target="_blank"
          rel="noopener"
        >Gitlab</a>
      </li>
      <li class='space'>
        <a
          href="https://www.instagram.com/belltintin/?hl=th"
          target="_blank"
          rel="noopener"
        >Instagram</a>
      </li>
    </ul>
    <ul>
      <li>
        <img src="../assets/face.png" alt="f" />
      </li>
      <li></li>
      <li>
        <img src="../assets/GitHub.png" alt="f" />
      </li>
      <li>
        <img src="../assets/gitlab.png" alt="f" />
      </li>
      <li>
        <img src="../assets/ig.png" alt="f" />
      </li>
    </ul>
    <h1 class="lineG"></h1>
    <div>
      <h2 id="Gall">Gallery photo</h2>
      <ul>
      <li>
        <img class="imgG" src="../assets/1.jpg" alt="f" />
      </li>
      <li></li>
      <li>
        <img class="imgG" src="../assets/2.jpg" alt="f" />
      </li>
      <li>
        <img class="imgG" src="../assets/3.jpg" alt="f" />
      </li>
      <li>
        <img class="imgG" src="../assets/4.jpg" alt="f" />
      </li>
    </ul>
    <ul>
      <li>
        <img class="imgG" src="../assets/5.jpg" alt="f" />
      </li>
      <li></li>
      <li>
        <img class="imgG" src="../assets/6.jpg" alt="f" />
      </li>
      <li>
        <img class="imgG" src="../assets/7.jpg" alt="f" />
      </li>
      <li>
        <img class="imgG" src="../assets/8.jpg" alt="f" />
      </li>
    </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
  
};
</script>

<style scoped>
.imgG {
  width: 40vh;
  height: 25vh;
}

.lineG {
  margin: 10vh;
  background-color: black;
  width: 100%;
  height: 0.25vh;
}
.changeBackground {
  background-color: black
}

.imgline {
  width: 100vh;
  border-bottom: 3px solid black;
}
.im2 {
  width: 120px;
}
.im3 {
  width: 130px;
}
.im4 {
  width: 80px;
}
.im5 {
  width: 150px;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
.space {
  margin-right: 50px;
  margin-left: 50px
}
img {
  width: 100px;
  height: 100px;
  margin: 15px;
}
.column {
  width: 50%;
  padding: 0%;
  height: 200px;
  margin: 10px;
}
.columnp {
  width: 100%;
  padding: 3%;
  height: 200px;
  margin: 10px;
}
.form-message {
  margin-right: 50px
}
h4 {
  display: flex;
  justify-content: flex-start;
  margin-left: 36%;
}
.me {
  display: flex;
  justify-content: flex-start;
  margin-left: 20%;
  margin-right: 20%;
}
.row {
  display: flex;
  justify-content: center;
}
.row1 {
  display: flex;
  justify-content: flex-end;
  margin: 50px;
}
</style>
