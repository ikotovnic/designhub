<template>
  <div class="wrap">

    <div class="firstscr">
      <div class="title">
        <p>provide the developers in a short time</p>
      </div>
      <div class="img">
        <img src="../assets/g1.svg">
      </div>
    </div>

    <div class="pluses">
      <div class="row">
        <div class="el">
          <p>You don't have to pay taxes</p>
        </div>
        <div class="el">
          <p>No need to hire developers</p>
        </div>        
      </div>
      <div class="row">
        <div class="el">
          <p>Hire an employee for a task</p>
        </div>
        <div class="el">
          <p>Employees for any period of time</p>
        </div>        
      </div>      
      <div class="row">
        <div class="el">
          <p>Working with NDA</p>
        </div>
        <div class="el">
          <p>Flexible and loyal system</p>
        </div>        
      </div> 
    </div>

    <div class="wehelp">
      <div>
        <img src="../assets/m1.svg">
      </div>
      <div class="txt">
        <p class="title">We’re helping Ukranian and Russian developers find projects all over the world</p>
        <p class="text">Our company provides an opportunity for designers to find projects to work with all over the world</p>
      </div>
      <div>
        <img src="../assets/roundtxt-explore.svg">
      </div>
    </div>

    <div class="directions">
      <div class="row">
        <div class="el blue"><p>Interface design</p></div>
        <div class="el red"><p>Ui/Ux</p></div>
        <div class="el green"><p>Motion design</p></div>
      </div>
      <div class="row">
        <div class="el gray"><p>Interaction design</p></div>
        <div class="el yel"><p>Web design</p></div>
      </div>
      <div class="row">
        <div class="el red"><p>Graphic design</p></div>
        <div class="el purp"><p>Java-script</p></div>
        <div class="el blue"><p>Html/css</p></div>
        <div class="el gray"><p>3d-web</p></div>
      </div>
      <div class="row">
        <div class="el yel"><p>Branding</p></div>
        <div class="el green"><p>Illustrations</p></div>
      </div>
    </div>

    <div class="projects">
      <div class="title"><p>Projects of the designer we work with</p></div>
      <div class="list">
        <div class="row">
          <div class="el"><p>element</p></div>
          <div class="el"><p>element2</p></div>
        </div>
        <div class="row">
          <div class="el"><p>element3</p></div>
          <div class="el"><p>element4</p></div>
        </div>
      </div>      
    </div>

  </div>
</template>
<script>

