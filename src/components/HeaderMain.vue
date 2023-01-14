<template>
  <div>
    <header class="header-in" id="header">
      <nav>
        <ul class="ul-list">
          <li><a href="#">HOME</a></li>
          <li><a href="#">ABOUT</a></li>
          <li><a href="#">CONTACT</a></li>
        </ul>
      </nav>
    </header>
  </div>
</template>

<script></script>

<style scoped>
.header-in {
  background-color: #ff7575;
  height: 100vh;
  position: relative;
}
.header-in img {
  position: absolute;
  top: 10%;
  right: 0;
}
/* ここからもホーム */
.ul-list {
  position: absolute;
  bottom: 0;
  font-size: 18px;
  color: #fff;
  margin-left: 20px;
  padding: 5px;
  border: 2px groove #fff;
  border-radius: 10px;
}

.ul-list li {
  margin-bottom: 10px;
  border-bottom: 2px solid #fff;
}

.ul-list li a:hover {
  color: #75d3ff;
}
</style>
