<template>
  <div id="contact">

      <!-- <img id="lefts" src="http://img.nt-geek.club/左边的树.png">
      <img id="rights"  SRC="http://img.nt-geek.club/右边的树.png">
      <img id="uscontact" src="http://img.nt-geek.club/联系我们.png">

      <img id="bianselong2"  src="http://img.nt-geek.club/变色龙2.png"> -->
     
      <!-- <img id="yezi"  src="https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fhbimg.b0.upaiyun.com%2Fcbc74c499dd0ecc99174c482008311c5dd36229faf5f-WvBNfP_fw658&refer=http%3A%2F%2Fhbimg.b0.upaiyun.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=auto?sec=1664783705&t=2a336b3beb3ff105694d2c2eb47b44c4"> -->
      <div id="wen4">

          <span>•热爱理学精神,善于创新,勤奋好学,永远保持对新知识的好奇之心、探索之心<br></span>
          <span>•有编程/算法/数学建模基础的可附上说明,我们乐于发掘自动化的卧虎藏龙<br></span>
          <span>•有团队意识,热爱竞赛,不言放弃,敢闯敢拼,拿得起、放得下！<br></span>
        
      </div>

      <div id="wayofcontact">


        <button id="cf4" target="_blank" onclick="window.location.href='https://jq.qq.com/?_wv=1027&k=AbBxAtHa'" alt="传帮带招新群" title="群号:243239322" class="q">招新群</button>

        <button id="cf5" onclick="window.location.href='https://www.wjx.top/vm/YRJSTaJ.aspx#'" TITLE="Geek组Github" class="q">报名表</button>

        <button id="yx" target="_blank" onclick="window.location.href='https://jq.qq.com/?_wv=1027&k=kPH4RfRS'" alt="自动化数模交流群" title="群号:304681838" class="q">交流群</button>

      </div>


  </div>
</template>
<script>
  import Copy from 'copy-util';
  export default {
    name: "contactus",
    methods: {
      bn1() {
        var value = document.getElementById("yx").title;
        Copy(value);
        alert("邮箱地址已复制到粘贴板")}}}
</script>
<style scoped>
  @media (min-width: 501px){
 

  #lefts{height: 38vw;position: relative;left:15%;}
  #rights{height: 43vw;position: relative;left: 51%;top: -0vw;}
  #yezi{width: 10vw;position:absolute;top: -1.5vw;right: 37vw;}
  #cf4 {left: 28vw;}
  #cf5 {left: 62vw;}
  #yx {left: 45vw;}
#bianselong2{
  display: none;
}
  #contact{position: relative;right: 10%;top: 240vw;}
  span{font-size: 1.5vw;font-family: FZYaoti;position: relative;top: -26vw;color:rgb(69, 100, 90);line-height: 2.8vw;}
  #wen4{position: absolute; left: 55%;top:35vw;line-height: 2vw;width: 600vw;} 
  #uscontact{width: 24vw;position:relative;top: -38vw;right: 16%;}
  #wayofcontact{position: absolute;top: 69%;font-family: FZYaoti;}
  
    

    button{
      position: absolute;
      width: 10vw;
      height:3vw;
      font-family: FZYaoti;
      cursor: pointer;
      color:white;
      font-size: 2vw;
      border-radius: 1vw;
      border-color: rgb(69, 100, 90);
      border-width: 0.2vw;
      outline: none;
      -webkit-transition-duration: 0.4s;
      transition-duration: 0.4s;
      background-color:rgb(69, 100, 90);
      box-shadow: none;
    }
    button:hover{
      background-color:rgb(255, 255, 255);
      border: none;
      color: rgb(69, 100, 90);
      transform: scale(1.1);
    }

    a{
      position: absolute;
      text-decoration: none;
      display: inline-block;
      text-align: center;
      line-height: 2.5vw;
      margin: 30px 3px;
      background-color: white;
      font-size: 2vw;
      letter-spacing: 2px;
      border-radius: 40px;
    }
    }


@media (max-width: 500px) {
  #contact{position: relative;top: 460vw;width: 100vw;height: 240vw;}
  #lefts {display: none;}
  #yezi {display: none;}
  #uscontact { width: 50vw;position: absolute;top: 1vw;left:20vw;z-index: 2;}
  #rights{
    display: none;
  }
  #bianselong2{
    position: absolute;
    left: 27vw;
    width: 75vw;
    height: 142vw;}
  #wen4{position: relative;top:33vw;font-family: FZYaoti;font-size: 4.5vw;left:13vw;line-height: 6vw;
  width: 70vw;}
  #cf4 {
    width: 18vw;
    height:5vw;
    color:white;
    font-size: 2vw;
    border-radius: 1vw;
    border-color: rgb(69, 100, 90);
    -webkit-transition-duration: 0.4s;
    transition-duration: 0.4s;
    outline: none;
    border-width: 0.2vw;
    background-color:rgb(69, 100, 90);
    box-shadow: none;
    position: absolute;
    left: 36vw;
    transition-duration: 0.4s;
    top: 114vw;
    transition-duration: 0.4s;
  }
  #cf4:hover{    color: rgb(69, 100, 90);
    background-color: white;

    border: none;
    transform: scale(1.1);
  }
  #cf5 {
    width: 17vw;
    height:5vw;

    font-size: 2vw;
    border-radius: 1vw;
    border-color: rgb(69, 100, 90);
    -webkit-transition-duration: 0.4s;
    transition-duration: 0.4s;
    outline: none;
    border-width: 0.2vw;

    box-shadow: none;
    position: absolute;
    transition-duration: 0.4s;
    top: 114vw;
    left: 62vw;
    transition-duration: 0.4s;    color:white;
    background-color:rgb(69, 100, 90);
  }
  #cf5:hover{
    background-color: white;
    border: none;    color: rgb(69, 100, 90);
    transform: scale(1.1);
  }
  #yx {
    width: 17vw;
    height:5vw;
    color:white;
    font-size: 2vw;
    border-radius: 1vw;
    background-color:rgb(69, 100, 90);
    border-color: rgb(69, 100, 90);
    -webkit-transition-duration: 0.4s;
    transition-duration: 0.4s;
    outline: none;
    border-width: 0.2vw;

    box-shadow: none;
    position: absolute;
    left: 10vw;
    transition-duration: 0.4s;
    top: 114vw;
  }
  #yx:hover{    color: rgb(69, 100, 90);

    border: none;
    transform: scale(1.1);    background-color: white;
  }
  a{
    position: absolute;
    text-decoration: none;
    display: inline-block;
    text-align: center;
    line-height: 2.5vw;
    margin: 30px 3px;
    background-color: white;
    font-size: 2vw;
    letter-spacing: 2px;
    border-radius: 40px;
  }
}
</style>