</script>
<style scoped>
  .wrap{
    background-color: #fff;
  }
  p{
    font-family: 'Roboto Flex';
    font-style: normal;
    font-weight: 1000;
    font-size: 70px;
    line-height: 82px;
    color: #1B1B1B;
    font-stretch: 151;
    font-variation-settings: 'GRAD' 0, 'slnt' 0, 'XTRA' 603, 'XOPQ' 85, 'YOPQ' 70, 'YTLC' 514, 'YTUC' 712, 'YTAS' 767, 'YTDE' -173, 'YTFI' 738, 'opsz' 14;
    text-align: left;
  }

  .firstscr{
    display: flex;
    flex-direction: row;
    padding: 100px 60px 0px 30px;
    flex-wrap: wrap;
    justify-content: space-between;
    align-items: center;
  }
  .firstscr .title{
    max-width: 60%;
  }
  .pluses{
    display: flex;
    flex-direction: column;
    align-items: stretch;
    padding: 0px 10px;
    gap: 10px;
  }
  .pluses .row{
    gap: 10px;
    display: flex;
    flex-flow: row wrap;
    align-items: center;
    justify-content: space-around;
  }

  .pluses .row .el{
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 0px 40px 0px 40px;
    background: #F2F2F2;
    border-radius: 50px;
    flex: 1 auto;
    height: 225px;
  }

  .pluses .row .el p{
    font-family: 'Roboto Flex';
    font-style: normal;
    font-weight: 1000;
    font-size: 30px;
    line-height: 35px;

    color: #1B1B1B;
    font-stretch: 151;
    font-variation-settings: 'GRAD' 0, 'slnt' 0, 'XTRA' 603, 'XOPQ' 85, 'YOPQ' 70, 'YTLC' 514, 'YTUC' 712, 'YTAS' 767, 'YTDE' -173, 'YTFI' 738, 'opsz' 14;
  }

  .wehelp{
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    padding: 50px 50px 0px;
    gap: 70px;
    flex-wrap: wrap;
    justify-content: space-between;
  }
  .wehelp .title{
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 0px;
    gap: 10px;
  }
  .wehelp .txt{
    width: 50%;
  }
  .wehelp .txt .title{
    font-family: 'Roboto Flex';
    font-style: normal;
    font-weight: 1000;
    font-size: 30px;
    line-height: 35px;
  }
  .wehelp .txt .text{
    font-family: 'Roboto Flex';
    font-style: normal;
    font-weight: 400;
    font-size: 14px;
    line-height: 16px;
    color: #1B1B1B;
  }

  .directions{
    display: flex;
    flex-direction: column;
    align-items: stretch;
    padding: 0px 10px;
    gap: 10px;
  }
  .directions .row{
    gap: 10px;
    display: flex;
    flex-flow: row wrap;
    align-items: center;
    justify-content: space-around;
  }
  .directions .row .el{
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 0px;
    border-radius: 50px;
    padding: 0px 40px 0px 40px;
    flex: 1 auto;
    height: 225px;
  }
  .directions .row .blue{
    background: #146AD0;
  }  
  .directions .row .red{
    background: #FF6737;
  }
  .directions .row .green{
    background: #2FFF9B;
  }
  .directions .row .gray{
    background: #DBDBDB;
  }
  .directions .row .yel{
    background: #FFC635;
  }
  .directions .row .purp{
    background: #BD7CFF;
  }
  .directions .row .el p{
    font-family: 'Roboto Flex';
    font-style: normal;
    font-weight: 1000;
    font-size: 30px;
    line-height: 35px;
    color: #FFFFFF;
  }

  .projects{
    display: flex;
    flex-direction: column;
    padding: 0px 10px;
  }
  .projects .list{
    display: flex;
    flex-direction: column;
    gap: 10px;
  }
  .projects .row{
    display: flex;
    flex-direction: row;
    gap: 10px;
  }
  .projects .row .el{
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 0px 40px 0px 40px;
    background: #F2F2F2;
    border-radius: 50px;
    width: 50%;
  }
  .projects .row .el p{
    font-family: 'Roboto Flex';
    font-style: normal;
    font-weight: 1000;
    font-size: 30px;
    line-height: 35px;
  }

@media screen and (max-width: 600px){
    p{
      font-family: 'Roboto Flex';
      font-style: normal;
      font-weight: 1000;
      font-size: 26px;
      line-height: 30px;
      color: #1B1B1B;
      font-stretch: 151;
      font-variation-settings: 'GRAD' 0, 'slnt' 0, 'XTRA' 603, 'XOPQ' 85, 'YOPQ' 70, 'YTLC' 514, 'YTUC' 712, 'YTAS' 767, 'YTDE' -173, 'YTFI' 738, 'opsz' 14;
      text-align: left;
  }

    .firstscr{
      padding: 50px 10px 0px 10px;
    }

    .firstscr img{
      width: 120px;
    }

    .pluses .row .el{
      padding: 15px 30px 0px 30px;
      height: 165px;
    }
    .pluses .row .el p{
      font-size: 18px;
      line-height: 20px;
    }

    .wehelp{
      padding: 20px 10px 40px 10px;
      gap: 20px;
    }
    .wehelp .txt{
      width: 100%;
    }

    .directions .row .el{
      padding: 15px 30px 0px 30px;
      height: 165px;
    }
    .directions .row .el p{
      font-size: 18px;
      line-height: 20px;
    }

    .projects .row{
      display: flex;
      flex-flow: row wrap;
      justify-content: space-around;
    }
  .projects .row .el{
    width: 100%;
  }
}

 
</style>
