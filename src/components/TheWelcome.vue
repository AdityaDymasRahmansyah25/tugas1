<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <h1><i>Pendidikan</i></h1>
        SDN 002 pkl.kuras<br>
        SMPIT at taqwa pkl.kerinci<br>
        SMKN 1 pkl.kerinci<br>
        Universitas islam riau
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <h1><i>Pengalaman</i></h1>
      Pernah Magang di Kantor pertanahan nasional
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <h1><i>Keahlian</i></h1>
      Ms. Word <br>
      C++ <br>
      Python <br>
      Java <br>
      HTML <br>
      CSS <br>
      JavaScript
  </WelcomeItem>


</template>
