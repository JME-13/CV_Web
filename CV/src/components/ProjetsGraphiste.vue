<template>
    <Menu />
    <MenuRight />
    <div class="content-container">
      <section class="top-container"><img class="setting-icons" src="../assets/images/settingIcons.png"></section>
            <div class="projects-box">
                <div class="row row-cols-1 row-cols-md-3">
                <div class="col">
                    <div class="img__wrap">
                        <img src="../assets/images/Cards/Centro208.png" class="img__img" alt="...">
                            <div class="img__description_layer">
                                <h5 class="img__description">Centro 208</h5>
                            </div>
                        </div>
                    </div>
                <div class="col">
                    <div class="img__wrap">
                        <img src="../assets/images/Cards/Edadis.png" class="img__img" alt="...">
                            <div class="img__description_layer">
                                <h5 class="img__description">Edadis</h5>
                            </div>
                        </div>
                    </div>
                <div class="col">
                    <div class="img__wrap">
                        <img src="../assets/images/Cards/SoL.png" class="img__img" alt="...">
                            <div class="img__description_layer">
                                <h5 class="img__description">Summer Of Legends</h5>
                            </div>
                        </div>
                    </div>
                </div>
                <br>
                <div class="row row-cols-1 row-cols-md-3">
                <div class="col">
                    <div class="img__wrap">
                        <img src="../assets/images/Cards/Omar.png" class="img__img" alt="...">
                            <div class="img__description_layer">
                                <h5 class="img__description">Industrias Omar</h5>
                            </div>
                        </div>
                    </div>
                <div class="col">
                    <div class="img__wrap">
                        <img src="../assets/images/Cards/Superfacial.png" class="img__img" alt="...">
                            <div class="img__description_layer">
                                <h5 class="img__description">Superfacial</h5>
                            </div>
                        </div>
                    </div>
                <div class="col">
                    <div class="img__wrap">
                        <img src="../assets/images/Cards/Oropesa.png" class="img__img" alt="...">
                            <div class="img__description_layer">
                                <h5 class="img__description">Oropesa del Mar</h5>
                            </div>
                        </div>
                    </div>
                </div>
                <br>
                <div class="row row-cols-1 row-cols-md-3">
                <div class="col">
                    <div class="img__wrap">
                        <img src="../assets/images/Cards/Dialogos.png" class="img__img" alt="...">
                            <div class="img__description_layer">
                                <h5 class="img__description">Dialogos 10</h5>
                            </div>
                        </div>
                    </div>
                <div class="col">
                    <div class="img__wrap">
                        <img src="../assets/images/Cards/Serigrafia.png" class="img__img" alt="...">
                            <div class="img__description_layer">
                                <h5 class="img__description">True Animals</h5>
                            </div>
                        </div>
                    </div>
                <div class="col">
                    <div class="img__wrap">
                        <img src="../assets/images/Cards/MX.png" class="img__img" alt="...">
                            <div class="img__description_layer">
                                <h5 class="img__description">Monsta X US Tour 2022</h5>
                            </div>
                        </div>
                    </div>
                </div>
                <br>
                <div class="row row-cols-1 row-cols-md-3">
                <div class="col">
                    <div class="img__wrap">
                        <img src="../assets/images/Cards/JH.png" class="img__img" alt="...">
                            <div class="img__description_layer">
                                <h5 class="img__description">PSYCHE - Joohoney</h5>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
    <p class="projects-btext"><span>Psst!</span> Trouve encore plus de mes projets sur <span>Behance</span>!</p>
    </div>

</template>

<script>
import Menu from '../components/Menu.vue'
import MenuRight from '../components/MenuRight.vue'

export default {
  name: 'ProjetsGraphiste',
  components: {
              Menu,
              MenuRight,
            },
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
      background-color: #7b9dd2;
    }

    .content-container {
      width: 70%;
      margin-bottom: 50px;
    }

    .projects-box {
        width: 95%;
        margin-top: 50px;
        margin-left: auto;
        margin-right: auto;
    }
    
    span {
        color:#7b9dd2;
        font-weight: bold;
    }

    .projects-btext {
        color: #352f6a;
        font-family: Big Pixel;
        font-size: 20px;
        font-weight: bold;
        text-align: center;
        margin-top: 50px;
    }

    .img__wrap {
        position: relative;
        height: 200px;
        width: 400px;
    }

    .img__img {
        height: 200px;
        width: 400px;
    }

    .img__description_layer {
        position: absolute;
        top: 0;
        bottom: 0;
        left: 0;
        right: 0;
        background: #7b9cd2bd;
        color: #fff;
        font-family: Big Pixel;
        font-weight: bold;
        visibility: hidden;
        opacity: 0;
        display: flex;
        align-items: center;
        justify-content: center;
        transition: opacity .2s, visibility .2s;
    }

    .img__wrap:hover .img__description_layer {
        visibility: visible;
        opacity: 1;
    }

    .img__description {
        transition: .2s;
        transform: translateY(1em);
    }

    .img__wrap:hover .img__description {
        transform: translateY(0);
    }
    </style>