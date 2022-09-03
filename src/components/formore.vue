
<template>
  <div id="foremo">
<img  id="b" src="http://img.nt-geek.club/question.png">
<img  id="decoration" src="http://img.nt-geek.club/s.png" alt="">
<img  id="decoration1" src="http://img.nt-geek.club/e.png" alt="">
<img  id="decoration2" src="http://img.nt-geek.club/g.png" alt="">
<img  id="decoration3" src="http://img.nt-geek.club/1.png" alt="">
<img  id="decoration4" src="http://img.nt-geek.club/%E7%99%BD.png" alt="">
<img  id="decoration5" src="http://img.nt-geek.club/%E7%99%BD.png" alt="">

    

    <div id="allquestion">

      <br><br><br><br>
        <div id="question1">
            <button v-on:click="btn1()">
                <li>1.什么是数学建模？</li>
            </button> <br>

            <span id="yinshen1"  class="a" style="display: block"><li>创新开拓、协力同心、数学抽象、学以致用。</li></span><br><br>
        </div>


        <div id="question2">
            <button v-on:click="btn2">
              <li>2.招新选拔是安排在什么时间？</li>
            </button><br>

            <span id="yinshen2" class="a" style="display: none"><li>按照惯例，正式招新时间是在国庆过后的第2~3周周末，不过今年因为疫情原因或有变动，笔试地点一般在第二教学楼。 如果想要了解我们，可以加入我们的QQ群，营员选拔具体的安排/变动会在交流群通知。</li></span><br><br>
        </div>


        <div id="question3">
            <BUTTON v-on:click="btn3()">
              <li>3.我们有考核机制嘛？是什么样子的？</li>
            </BUTTON><br>

            <span id="yinshen3" class="a" style="display: none"><li>
              嗯...我们希望入营学习的同学能够坚持到底、学有所获,所以会根据实际培训情况布置一定的训练任务,只要认真对待按时完成任务即可认定考核合格;对于长期消极参训的同学我们也不会留有太多的余地。
            </li></span><br><br>
        </div>


        <div id="question4">
            <BUTTON v-on:click="btn4()">
              <LI>4.进入“传帮带”培训会不会影响正常学业呢？</LI>
            </BUTTON><br>

            <span id="yinshen4" class="a" style="display: none"><li>放心！我们的课程培训都是在课余时间(暂定周末)进行,不会与日常课程冲突的！而且,我们的训练任务会给足时间,循序渐进。
               </li></span><br><br>
        </div>


        <div id="question5">
            <BUTTON v-on:click="btn5()"> 
              <LI>5.加入“传帮带”项目我能有什么收获嘛？</LI>
            </BUTTON><br>

            <span id="yinshen5" class="a" style="display: none"><li>“传帮带”数模培训实行小班制,学员与学长之间有充足交流机会！在数模“传帮带”里,可以较早地了解竞赛知识,在数模赛道上领跑超越;可以认识一群志同道合的前辈同僚,携手向数模世界奋进！
                      </li></span><br>
        </div>


        <div id="question6">
            <BUTTON v-on:click="btn6()">
              <li>6.“传帮带”招生对象包括哪些呢？有门槛吗？</li>
              </BUTTON><br>
            <span ID="yinshen6" class="a" style="display: none"><li>自动化学院数学建模“传帮带”项目目前仅面向:自动化学院2022级新生招生,选拔考试不设门槛,均可报名参加!根据笔试成绩择优录取。*注：对于参训期间内转专业的同学,由于数模组队政策,将不能参与第二阶段以后的培训。
           </li></span><br>
        </div>
        <div id="question7">

            <BUTTON v-on:click="btn7()">
              <li>7.学长学姐们的期望是什么?</li>
            </BUTTON>
            <span id="yinshen7" class="a" style="display: none"><li>我们希望你有很强的自学能力,积极上进,对数学保持兴趣;对新技术保持好奇心,谦逊好学,善于创新;不轻言放弃,坚持不懈,和学长学姐们一起走到结营！
            </li></span><br>
        </div>

    </div>

</div>



</template>
<script>
  export default {
    el:"#foremore",
    data:{},
    methods:{
      btn1(){
        var value=document.getElementById("yinshen1").style.display;
        if(value=="none"){document.getElementById("yinshen1").style.display="block";}
        else if(value=="block"){document.getElementById("yinshen1").style.display="none";}
      },
      btn2(){
        var value=document.getElementById("yinshen2").style.display;
        if(value=="none"){document.getElementById("yinshen2").style.display="block";}
        else if(value=="block"){document.getElementById("yinshen2").style.display="none";}
      },
      btn3(){
        var value=document.getElementById("yinshen3").style.display;
        if(value=="none"){document.getElementById("yinshen3").style.display="block";}
        else if(value=="block"){document.getElementById("yinshen3").style.display="none";}
      },
      btn4(){
        var value=document.getElementById("yinshen4").style.display;
        if(value=="none"){document.getElementById("yinshen4").style.display="block";}
        else if(value=="block"){document.getElementById("yinshen4").style.display="none";}
      },
      btn5() {var value=document.getElementById("yinshen5").style.display;
        if(value=="none"){document.getElementById("yinshen5").style.display="block";}
        else if(value=="block"){document.getElementById("yinshen5").style.display="none";}
      },
      btn6(){
        var value=document.getElementById("yinshen6").style.display;
        if(value=="none"){document.getElementById("yinshen6").style.display="block";}
        else if(value=="block"){document.getElementById("yinshen6").style.display="none";}
      },
      btn7(){
        var value=document.getElementById("yinshen7").style.display;
        if(value=="none"){document.getElementById("yinshen7").style.display="block";}
        else if(value=="block"){document.getElementById("yinshen7").style.display="none";}
      },
    }
  }
