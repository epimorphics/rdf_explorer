<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Hind+Siliguri&display=swap');
body {
  overflow-wrap:break-word;
  background-color: white;
}
#app {
  font-family: 'Hind Siliguri', sans-serif;
  /* font-family: Avenir, Helvetica, Arial, sans-serif; */
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: black;
  overflow-wrap:break-word;
  overflow-x: hidden;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}

input {
  font-family: 'Hind Siliguri', sans-serif;
}

button:hover {
  cursor: pointer;
  text-decoration: underline;
}
button {
    padding: 1%;
    margin: 0.5%;
    color: #001c39;
    background-color: white;
    /* border: 3px solid #b1d8e7; */
    /* box-shadow: 0px 2px 10px 1px rgb(0, 0, 0); */
    border: 1px solid grey;
    text-transform: uppercase;
    border-radius: 1px;
    text-align: center;
}

button {
  font-family: 'Hind Siliguri', sans-serif;
  box-shadow: 0px 2px 5px 1px rgba(172, 172, 172, 0.01);
  border-radius: 3px;
  text-transform:none;
}

h2 {
  font-family: 'Montserrat', sans-serif;
}

h3 {
  font-family: 'Montserrat', sans-serif;
}

h1 {
  font-family: 'Montserrat', sans-serif;
  display: inline;
  font-size: 25px;
  margin: 0;
  padding: 0;
}

p {
  display: inline;
}

.inputBox {
  font-size: 80%;
  font-family: 'Hind Siliguri', sans-serif;
  border: 1px solid grey;
  border-radius: 3px;
}

.popupBacksplash {
  background: rgba(0,0,0,0.4);
  display: none;
  position: fixed;
  top: 0;
  height: 100%;
  width: 100%;
  z-index: 10000;
}

.popupBackground {
  background-color: #fff;
  box-shadow: 10px 10px 60px #555;
  display: inline-block;
  height: auto;
  max-width: 551px;
  min-height: 100px;
  vertical-align: middle;
  width: 60%;
  left: 30%;
  top: 90px;
  position: fixed;
  white-space:pre-wrap;
  text-align: left;
  padding: 50px 5%;
  z-index: 10000;
}

.popupCloseButton {
  background-color: #fff;
  border: 2px solid #999;
  cursor: pointer;
  font-weight: bold;
  font-size: 300%;
  line-height: 35px;
  position: absolute;
  top: 0px;
  right: 0px;
  width: 30px;
  height: 30px;
  text-align: center;
  z-index: 10000;
}
</style>
