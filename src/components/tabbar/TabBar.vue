<template>
  <div id="tab-bar">
   <slot></slot>
  </div>
</template>
<script>
export default {
  name: "TabBar",
  data() {
    return {};
  },
  components: {},
};
</script>
<style >
#tab-bar {
  display: flex;
  background-color: rgb(212, 206, 206);
  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;
  box-shadow: 0 -3px 10px rgba(100, 100, 100, 0.1);
}
</style>