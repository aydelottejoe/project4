<template>
<div id="app">
  <div class="header">
    <div class="title">
      <router-link to="/">
	<h1>Family Photos</h1>
      </router-link>
    </div>
  </div>
  <div class="content">
    <router-view />
  </div>
  <div class="footer">
    <router-link to="/" class="link">Add Photos </router-link>
    <a href="" class="link"> | </a>    
    <router-link to="/gallery" class="link"> Gallery </router-link>
    <a href="" class="link"> | </a>
    <a href="https://github.com/aydelottejoe/project4.git" class="link"> Github</a>
  </div>
</div>
</template>

<style>
html {
  box-sizing: border-box;
}

body {
  font-family: 'Montserrat', sans-serif;
  font-size: 16px;
  background: #fff;
  padding: 0px;
  margin: 0px;
}

/* Header */
.header {
  display: flex;
  padding: 10px 100px 0px 100px;
  background-color: #28B463;
  color: white;
  text-decoration: none;
}

.header a {
  color: white;
}

.title {
  margin-top: 5px;
}

.title h1 {
  font-size: 30px;
}

.content {
  padding: 20px 100px;
  min-height: 500px;
}

/* Footer */
.footer {
  height: 40px;
  padding: 20px 100px 0px 100px;
  background: #28B463;
  font-size: 12px;
}

.footer a {
  color: white;
}

h1 {
  font-size: 20px;
}

h2 {
  font-size: 14px;
}

.link {
  text-decoration: none;
}
</style>
