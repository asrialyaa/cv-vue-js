<!-- <script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>-->

<template>
<div class="imgnya">
<img src="@/assets/Photo.png" alt="">
<h1>Software Developer</h1>
<p>Asri is a student from Taruna Bhakti Vocational High School majoring in software engineering likes new things about IT. In order to improve his abilities, he continued develop knowledge and skills for more work experience continue and have a good impact on his career.</p>
<button>Let's Talk</button>
</div>
</template> 

<style>
  .imgnya img{
    position: relative;
    top: 5rem;
    left: 85%;
    width: 200px;
    margin-bottom: 7rem;
  }
  .img img,h1{
    margin-left: 6rem;
  }
  .imgnya h1{
    position: relative;
    left: 16rem;
  }
  .imgnya p{
    position: relative;
    left: 22rem;
  }
  .imgnya button {
    position: relative;
    margin-top: 2rem;
    width: 150px;
    height: 30px;
    left: 35rem;
    border: 1px solid #333;
    background: transparent;
    border-radius: 17px 17px 1px 17px;
  }
  .imgnya button:hover {
    background: rgb(255, 188, 63);
    border: none;
  }
</style>