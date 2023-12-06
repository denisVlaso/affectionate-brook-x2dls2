<template>
  <div id="app">
    <Header></Header>
    <div class=dialog>
    <People></People>
    <Message></Message></div>
    <div>
        <Footer />
    </div>

    
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Message from './components/Message.vue';
import People from './components/People.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'App',
  components: {
    Header,
    Message,
    People,
    Footer
  }
}
</script>

<style>
body{
    margin: 0;
    padding:0;
    background-color: rgb(108, 168, 221);
    display: block;
}
.dialog{
    width:154.4vh;
    display: flex;
}
</style>