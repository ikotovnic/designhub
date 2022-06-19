<template>
  <div>
    <div class="mobile-logo"><img src="./assets/logo.svg"></div>
    <div class="header">

        <router-link to="/">
          <div class="logo"> <img src="./assets/logo.svg"></div>
        </router-link>

        <div class="nav">

              <router-link to="/">
               <span>for employers</span>
              </router-link>

              <router-link to="/ForDesigners">
                <span>for designers</span>
              </router-link>
              <router-link to="/contact">
                <span>contact</span>
              </router-link>
        </div>
    </div>

<router-view v-slot="{ Component }">
  <transition name="scale">
    <component :is="Component" />
  </transition>
</router-view>

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
.mobile-logo{
  display: none;
}

.header{
  display: flex;
  flex-direction: row;
  position: fixed;
  top: 0;
  left: 0;
  height: 70px;
  background-color: rgba(255, 255, 255, 1);
  width: 100%;
  justify-content: space-between;
  align-items: center;
  z-index: 99;
}
@supports ((-webkit-backdrop-filter: none) or (backdrop-filter: none)) {
  .header{
    background-color: rgba(255, 255, 255, 0.6);
    -webkit-backdrop-filter: blur(10px);
    backdrop-filter: blur(10px);
  }
}

.header .logo{
  padding-left: 20px;
}
.header .nav{
  display: flex;
  flex-direction: row;
  gap: 10px;
  justify-content: space-between;
  padding-right: 20px;
  padding: 0px 10px 0px 10px;
  height: 40px;
}

.header .nav a{
  color: #1b1b1b;
  transition: all 1s;
  padding: 0px 10px 0px 10px;
  border-radius: 10px;
  font-family: 'Roboto Flex';
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 16px;
  text-decoration: none;
  display: flex;
  justify-content: center;
  align-items: center;
}

.scale-enter-active{
  transition: all 0.5s ease;
  transition-delay: 0.5s;
}
.scale-leave-active {
  transition: all 0.5s ease;
}

.scale-enter-from,
.scale-leave-to {
  opacity: 0;
  transform: scale(0.95);
}

.nav a.router-link-exact-active{
  color: #1b1b1b;
  background-color: #ff5151;
  padding: 0px 10px 0px 10px;
  border-radius: 10px;
  display: flex;
  justify-content: center;
  align-items: center;
}

@media screen and (max-width: 600px){
  .mobile-logo{
    display: unset;
    position: fixed;
    top: 0;
    left: 0;
    margin: 10px 0px 0px 10px;
    height: unset;
    z-index: 99;
  }
  .mobile-logo img{
    width: 100px;
  }
  .header{
    top: unset;
    bottom: 0;
    height: 50px;

  }
  .header .logo{
    display: none;
  }

  .header .nav{
    width: 100%;
    padding: 0px 10px 0px 10px;
    height: 40px;
  }

}
</style>
