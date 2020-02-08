<template>
  <div id="app">
    <name />
    <div class="BGimg">
      <h1 class="surname">Chutinun Tantasathiar</h1>
    </div>
    <HelloWorld msg="" employees/>
  </div>
</template>

<script>
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "app",
  components: {
    HelloWorld,

  },
  data() {
    return {
      employees: [
        {
          id: 1,
          name: 'Chutinun',
          last: 'Tantasathiar',
          message: 'your are the best'
        }
      ]
    }
  },
  methods: {
    addEmployee(employee) {
      const lastId =
      this.employees.length > 0 ? this.employees[this.employees.length-1].id : 0
      const id = lastId + 1;
      const newEmployee = {...employee, id}
      this.employees = [...this.employees, newEmployee]
      }
    }
};
</script>

<style>
.BGimg {
  background:url('https://scontent.fbkk8-3.fna.fbcdn.net/v/t1.0-9/p720x720/72097764_3280812101959910_682445688876826624_o.jpg?_nc_cat=111&_nc_ohc=_-_jYEDpodIAX-NYLnc&_nc_ht=scontent.fbkk8-3.fna&_nc_tp=6&oh=214b659dcdb3b5b5aec0b3de547f8b8b&oe=5ECCCB85');
  display: flex;
  justify-content: center;
  object-fit: cover;
  padding: 10%;
  width: 800px;
  height: 450px;
  padding: 0%

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
  text-shadow: -4px 2px 3px #AFAFAF;
  font-size: 50px;
}
.front {
  display: flex;
  justify-content: center;
  text-align: center
}
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
