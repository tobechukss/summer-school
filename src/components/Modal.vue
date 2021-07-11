<template>
  <transition name="fade">
    <div class="modal" v-if="show">
      <div class="modal__backdrop" @click="closeModal()"/>

      <div class="modal__dialog">
        <div class="modal__closing">
          <slot name="closing"/>
        </div>

        <div class="modal__body">
          <slot name="body"/>
        </div>



      </div>
    </div>
  </transition>
</template>

<script>
export default {
  name: "Modal",
  data() {
    return {
      show: false
    };
  },
  methods: {
    closeModal() {
      this.show = false;
      document.querySelector("body").classList.remove("overflow-hidden");
    },
    openModal() {
      this.show = true;
      document.querySelector("body").classList.add("overflow-hidden");
    }
  }
};
</script>


<style scoped>

div.addstudent div.input-parent-detail {
  display: flex;
}
div.modal {
  overflow-x: hidden;
  overflow-y: auto;
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 9;
}
div.modal div.modal__backdrop {
    background-color: rgba(0, 0, 0, 0.3);
    position: fixed;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    z-index: 1;
  }

div.modal div.modal__dialog {
    background-color: #ffffff;
    position: relative;
    width: 600px;
    padding: 20px;
    margin: 50px auto;
    display: block;
    border-radius: 5px;
    z-index: 2;
  }


div.modal div.modal__closing {
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
  align-items: flex-end;
  margin-right: 20px;

}





div.modal__body {
    padding: 10px 20px 10px;
    text-align: center;
    overflow: auto;
    display: block;

  }

div.modal__body h2 {
  color: #353535;

}

div.modal__body p {
  color: #555555;


}
div.modal div.modal__footer {
    padding: 10px 20px 20px;
}

.fade-enter-active,
.fade-leave-active {
  transition: opacity 0.2s;
}
.fade-enter,
.fade-leave-to {
  opacity: 0;
}

@media screen and (max-width:650px) {
  div.modal div.modal__dialog {
    width: 400px;
  }
}
</style>
