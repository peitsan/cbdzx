<template>
  <div id="fontend">


    <div id="wen1">

          <span id="fq1">建模手(Modelizer)</span><br>
          <p  id="we1" >“Stay Hungry，Stay Foolish” </p><br>
        <div id="wenzi1">
          <li>建模手在数模竞赛中负责对题目的解答并输出数学语言答案。</li><br><br>
          <li>需要熟练地学习常用数学模型、智能算法、具有较强的数据分析能力。</li><br><br>
          <li>建模对数学思维能力的要求更高,需要系统地学习数学模型。</li>
        </div>
    </div>

    <!-- <img id="monkey" src="http://img.nt-geek.club/houzi.png">
    <img id="houzi" src="http://img.nt-geek.club/shangbanshen.png"> -->
    <img id="houzibeijing" src="https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fb-ssl.duitang.com%2Fuploads%2Fitem%2F201808%2F19%2F20180819133522_prilf.jpg&refer=http%3A%2F%2Fb-ssl.duitang.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=auto?sec=1664791825&t=0ed16fd54c38f4656b3fdef7c5c2bce8">
  
    <!-- <img id="houzibeijing" src="https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fhbimg.huaban.com%2Ff3b41ec76b81667f46d951b56a905639cd7595cd1b0a7-Pyh74C_fw658&refer=http%3A%2F%2Fhbimg.huaban.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=auto?sec=1664782708&t=f9448c13d133eca92aa8ec63380ba267"> -->
    <!-- <img id="xiangjiao" src="http://img.nt-geek.club/香蕉.png"> -->
  </div>
</template>
<style scoped>


  @media screen and (min-width:501px){
  #fontend{
    position: absolute;
    top:75vw;
    height: 170vw;
    left: 37%;
  }
#houzibeijing{
  height: 60vw;
  display: none;
}
  #xiangjiao{
    display: none;
    }

  #houzi{
    display: none;
    }

  #monkey{
    width: 34vw;
    height: 45vw;
    position: absolute;
    top: 15%;left: 75%;
  }

#wen1{position: relative;
  top:19%;
  left: 20%;
  font-family: FZYaoti;
  width: 40vw;
}

#fq1{font-size: 3.5vw;
}

#fq2{
  font-size: 2.5vw;
  position: relative;
  top: -1vw;
  }
  
span{
  font-size: 2vw;
  font-family: FZYaoti
  }

p{
  color:#7BD3FF;
  font-size: 3vw;
  font-family: FZYaoti;
  line-height: 2
  }

li{
  position: relative;
  font-size: 2vw;
  font-family: FZYaoti;
  left: 0%;
  }

#we1{
  position: relative;
  top:-0.3vw;
  }

}


  @media (max-width: 500px) {

    #we1{
      position: absolute;
      left: 2vw;
      top: 190vw;
      width: 100vw;
      }

      #wenzi1{
      position: absolute;
      left: 2vw;
      top: 200vw;
      width: 74vw;
      font-size: 2vw;
      }
    #fq1{
      position: absolute;
      left: 2vw;
      top: 180vw;
      width: 100vw;
      }

    #monkey{display: none}


    #xiangjiao{
      position: absolute;
      width: 20vw;
      left: 70vw;
      z-index: 10;
      top: 190vw;
      }

    #houzi{ 
      position: absolute;
      width: 67%;
      left: 25vw;
      top: 300vw;
      z-index: 10;
    }
    #houzibeijing{ 
      position: absolute;
      width: 100%;
      left: 0vw;
      top: 10vw;
      height:930vw;
      z-index: -10;
    }



    #fq1{
      font-size: 7vw;
      }

    #wen1{
      position: absolute;
      left: 11%;
      top: 21vw;
      z-index: 2;
      }

    span{
      font-size: 4.5vw;
      font-family: FZYaoti;
      }

    p{
      color:#5593f0;
      font-size: 6vw;
      font-family: FZYaoti;
      }

    li{
      font-size: 4.5vw;
      font-family: FZYaoti;
      }

  }
</style>
