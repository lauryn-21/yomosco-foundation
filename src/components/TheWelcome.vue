<script setup>
import WelcomeItem from './WelcomeItem.vue'
import ToolingIcon from './icons/IconHome.vue'
import ToolingIcon from './icons/IconContact.vue'
import EcosystemIcon from './icons/IconCategories.vue'
import CommunityIcon from './icons/IconAbout.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <Homeicon />
    </template>
    <template #heading>Home</template>

    
    <a target="_blank" href="">official home page</a>
    provides you with all information 
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <Abouticon />
    </template>
    <template #heading>About</template>

    This foundation is served and bundled with
    <a href="" target="_blank">About page</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <Categoriesicon />
    </template>
    <template #heading>Categories</template>

    Get to know the organization of this foundation
    <a target="_blank" href="">Categories page</a>,
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <Contacticon />
    </template>
    <template #heading>Contact</template>

    Got stuck? Ask your question on
    <a target="_blank" href="">Contact page</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Support Yomosco</template>

    As an independent foundation, Yomosco relies on community backing for its sustainability. You can help
    us by becoming a member
    <a target="_blank" href="">Support page</a>.
  </WelcomeItem>
</template>
