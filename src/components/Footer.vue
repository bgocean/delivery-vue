<template>
  <footer class="footer">
      <div class="container">
        <div class="footer-box">
          <router-link to="/" class="footer-logo logo">
            <img src="../assets/images/logo.png" alt="logo" />
          </router-link>
          <div class="footer-nav">
            <ul>
              <li><a href="#">Ресторанам</a></li>
              <li><a href="#">Курьерам</a></li>
              <li><a href="#">Пресс-центр</a></li>
              <li><a href="#">Контакты</a></li>
            </ul>
          </div>
          <div class="footer-social">
            <a href="#">
              <img src="../assets/images/social/inst.png" alt="inst" />
            </a>
            <a href="#">
              <img src="../assets/images/social/fb.png" alt="fb" />
            </a>
            <a href="#">
              <img src="../assets/images/social/vk.png" alt="vk" />
            </a>
          </div>
        </div>
      </div>
    </footer>
</template>

<script>
export default {
  
}
</script>

<style scoped>
.footer {
  display: flex;
  align-items: center;
  min-height: 156px;
  padding: 60px 0;
}

.footer-box {
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 36px;
  flex-wrap: wrap;
}

.footer-nav {
  flex-grow: 1;
}

.footer-nav ul {
  display: flex;
  align-items: center;
  list-style: none;
  padding: 0;
  margin: 0;
  gap: 15px;
  flex-wrap: wrap;
}

.footer-nav ul li {
  color: #595959;
  font-size: 18px;
  font-weight: 400;
}

.footer-nav a {
  text-decoration: none;
}

.footer-social {
  display: flex;
  align-items: center;
  justify-content: flex-end;
  gap: 20px;
}

</style>