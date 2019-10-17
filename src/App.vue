<template>
<div>
  <app-header></app-header>
  <router-view></router-view>
</div>
</template>


<script>
import showBlog from './components/showBlog';
import addBlog from './components/addBlog';
import listBlog from './components/listBlog';
import header from './components/header';


export default {
  components: {
    'add-blog' : addBlog,
    'show-blog' : showBlog,
    'list-blog' : listBlog,
    'app-header' : header,
  },
   data(){
     return{

     }
   }
}
</script>


<style>


</style>
