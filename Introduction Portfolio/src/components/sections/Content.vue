<template>
  <div class="row p-5">
    <div class="col-6 mt-4">
      <img
        src="/images/Prop image.svg"
        width="310"
        class="img-fluid mx-auto d-block"
      />
    </div>

    <div class="col-6 text-center mt-3">
      <div class="row">
        <div class="col-6 m-3 background">
          <img src="/images/Unity.png" width="120px" class="mx-auto d-block p-3" />
          <div class="title_below_icon">
            UNITY Engine
          </div>
        </div>

        <div class="col-6 m-3 background">
          <img src="/images/Visual_studio.png" width="120px" class="mx-auto d-block p-3" />
            <div class="title_below_icon">VISUAL STUDIO</div>
        </div>
      </div>

      <div class="row">
        <div class="col-6 m-3 background">
          <img src="/images/C_sharp.png" width="120px" class="mx-auto d-block p-3" />
            <div class="title_below_icon">C# LANGUAGE</div>
        </div>

        <div class="col-6 m-3 background">
          <img src="/images/Game.png" width="120px" class="mx-auto d-block p-3" />
            <div class="title_below_icon">GAME DESIGN</div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.background {
  width: 150px;
  height: 160px;
  left: 0px;
  top: 0px;
  border-radius: 41px;
  border: 5.5px #1f2223 solid;
}
.title_below_icon{
    color: white;
    font-size: 15px;
    font-family: Reospec;
}
.light {
  opacity: 0.8;
  background: #c6e3ff;
  box-shadow: 56px 56px 56px;
  filter: blur(56px);
}
</style>
