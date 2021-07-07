<template>
  <div class="links">
    <div>
    <a href="#" class="more" @click="isOpen = !isOpen">
      {{ title }}
      <span class="material-icons">arrow_drop_down</span>
    </a>
    <transition name="fade" appear>
    <div class="sub-menu" v-if="isOpen">
      <div v-for="(item, i) in items" :key="i" class="menu-item">
        <a href="item.link">{{ item.title }}</a>
      </div>
    </div>
  </transition>
  </div>
</div>

</template>

<script>
export default {
  name: 'dropdown',
  props: ['title', 'items'],
  data() {
    return {
      isOpen: false
    }
  }
}
</script>

<style>
nav .links .sub-menu {
   position: relative;
  background-color: #fff;

  margin-right: 0;

  padding: 10px;
  width: max-content;
  border-radius: 0px 0px 16px 16px;
}
div.sub-menu, div.menu-item, div.links {
  padding: 0;
  margin: 0;
}

div.sub-menu div.menu-item a {
  padding: 20px;
}
.fade-enter-active,
.fade-leave-active {
  transition: all 1s ease-out;
}

.fade-enter,
.fade-leave-to {
  opacity: 0;
}
</style>