</script>

<style scoped>
  @media(min-width: 501px) {
      #foremo{
        position: absolute;
        top: 300vw;
        left: 0%;
        width: 100%;
        background-color: #8dc6ff;
        min-height:77vw;
      }

      #b{
        z-index: 10;
        position: absolute;
        top: 2vw;
        right: 22%;
        width: 80%;
      }

      #bi2{
        display: none;
      }
#decoration{
  z-index: 10;
  position: absolute;
  top: 12vw;
  width: 23vw;
  left: -7%;
}

#decoration1{
  z-index: 10;
  position: absolute;
  top: 20vw;
  width: 20vw;
  left: 81%;
}

#decoration2{
  z-index: 10;
  position: absolute;
  top: 43vw;
  width: 12vw;
  left: 90%;
}

#decoration3{
  z-index: 10;
  position: absolute;
  top: 40vw;
  width: 15vw;
  left: -8%;
}

#decoration4{
  z-index: 10;
  position: absolute;
  top: 30vw;
  width: 10vw;
  left: 6%;
}

#decoration5{
  z-index: 10;
  position: absolute;
  top: 60vw;
  width: 14vw;
  left: 4%;
}

#decoration5{
  z-index: 10;
  position: absolute;
  top: 38vw;
  width: 8vw;
  left: 84%;
}






    span{
      line-height: 4vw;
      position: relative;
      overflow: hidden;
      left: 22%;
      width: 60vw;
      font-size: 1.8vw;
       font-family: FZYaoti;
       text-align: left;
       display: block;
       top: 2vw;
    }


      button{
        position: relative;
        background: #8dc6ff;
        height:5vw;
        color: white;
        border: none;
        left: 20%;
        position: relative;
        font-family:FZYaoti;
        transition-duration: 0.4s;
        outline: none;
        text-align: left;
        top: 2vw;
        width: 60vw;
        cursor: pointer;
      }

      button:hover::before{
        transition-duration: 2s;
        font-size: 1.4vw;
        transform: scale(1.3);
      }

      button:hover{
        color: #3e7af6;
        transform: scale(1.07);
        background-color: #9acdff;
      }

      li{
        font-size: 1.8vw;
        position: relative;
        left: 0%;
        width: 60vw;
        right: 10%;
        line-height: 4vw;
        }
    
    #allquestion{
      position: absolute;
      left: 0%;
      right: 0%;
      top: 7vw;
      background-color: #8dc6ff;
    }



  }

  @media (max-width: 500px) {
    #b{width: 80vw;position:absolute;top: -5vw;left: -3%;}
    #foremo {
      position: relative;
      top: 368vw;
      background-color: #8dc6ff;
      width: 100vw;
    }
    .a {
      text-align: center;
      font-size: 1.4vw;
      font-family: FZYaoti;
    }
    span{
      line-height: 4vw;
      position: relative;
      overflow: hidden;
      left: 3%;
      width: 87vw;
      font-size: 2vw;
      overflow: none;
      font-family: FZYaoti;
      text-align: left;
      display: block;
      top: 3vw;
    }
    button{
      position: relative;
      background: #8dc6ff;
      height:5vw;
      color: white;
      border: none;
      position: relative;
      font-family:FZYaoti;
      transition-duration: 0.4s;
      outline: none;
      text-align: left;
      top: 1vw;
      width: 100vw;
    }
    button:hover::before{
      transition-duration: 2s;
      font-size: 1.4vw;
      transform: scale(1.3);
    }
    button:hover{
      color: #3e7af6;
      font-size: 1.8vw;
      transform: scale(1.07);
      background-color: #9acdff;
    }
    li{
      font-size: 2.6vw;
      position: relative;
      left: 17vw;
      width: 63vw;
      line-height: 4vw;
      overflow: none;
    }
    li{position: relative;top: 0vw;line-height: 1.5;font-size:2.8vw;right:20 vw;}
    #question1{position: relative;top:-10vw;}
    #question2{position: relative;top:-15vw;}
    #question3{position: relative;top:-18vw;}
    #question4{position: relative;top:-22vw;}
    #question5{position: relative;top:-26vw;}
    #question6{position: relative;top:-25vw;}
    #question7{position: relative;top:-25vw;}
  #decoration{
  z-index: 10;
  position: absolute;
  top: 12vw;
  width: 23vw;
  left: -7%;
}

#decoration1{
  z-index: 10;
  position: absolute;
  top: 20vw;
  width: 20vw;
  left: 81%;
}

#decoration2{
  z-index: 10;
  position: absolute;
  top: 43vw;
  width: 12vw;
  left: 90%;
}

#decoration3{
  z-index: 10;
  position: absolute;
  top: 40vw;
  width: 15vw;
  left: -8%;
}

#decoration4{
  z-index: 10;
  position: absolute;
  top: 30vw;
  width: 10vw;
  left: 6%;
}

#decoration5{
  z-index: 10;
  position: absolute;
  top: 60vw;
  width: 14vw;
  left: 4%;
}

#decoration5{
  z-index: 10;
  position: absolute;
  top: 38vw;
  width: 8vw;
  left: 84%;
}
    }
  
</style>
