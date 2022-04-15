<template>

    <div class="style">

        <nav class="navbar navbar-expand-lg navbar-light bg-light fixed-top">
  <a class="navbar-brand" href="#">
    <img src="../assets/AssetsNFTmaQer/Assets_des_sections_pareille/Entete/QryptoBank_Logotype_LogoMark.png"
      width="150px" alt="">
  </a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavQrypto"
    aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation" @click="show()">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" :class="{ 'show': isshow}" id="navbarNavQrypto">
    <ul class="navbar-nav mr-auto">
      <li class="nav-item active">
        <a class="nav-link" href="#"> <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#"><strong>Q</strong>ryptobank</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#"><strong>Q</strong>redit</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href=""><strong>Q</strong>ryptex</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href=""><strong>Q</strong>lubdeal</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="">AirDrop</a>
      </li>
      <li class="nav-item ml-5">
        <a class="nav-link ml-5">Pending Switzerland's regulation
          <img src="../assets/AssetsNFTmaQer/Assets_des_sections_pareille/Entete/Drapeau_suisse.svg" width="12px"
            alt="">
        </a>
      </li>
    </ul>
    <span class="navbar-text">
      <ul class="nav justify-content-end">
        <li class="nav-item">
          <a class="nav-link active" href="#">Connect</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">
            <img src="../assets/AssetsNFTmaQer/Assets_des_sections_pareille/Entete/moon.svg" alt="">
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">
            <img src="../assets/AssetsNFTmaQer/Assets_des_sections_pareille/Entete/apple-logo.svg" alt="">
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link">
            <img src="../assets/AssetsNFTmaQer/Assets_des_sections_pareille/Entete/playstore.svg" alt="">
          </a>
        </li>
      </ul>
    </span>
  </div>
</nav>

<div class="jumbotron jumbotron-fluid" id="image">
  <div class="container text-center">
    <h1 class="mb-3">The Place to create manage your <span class="text-primary">NFT Collection</span> </h1>
    <a href="#" class="btn btn-primary btn-lg" id="create_button" role="button">Create your account for free</a>
  </div>
  <div class="mt-5">
    <ul class="nav justify-content-center">
      <li class="nav-item">
        <a class="nav-link active" href="#">
          <img id="img" src="../assets/AssetsNFTmaQer/images/nfts/3.png" class="rounded-circle"
          v-bind:width="customWdth.img1"
          @mouseover="enterImg1()" @mouseleave="leaveImg1()"
          alt="">
        </a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">
          <img id="img1" src="../assets/AssetsNFTmaQer/images/nfts/1.png" class="rounded-circle"
          v-bind:width="customWdth.img2"
          @mouseover="enterImg2()" @mouseleave="leaveImg2()"
           alt="">
        </a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">
          <img src="../assets/AssetsNFTmaQer/images/nfts/2_copy.png" class="rounded-circle"
          v-bind:width="customWdth.img3"
          @mouseover="enterImg3()" @mouseleave="leaveImg3()"
          alt="">
        </a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">
          <img src="../assets/AssetsNFTmaQer/images/nfts/7.png" class="rounded-circle"
          v-bind:width="customWdth.img4"
          @mouseover="enterImg4()" @mouseleave="leaveImg4()"
          alt="">
        </a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">
          <img src="../assets/AssetsNFTmaQer/images/nfts/4.png" class="rounded-circle"
          v-bind:width="customWdth.img5"
          @mouseover="enterImg5()" @mouseleave="leaveImg5()"
            alt="">
        </a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">
          <img src="../assets/AssetsNFTmaQer/images/nfts/6.png" class="rounded-circle"
          v-bind:width="customWdth.img6"
          @mouseover="enterImg6()" @mouseleave="leaveImg6()"
           alt="">
        </a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">
          <img src="../assets/AssetsNFTmaQer/images/nfts/5.png" class="rounded-circle"
          v-bind:width="customWdth.img7"
          @mouseover="enterImg7()" @mouseleave="leaveImg7()"
           alt="">
        </a>
      </li>
    </ul>
  </div>
</div>

    </div>

</template>

<script>
export default {
    name : 'HeaderNav',
    data() {
      return {
        isshow: false,
        customWdth : {
            img1 : 60,
            img2 : 70,
            img3 : 80,
            img4 : 50,
            img5 : 80,
            img6 : 70,
            img7 : 60
        }
      }
   },
   methods: {
      show() {
          this.isshow = !this.isshow
      },
      enterImg1() {
        
        this.customWdth.img1 += 30;
    
      },

      enterImg2() {

        this.customWdth.img2 += 30;

      },
      enterImg3() {

        this.customWdth.img3 += 30;

      },
      enterImg4() {

        this.customWdth.img4 += 30;

      },
      enterImg5() {

        this.customWdth.img5 += 30;

      },
      enterImg6() {

        this.customWdth.img6 += 30;

      },
      enterImg7() {

        this.customWdth.img7 += 30;

      },

      leaveImg1() {

          this.customWdth.img1 = 60
      },

      leaveImg2() {

          this.customWdth.img2 = 70
      },
      leaveImg3() {

          this.customWdth.img3 = 80
      },
      leaveImg4() {

          this.customWdth.img4 = 50
      },
      leaveImg5() {

          this.customWdth.img5 = 80
      },
      leaveImg6() {

          this.customWdth.img6 = 70
      },
      leaveImg7() {

          this.customWdth.img7 = 60
      },
   }
}
</script>

<style>
    #image {
        background-image: url('../assets/AssetsNFTmaQer/Assets_des_sections_pareille/Entete/bg_QryptoBank.jpg');
        background-attachment: fixed;
        margin: 0;
        max-block-size: 50%;
        height: 400px;
        margin: auto;
    }

    #create_button {
    border-radius: 50px;
    text-transform: capitalize;
    box-shadow: 10px 5px 5px #2EBAFB;
}

  .style{
      padding-top: 3em;
      
  }

</style>