<template>
  <button class="btn">
    <slot></slot>
  </button>
</template>

<script>
export default {
  name: "my-button",
};
</script>

<style scoped>
.btn {
  /* margin-top: 15px; */
  align-self: flex-end;
  padding: 10px 15px;
  background: none;
  color: teal;
  cursor: pointer;
  border: 1px solid teal;
  transition: 0.5s;
}
.btn:hover {
  background: teal;
  color: white;
}
</style>