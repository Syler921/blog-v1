<template>
<div>
    <div class="container">
        <div class="row">

          <BlogCard/>
          <BlogCard/>
          <BlogCard/>
          <BlogCard/>

        </div>
        <div class="row">

          <BlogCard/>
          <BlogCard/>
          <BlogCard/>
          <BlogCard/>

        </div>
    </div>

</div>











</template>

<script>


import Logo from '~/components/Logo.vue'
import BlogCard from '~/components/BlogCard.vue'
import {$,jQuery} from 'jquery';



export default {
  components: {
    Logo,
    BlogCard
  }
}
</script>

<style>

</style>
