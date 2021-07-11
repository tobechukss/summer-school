<template>
  <div class="links">
    <div>
    <a href="#" class="dropdown" @click="isOpen = !isOpen">
      <i class="fa fa-bars fa-2x"></i>
    </a>

    <div class="sub-menus" v-if="isOpen">
      <div v-for="(item, i) in items" :key="i" class="menu-item">
        <a href="item.link">{{ item.title }}</a>
      </div>
    </div>

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
nav .links .sub-menus {
   position: fixed;
  background-color: #fff;

  margin-right: 100px;

  padding: 10px;
  transform: translateX(-50%);
  width: 400px;
  height: 500px;
  border-radius: 0px 0px 16px 16px;
}
div.sub-menus, div.menu-item, div.links {
  padding: 0;
  margin: 0;
}


div.sub-menus div.menu-item a {
  margin: auto;

  padding-bottom: 40px;
  font-size: 20px;
}


</style>
