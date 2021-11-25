<template>
  <header>
    <div class="left-header">
      <div class="logo">
        <img src="../assets/dc-logo.png" alt="dc-logo">
      </div>
    </div>
    <div class="right-header">
      <ul>
        <li v-for="link,i in links" :key="i">
          <a :href="link.url" :class="link.active ? 'active' : '' ">{{link.text}}</a>
        </li>
      </ul>
    </div>
  </header>
</template>

<script>
export default {
  name: 'Header',
  data() {
    return{
      links:[
        {
          text: "CHARACTERS",
          url: "#",
          active: false
        },
        {
          text: "COMICS",
          url: "#",
          active: true
        },
        {
          text: "MOVIES",
          url: "#",
          active: false
        },
        {
          text: "TV",
          url: "#",
          active: false
        },
        {
          text: "GAMES",
          url: "#",
          active: false
        },
        {
          text: "COLLECTIBLES",
          url: "#",
          active: false
        },
        {
          text: "VIDEOS",
          url: "#",
          active: false
        },
        {
          text: "FANS",
          url: "#",
          active: false
        },
        {
          text: "NEWS",
          url: "#",
          active: false
        },
        {
          text: "SHOP",
          url: "#",
          active: false
        }
      ]
    };
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  header{
    width: 60%;
    height: 150px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;

    .right-header{

      li{
        display: inline;
        margin-right: 10px;
        list-style-type: none;
        font-size: 20px;

        a{
          text-decoration: none;
          color: black;
        }
        .active{
          color: #0282F9;
        }
      }

    }
    
  }
</style>
