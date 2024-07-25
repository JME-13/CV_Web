<template>
    <div class="content-container">
      <section class="top-container"><img class="setting-icons" src="../assets/images/settingIcons.png"></section>
      <h1>Contact Test</h1>
      <br>
      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ea facilis labore consectetur placeat cumque temporibus adipisci ducimus. Dolores ducimus reprehenderit mollitia vero, officiis ad! A eos maiores tenetur dolorum quia?
    </div>
    </template>

<script>
export default {
  name: 'ContactComponent',
  data() {
    return {
      // Your data properties here
    };
  },
  created() {
    // Ensure no infinite loops or recursion
  },
  methods: {
    // Ensure proper handling of methods
  },
};
</script>
    
<style scoped>
    .top-container {
        background-color: #a76cad;
  }

    h1 {
      text-align: center;
      font-family: Big Pixel;
      font-optical-sizing: auto;
      font-size: 48px;
      font-style: normal;
      margin-top: 50px;
    }
    
    .get-started {
      width: 200px;
      height: 50px;
      margin-left: auto;
      margin-right: auto;
      padding-top: 10px;
      color: white;
      text-align: center;
      font-family: Big Pixel;
      background-color: #a76cad;
      border-radius: 20px;
      border-color: black;
      border-width: 3px;
      border-style: solid;
    }
    
    .get-started:hover {
      background-color: #ab96ae;
    }
    </style>