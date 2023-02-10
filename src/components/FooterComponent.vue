<template>
  <footer>
    <p>© {{ currentYear }} {{ conf.SITE_NAME }}</p>
  </footer>
</template>

<script>
export default {
  data() {
    return {
      currentYear: new Date().getFullYear(),
      conf: {
        SITE_NAME: "Your Site Name",
      },
    };
  },
};
</script>

<style>
footer {
  background-color: #333;
  color: #fff;
  text-align: center;
  padding: 20px;
}
</style>
