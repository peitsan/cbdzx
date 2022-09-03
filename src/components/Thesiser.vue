<template>
  <div  id="se">

        <DIV id="wen3">

            <span id="d1">论文手(Thesiser)</span><br>
            <p  id="we3">"Night Pause But Typing Continue"</p><br>
            <span id="d2">论文手在数模竞赛中负责将研究过程、研究成果整理成论文。</span><br><br>
            <li class="c">需要掌握学术论文的写作方法,学习Tex、Word、Excel等软件使用。</li>
            <li class="c">论文手需要有较强的文献检索能力、综述归纳能力,并擅长学术写作。</li><br><br>
            <li class="c" id="dingwei">写论文一定是严谨踏实、精益求精。</li>
        </DIV>
            <!-- <img id="lion" src="http://img.nt-geek.club/anquan.png">
            <img id="shizi2"  src="http://img.nt-geek.club/shizi2.png">
            <img id="chap"  src="http://img.nt-geek.club/王冠.png"> !-->
           
            <!-- <img id="beijp" src="https://img2.baidu.com/it/u=3441828145,1668305802&fm=253&fmt=auto&app=138&f=JPEG?w=400&h=711">  -->
            <!-- <img id="beijp" src=" https://img0.baidu.com/it/u=1888835056,350422097&fm=253&fmt=auto&app=138&f=JPEG?w=500&h=888">  -->
  </div>


</template>
<style scoped>
  @media (min-width: 501px) {
    #shizi2{display: none}
    #chap{display: none}
    #se{position: absolute;left:10%;top:150vw}
    #lion{position:absolute;width:38vw;height: 42vw; top:-2%;left: 5%;}
    #wen3{position: absolute;top:3vw;left: 58%;width: 40vw;}
    #d1{font-size: 3vw}
    span{font-size: 2vw;font-family: FZYaoti}
    p{color:#7BD3FF;font-size: 2.3vw;font-family: FZYaoti;color: cornflowerblue;position: relative;top:1.5vw;}
    li{font-size: 2vw;font-family: FZYaoti}
    #d2{position: relative;top: 2vw;}
    .c{position: relative;top: 3vw;}
    #beijp{display: none}
  }
  @media (max-width: 500px) {
    #se{
      position: absolute;
      top: 500vw;
      height:170vw;
      left:0%;
      }

    #lion{
      display: none;
      }

    #shizi2 
    {height: 170vw;
      width: 65vw;
      z-index: 200;
      position: absolute;
      top: 120vw;
      left: 34vw;
    }

    #chap{ 
      width: 20%;
      z-index: 2;
      width: 20%;
      top: 5vw;
      right: 3%;
      position: absolute;
      }

    #wen3{
      position: absolute;
      top:20vw;
      left: 10vw;
      z-index:2;
      width: 80vw;
      }

    #beijp{
      width: 100vw;
      height: 440vw;
      position: absolute;
      top: 0vw;
      left: 0%;
    }

    #d2{
      position: relative;
      top:4vw;
      }

    span{
      font-size: 4.5vw;
      font-family: FZYaoti
      }

    p{
      color:cornflowerblue;
      font-family: FZYaoti;
      }

    li{
      font-size: 4.5vw;
      font-family: FZYaoti;
      position: relative;
      top:6vw;
      }

    #we3{
      font-size: 5vw;
      position: relative;
      top: 2.5vw;
      }

    #d1{
      font-size: 7vw;
      }
  }
</style>
