<template>
  <main>
    <SideBar/>
    <Content/>
  </main>

</template>

<script >
import SideBar from './components/SideBar.vue';
import Content from './components/Content.vue';

export default{
  components:{
    SideBar,
    Content

}
}
</script>