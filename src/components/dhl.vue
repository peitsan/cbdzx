<template>
    <div id="dh">


          <button id="geek">
          <img id="GEEK" src="../assets/mainpic2.jpg" >
          </button>
          <button id="sayings">Keep Curiosity&Studing<br>The Power Of Evolution</button>

    </div>
    
</template>

<script>
    export default {
        name: "dhl"
    }
</script>

<style scoped>
  @media(min-width: 551px) {

    #anniu{display: none}
    button{
      position: absolute;
      top: 1%;
      left: 25vw;
      outline: none;
      background: none;
      border: none;
      transition-duration: 0.5s;
    }

    button:hover{
    transform: scale(1.1);
    }

    #sayings{
      position: absolute;
      font-family:HWHupo;
      font-size: 1.8vw;
      font-weight: 900 ;
      color: rgb(251, 219, 219);
      left: 39vw;
      top:36vw;
      cursor: pointer;
    }

    #geek{
      position: relative;
      width: 100vw;
      top: 12vw;
      cursor: pointer;
    }

       #GEEK{
      position: relative;
      width:66vw;
      top: 1vw;
      left: -27vw;
      cursor: pointer;

    }


    #fontz1{
      position:absolute; left: 3vw;
      top:1.5%;
      cursor: pointer;
    }
    #fontz2{position:absolute;right: 12vw;top:1.5%;}
    #fontz3{
      position: absolute; right: 3vw;
      top:1.5%;
    }
    .a{font-size: 1.8vw;
      font-family: STHupo;
    }
    #dh {
      position: absolute;
      background: url("https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fb-ssl.duitang.com%2Fuploads%2Fitem%2F201808%2F19%2F20180819133522_prilf.jpg&refer=http%3A%2F%2Fb-ssl.duitang.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=auto?sec=1664791825&t=0ed16fd54c38f4656b3fdef7c5c2bce8");
      background-size: 100% 100%;
      width: 96%;
      height: 300vw;
      background-color: #efefef;
      left: 2%;
      right: 2%;
      margin: 0 auto;
      top: 2%;
    }}
  @media (max-width: 550px) {
#geek{
  background: none;
  border: none;
  outline: none;
}

      #GEEK{
        position: absolute;
        top: 50vw;
        left: 5%;
        height: 68vw;
        transition-duration: 4ms;
      }

      #sayings{
      display: none;
      }
      #GEEK:hover{
        transform: scale(1.1);
      }


    #dh{background: url("../assets/banner.png");
      position: absolute;
      background-size: 100% 100%;
      width: 100%;
      height: 30vw;}
  }
    @font-face {
      font-family: STHupo;
      src: url(font.ttf);
      font-weight: bold;
    }
    @font-face {
      font-family: FZYaoti;
      src: url(fzyaoti.ttf);
      font-weight: bold;
  }
</style>
