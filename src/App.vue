<template>
<Navbar></Navbar>
<Header></Header>
<br>
<center>
<Rating></Rating> </center>
<br>
<hr>
<br>
<br>

<center><Content1></Content1></center>
<br>
<br>
<hr>
<Footer></Footer>

</template>


<script>
import Navbar from './components/Navbar.vue';
import Header from './components/Header.vue';
import Rating from './components/Rating.vue';
import Content1 from './components/Content1.vue';
import Footer from './components/Footer.vue';
export default {
  components: {
    Navbar,
    Header,
    Rating,
    Content1,
    Footer
  }
}
</script>