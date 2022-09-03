<template>
  <div id="cat">


      <div id="wen2">
          <span id="p1">编程手(Programmer)</span><br>
          <p style="color:purple;">"Life is Short,you need Python。"</p>
          <p id="ab">编程手在数学建模竞赛中负责将模型逻辑转化为代码。</p><br>
          <li class="a">编程手需要熟练掌握至少一门高级语言。</li><br><br>
          <li class="a">需要学习MATLAB、Python、C++等常用语言</li><br><br>
          <li class="a">擅长使用算法、数据可视化。</li>
      </div>

      
      <!-- <img id="chanpin" src="http://img.nt-geek.club/chanpin.png">
      <img id="chanpin2" src="http://img.nt-geek.club/俩个.png">
      <img id="heiban"  src="https://gd-hbimg.huaban.com/95e5e5142ae806f8cf20d6f8d7e5331a0886e1a1106c4-MVdOil_fw658"> -->
  <!-- <img id="prx" src="https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fb-ssl.duitang.com%2Fuploads%2Fitem%2F201808%2F19%2F20180819133522_prilf.jpg&refer=http%3A%2F%2Fb-ssl.duitang.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=auto?sec=1664791825&t=0ed16fd54c38f4656b3fdef7c5c2bce8"> -->
   </div>
</template>

<style scoped>
  @media screen and (min-width:501px) {
    #chanpin2{display: none;}
    #prx{
      display: none;
      
    }
    #heiban{display: none}
    #cat{position:relative;top: 76vw;left: -8%;}
    #chanpin{width: 35vw;height: 170vw;position: absolute;top: 0%;left: 18%;}
    span{font-size: 2vw;font-family: FZYaoti}
    p{font-size: 2.7vw;font-family: FZYaoti;position: relative;top:1.5vw;}
    li{font-size: 2vw;font-family: FZYaoti}
    #wen2{position: relative;
      font-family: FZYaoti;
      top: 0vw;
      left: 35%;
      width:40vw}
    #p1{font-size: 3vw}
    .a{position: relative;top:3vw;}
    #ab{
      font-size: 2vw;font-family: FZYaoti;
      position: relative;
      top: 3vw;
    }
  }
  @media(max-width: 500px){
 
    #chanpin{
      display: none;
      }
   #cat{
      position: relative;
      top: 348vw;
      width: 10%; 
    }



    #chanpin2{
      height: 170vw;
      position: relative;
      top: 10vw;
      left: 18vw;
      z-index: 200;
      }
    #heiban{
       width: 20vw;
       position: absolute;
       top: 10vw;
       left: 70vw;
       z-index: 2;
       }
    #wen2{
      position: absolute;

      left: 10vw;
      z-index: 2;
      }

    span{
      font-size: 4.5vw;
      font-family: FZYaoti;
      }

    #p1{
      font-size: 6vw;
      font-family: FZYaoti;
      position: absolute;
      width: 70vw;
      top: 18vw;
      }
    p{
      font-size: 4.5vw;
      font-family: FZYaoti;
      position: absolute;
      width: 70vw;
      top: 27vw;
      }
    #ab{
      font-size: 4.5vw;
      font-family: FZYaoti;
      position: absolute;
      top: 40vw;
      width: 70vw;
      }
    li{
      font-size: 4.5vw;
      font-family: FZYaoti;
      position: relative;
      top: 46vw;
      width: 80vw;
      }
    #prx{
      width: 100vw;
      height: 170vw;
      /* padding:10%; */
      position: absolute;
      top: -0vw;
      left: 0%;
      }
  }

</style>

