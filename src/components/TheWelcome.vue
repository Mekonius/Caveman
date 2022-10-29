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
    <template #heading><p class="orange">Back to basics</p></template>
    <template #text>
    <p>We are a company that want to go, back to a time where games where primitive, raw, and Repeatable </p>
    </template> 
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading><p class="orange">Oldschool is NewSchool</p></template>
    <template #text><p>
    Oldschool games have a charm, and a feel like no other, we want to preserve that feel with new technologies</p> 
    </template>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading><p class="orange">Game Design matters</p></template>
    <template #text>
    <p>We aim to put Gamedesign above anything else, everyone can make a shiny 8k dessert with unreal engine, we aim to take a different path</p>
    <h1>Less is more</h1>
  </template>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading><p class="orange">Fuck microtransaction</p></template>
    <template #text>
    We promise that our games only will have a 1 time price of <span class="orange">1000$</span>
  </template> 
  </WelcomeItem>

</template>
