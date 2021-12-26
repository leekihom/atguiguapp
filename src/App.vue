<template>
  <div>
    <Header />
    <Footer />
  </div>
</template>

<script>
//引入Header与Footer非路由组件
import Header from "./components/Header";
import Footer from "./components/Footer";
export default {
  name: "",
 
  components: {
    Header,
    Footer,
  },
  
};
</script>

<style scoped></style>
