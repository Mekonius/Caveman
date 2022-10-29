<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading><p class="orange">Kenneth</p></template>
    <template #text>
      <div class="border-spacing-1 border-dotted border-gray-700 border-4 ">
        <p>
          <img alt="caveman" class="profile" src="@/assets/kenneth.png"  />

        </p>
        <p>
          Teacher at Aarhustech

        </p>
      </div>
    </template>

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading><p class="orange">Michael</p></template>
    <template #text>
      <div class="border-spacing-1 border-dotted border-gray-700 border-4 ">
        <p>
          <img alt="caveman" class="profile" src="@/assets/kenneth.png"  />

        </p>
        <p>
          student at Aarhustech

        </p>
      </div>
    </template>

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading><p class="orange">Pierre</p></template>
    <template #text>
      <div class="border-spacing-1 border-dotted border-gray-700 border-4 ">
        <p>
          <img alt="caveman" class="profile" src="@/assets/kenneth.png"  />

        </p>
        <p>
          Teacher at Aarhustech

        </p>
      </div>
    </template>

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading><p class="orange">Victor</p></template>
    <template #text>
      <div class="border-spacing-1 border-dotted border-gray-700 border-4 ">
        <p>
          <img alt="caveman" class="profile" src="@/assets/kenneth.png"  />

        </p>
        <p>
          Teacher at Aarhustech

        </p>
      </div>
    </template>

  </WelcomeItem>

</template>


