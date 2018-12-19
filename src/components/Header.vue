<template>
  <header class="navbar navbar-default footer">
        <ul class="nav nav-pills mynav">
            <li class="active"><a href="#">萌书</a></li>
            <li><a href="#">分类</a></li>
            <li><a href="#">购物车</a></li>
            <li><a href="#">我的</a></li>
        </ul>
    </header>
</template>
<script>
export default {
  name: 'header'
}
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
html {
  position: relative;
  min-height: 100%;
}
body {
  /* Margin bottom by footer height */
  margin-bottom: 2.5rem;
}
.footer {
  position: fixed;
  bottom: 0;
  width: 100%;
  /* Set the fixed height of the footer here */
  height: 2.5rem;
  background-color: #f5f5f5;
  padding:0;
  text-align:center;
}
.mynav{
  width:100%;
  height: 2.5rem;
  line-height:2.5rem;
}
.mynav li{
  width:25%;
  height:100%;
}
</style>
