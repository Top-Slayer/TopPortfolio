<template>
  <div class="input-group rounded" id="position">
    <div style="font-size: 160%; margin-right: 20px; font-weight: 700">
      SKILLs LIST
    </div>

    <input
      style="
        font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI',
          Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue',
          sans-serif;
      "
      type="search"
      class="rounded-3"
      placeholder=" Search"
      aria-describedby="search-addon"
    />
  </div>
</template>

<style scoped>
#position {
  position: absolute;
  top: 20px;
  left: 10%;
}
input[type="search"] {
    width: 500px;
    padding: 10px;
    border: 1px #ccc;
    background-color: #5B6B75
}
::placeholder {
  color: #CCCCCC;
  opacity: 1; /* Firefox */
}
</style>
