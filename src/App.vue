<template>
  <div id="nav"></div>
  <router-view />
</template>

<script>
export default {
  components: {},
};
</script>

<style lang="scss">
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
ul {
  list-style: none;
}

body {
  font-family: "Roboto", sans-serif;
  background: rgb(243, 243, 243);
  overflow-x: hidden;
  transition: all ease 0.5s;
}
::-webkit-scrollbar {
  width: 3px;
}

/* Track */
::-webkit-scrollbar-track {
  background: transparent;
}

/* Handle */
::-webkit-scrollbar-thumb {
  background: #1ebd77;
}

/* Handle on hover */
::-webkit-scrollbar-thumb:hover {
  background: #555;
}
</style>
