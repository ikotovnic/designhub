<template>
  <div>
    <div class="header">
      <router-link to="/">
        <div class="logo"> <img src="./assets/logo.svg"></div>
      </router-link>
      <div class="nav">
        <router-link to="/ForDesigners">
          <p>for designers</p>
        </router-link>
        <router-link to="/">
          <p>for employers</p>
        </router-link>
        <p>contact</p>
      </div>
    </div>

    <transition name='router-anim'>
      <router-view />
    </transition>

  </div>
</template>

<style>
  :root {
    --color-accent:  #F5B40D;
  }

@import url('https://fonts.googleapis.com/css2?family=Roboto+Flex:opsz,wdth,wght,XTRA@8..144,100,400,468;8..144,100,600,468;8..144,100,1000,468;8..144,151,400,603&display=swap');

body{
  padding: 0px;
  margin: 0px;
}
a{
  text-decoration: none;
}
.header{
  display: flex;
  flex-direction: row;
  position: fixed;
  top: 0;
  left: 0;
  height: 70px;
  background: white;
  width: 100%;
  justify-content: space-between;
  align-items: center;
}
.header .logo{
  padding-left: 20px;
}
.header .nav{
  display: flex;
  flex-direction: row;
  gap: 30px;
  justify-content: space-between;
  padding-right: 20px;
}
.header .nav p{
  font-family: 'Roboto Flex';
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 16px;
  color: #1B1B1B;
}

.router-anim-enter-active{
  animation: coming 1.5s;
  animation-delay: 0s;
  opacity: 0;
  transform: scale(0.9);
}
.router-anim-leave-active{
  animation: going 0.5s;

}

@keyframes going {
  from {
    transform: scale(1);
  }
  to{
    opacity: 0;
    transform: scale(0.9);
  }
}

@keyframes coming {
  from {
    opacity: 0;
    transform: scale(0.7);
  }
  to{
    transform: translateX(0px);
    opacity: 1;
    transform: scale(1);
  }
}



</style>
