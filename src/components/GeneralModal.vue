<template>
    <div class="modal-container">
        <div class="modal-content-container">
        <slot name="content"></slot>
        <slot name="buttons"></slot>
        </div>
    </div>
</template>

<script>
export default {}
</script>

<style scoped>
.modal-container {
  display: flex;
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-color: rgba(0, 0, 0, 0.5);
  justify-content: center;
  align-items: center;
}

.modal-content-container {
  display: flex;
  flex-direction: column;
  width: 80%;
  margin: 50 auto;
  border: 1px solid red;
  background-color: white;
  align-items: center;
  justify-content: center;
}
</style>