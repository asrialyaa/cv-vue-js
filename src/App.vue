<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import "@/style.css"
import "bootstrap/dist/css/bootstrap.min.css"
import "bootstrap"
</script>

  <template>
  <header>

    <div class="wrapper">
      <!-- <HelloWorld msg="You did it!" /> -->

      <nav>
        <div class="logo">
          <a href="">Asri Alya Ramadhani</a>
        </div>
        <div class="tengah"> 
        <a href=""><RouterLink to="/">Personal</RouterLink></a>
        <a href=""><RouterLink to="/about">Skill</RouterLink></a>
        <a href="https://www.canva.com/design/DAFKGB_Mp-Q/ZE9fqdsJcCRYQrPcyYUiMw/view?utm_content=DAFKGB_Mp-Q&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink" target="_blank" style="margin-left: 6rem;">CV</a>
        </div>
      </nav>
      
    </div>
    <RouterView/>
  </header>

</template>