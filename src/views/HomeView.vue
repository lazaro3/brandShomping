<template>


 <body class="container">
     <SideBar></SideBar>   
     <Header></Header>
     <HeaderSide></HeaderSide>
     <Content></Content>
     <Footer></Footer>
 </body>
 
</template>

<script>
  import SideBar from '@/components/SideBar.vue';
  import Header from '@/components/Header.vue';
  import Content from '@/components/Content.vue';
  import HeaderSide from '@/components/HeaderSide.vue';
  import Footer from '@/components/Footer.vue';

export default {
  name: 'HomeView',
  components: {
    SideBar,
    Header,
    Content,
    HeaderSide,
    Footer,
  }
}
</script>