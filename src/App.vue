<template>
  <div id="app">
    <div class="navbar-left">
        <img src="" alt="" />
    </div>
    <div class="navbar">
        <label >Home</label>
        <a href="#Gall"><label >Gallery</label></a>
        <label >User</label>
        <label >login</label>
    </div>

    <div class="BGimg">
      <h1 class="surname">Chutinun Tantasathiar</h1>
    </div>
    <HelloWorld msg />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "app",
  components: {
    HelloWorld
  },
};
</script>

<style>
.navbar {
  background-color: #2c3e50;
  width: 100%;
  height: 8vh;
  margin-bottom: 5vh;
  display: flex;
  justify-content: flex-end;
}
.navbar-left {
  width: 100%;
  display: flex;
  justify-content: flex-end;
}
.form-input {
  margin-right: 10px;
  margin-left: 10px
}
.inform {
  width: 3px;
}
.BGimg {
  background: url("https://scontent.fbkk8-3.fna.fbcdn.net/v/t1.0-9/p720x720/72097764_3280812101959910_682445688876826624_o.jpg?_nc_cat=111&_nc_ohc=_-_jYEDpodIAX-NYLnc&_nc_ht=scontent.fbkk8-3.fna&_nc_tp=6&oh=214b659dcdb3b5b5aec0b3de547f8b8b&oe=5ECCCB85");
  display: flex;
  justify-content: center;
  object-fit: cover;
  padding: 10%;
  width: 800px;
  height: 450px;
  padding: 0%;
}
button {
  background-color: aquamarine;
  font-size: 16px;
  border: none;
}
@media only screen and (max-width: 1024) {
  .BGimg {
    width: 100%;
    height: 100%;
  }
}
@media only screen and (min-width: 1025px) {
  .BGimg {
    margin-left: 28%;
  }
}
.surname {
  margin-top: 20%;
  color: black;
  text-shadow: -4px 2px 3px #afafaf;
  font-size: 50px;
}
label {
  display: flex;
  justify-content: flex-end;
  padding: 3vh;
  margin-right: 1vh;
  color: whitesmoke;
  font-size: 20px;
}
.front {
  display: flex;
  justify-content: center;
  text-align: center;
}
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;

}
</style>
