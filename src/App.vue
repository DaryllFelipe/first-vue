<template>
  <div class="main-container">
    <div class="top-bar"><TheTopBar /></div>
    <div class="app-container">
      <div class="container-fluid">
        <div class="row">
          <div class="col-xl-2 nav">
            <div class="container-fluid dashnav">
              <div class="row">
                <div class="col-xl-12 main-profile">
                  <TheProfile />
                </div>
                <div class="col-xl-12 main-nav">
                  <TheNavigation />
                </div>
              </div>
            </div>
          </div>
          <div class="col-xl-10 main-content">
            <div class="content"><router-view /></div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import TheNavigation from '@/components/TheNavigation.vue'
import TheProfile from '@/components/TheProfile.vue'
import TheTopBar from '@/components/TheTopBar.vue'
export default {
  components: {
    TheNavigation,
    TheProfile,
    TheTopBar
  }
}
</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300&display=swap');
</style>
<style>
html {
  height: 100%;
  overflow: hidden;
  scroll-behavior: smooth;
}
body {
  font-size: 16px;
  font-family: 'Roboto', sans-serif;
  text-align: left;
}
* {
  margin: 0px;
  padding: 0px;
}
/* width */
::-webkit-scrollbar {
  width: 7px;
}

/* Track */
::-webkit-scrollbar-track {
  box-shadow: inset 5px 5px 20px #f1f1f1;
  border-radius: 20px;
}

/* Handle */
::-webkit-scrollbar-thumb {
  background: #888;
  border-radius: 10px;
}

/* Handle on hover */
::-webkit-scrollbar-thumb:hover {
  background: #555;
}
.main-container {
  background-color: lightskyblue;
}
.app-container {
  width: 98%;
  margin-left: 15px;
  height: 92vh;
}
.top-bar {
  height: 8vh;
  width: 100%;
  background-color: lightcoral;
}
.nav {
  margin-top: 10px;
  width: 100%;
  height: 89vh;
}
.dashnav {
  width: 100%;
  height: 89vh;
  border-radius: 20px;
  border-radius: 10px;
  background-color: lightcoral;
  overflow: hidden;
}
.main-profile {
  background-image: url('../src/assets/bg.jpg');
  background-size: cover;
  background-repeat: no-repeat;
  -webkit-box-shadow: 0px 0px 11px -3px rgba(0, 0, 0, 0.75);
  box-shadow: 0px 0px 11px -3px rgba(0, 0, 0, 0.75);
  border-radius: 10px;
  width: 100%;
  height: 24vh;
}
.main-nav {
  -webkit-box-shadow: 0px 0px 11px -3px rgba(0, 0, 0, 0.75);
  box-shadow: 0px 0px 11px -3px rgba(0, 0, 0, 0.75);
  padding: 10px 10px;
  margin-top: 15px;
  border-radius: 15px;
  width: 100%;
  height: 63vh;
  overflow-x: hidden;
  overflow-y: auto;
}
.main-content {
  border-radius: 10px;
  margin-top: 10px;
  width: 100%;
  height: 89vh;
  background-color: white;
  overflow-x: hidden;
  overflow-y: auto;
  padding: 20px 20px;
}
</style>
