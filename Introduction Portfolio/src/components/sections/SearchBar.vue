<template>
  <div class="row">
    <div class="input-group rounded" id="position">
      <!-- Skill list -->
      <div class="col-12 col-md-3">
        <div style="font-size: 160%; margin-right: 20px; font-weight: 700">
          SKILLs LIST
        </div>
      </div>
      <!-- Search bar -->
      <div class="col-8 col-md-5 pt-1 pt-md-0">
        <input
          style="
            font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI',
              Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue',
              sans-serif;
          "
          type="search"
          class="rounded-3 material-icons"
          placeholder=" Search..."
        />
      </div>
      <!-- microphone icon -->
      <div class="col-4 col-md-4 pt-1 pt-md-0">
        <a href="#">
          <span class="material-symbols-outlined apperance rounded-end-3">
            mic
          </span>
        </a>
      </div>
    </div>

  </div>
</template>

<style scoped>
#position {
  position: absolute;
  top: 20px;
  left: 10%;
}
input[type="search"] {
  padding: 10px;
  width: 101%;
  border: 1px #ccc;
  background-color: #5b6b75;
}
::placeholder {
  color: #cccccc;
  opacity: 1; /* Firefox */
}
.material-icons::before {
  content: "search"; /* Replace "search" with the name of the desired Material Icon */
  display: inline-block;
  font-family: "Material Icons";
  font-size: 24px; /* Adjust the font size as needed */
  line-height: 1;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  text-transform: none;
  white-space: nowrap;
  word-wrap: normal;
}
.apperance {
  color: #cccccc;
  font-size: 30px;
  position: relative;
  font-weight: lighter;
  background-color: #5b6b75;
  padding: 7px;
}
</style>
