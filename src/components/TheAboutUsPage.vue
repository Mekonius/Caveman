<script setup>
import AboutUsItem from './AboutUsItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import IconSupportIcon from './icons/IconSupport.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
</script>

<template>



  <AboutUsItem >
    <template #icon>
      <CommunityIcon />
      </template>
      <template #heading class="flex-0 flex-row ml-auto">
        <div>
          <p class="orange">Kenneth</p>
        </div>
      </template>

      <template #imageHolder>
        <img alt="caveman" class="profile" src="@/assets/kenneth.png"  />
      </template>
      
      <template #text>
        <div>
          <p class="AboutText">
            Teacher at Aarhustech (maybe IOS dev) 
          </p>
          <p>
            
          </p>
            
        </div>
    </template>

  </AboutUsItem>

  <AboutUsItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading><p class="orange">Mads</p></template>
    <template #text>
      <div>
        <p>


        </p>
        <p class="AboutText">
          The new guy !!!
        </p>
      </div>
    </template>

    <template #imageHolder>
        <img alt="caveman" class="profile" src="@/assets/kenneth.png"  />
      </template>

  </AboutUsItem>

  <AboutUsItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading><p class="orange">Michael</p></template>
    <template #text>
      <div>

        <p class="AboutText">
          student at Aarhustech

        </p>
      </div>
    </template>

    <template #imageHolder>
        <img alt="caveman" class="profile" src="@/assets/kenneth.png"  />
      </template>

  </AboutUsItem>

  <AboutUsItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading><p class="orange">Pierre</p></template>
    <template #text>
      <div>
        <p class="AboutText">
          student at Aarhustech

        </p>
      </div>
    </template>

    <template #imageHolder>
        <img alt="caveman" class="profile" src="@/assets/kenneth.png"  />
      </template>

  </AboutUsItem>

  <AboutUsItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading><p class="orange">Victor</p></template>
    <template #text>
      <div >

        <p class="AboutText">
          student at Aarhustech

        </p>
      </div>
    </template>

    <template #imageHolder>
        <img alt="caveman" class="profile" src="@/assets/kenneth.png"  />
      </template>

  </AboutUsItem>



</template>


