<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style lang="scss">
a,
b,
body,
button,
dd,
div,
dl,
em,
footer,
form,
h1,
h2,
h3,
h4,
h5,
h6,
i,
input,
label,
li,
nav,
p,
select,
span,
td,
textarea,
u,
ul {
  padding: 0;
  margin: 0;
  -webkit-tap-highlight-color: transparent;
  -webkit-text-size-adjust: none
}

li,
ol,
ul {
  list-style: none
}

a {
  text-decoration: none;
  color: #414a60
}

a:active,
a:focus,
a:hover,
button,
input,
textarea {
  outline: 0
}

a:hover {
  color: #00d7c6;
  text-decoration: none;
  -webkit-transition: all linear .2s;
  transition: all linear .2s
}

img {
  border: none
}

map area {
  outline: 0
}

table {
  border-collapse: collapse
}

body,
button,
input,
option,
select,
td,
textarea {
  font-family: arial, verdana, helvetica, 'PingFang SC', 'HanHei SC', STHeitiSC-Light, Microsoft Yahei, sans-serif;
  -webkit-font-smoothing: antialiased
}

button,
input[type=button],
input[type=number],
input[type=password],
input[type=search],
input[type=submit],
input[type=tel],
input[type=text],
textarea {
  -webkit-appearance: none
}

body {
  background: #f6f6f8;
  min-width: 1184px;
  line-height: 26px;
  color: #414a60;
  font-size: 14px
}

body,
html {
  height: 100%
}

body {
  height: 100.1%
}

body.page-white {
  background: #fff
}
</style>
