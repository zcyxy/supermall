<template>
  <div id="tab-bar">
    <slot></slot>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  },
  methods: {},
  components: {}
};
</script>

<style scoped>
@import url("~assets/css/base.css");

#tab-bar {
  display: flex;
  background-color: #f4f4f4;

  position: fixed;
  left: 0px;
  right: 0px;
  bottom: -3px;

  box-shadow: 0px 1px -1px rgba(100, 100, 100, 0.1);
}
</style>
