<template>
  <div class="container text-center mt-5">
    <div class="d-flex justify-content-around mb-4">
      <div v-for="n in 4" :key="n" class="circle"></div>
    </div>

    <div class="position-relative">
      <svg viewBox="00 0 500 100" preserveAspectRatio="none" class="curve-svg">
        <path d="M0,30 C150,90 350,0 500,30 L500,100 L0,100 Z" style="fill:#c4db00;"></path>
      </svg>

      <div class="icon-bar d-flex justify-content-around align-items-center">
        <div class="text-center">
          <i class="bi bi-house-door-fill icon"></i>
          <div class="label">Home</div>
        </div>
        <i class="bi bi-house-door-fill icon"></i>
        <i class="bi bi-gear-fill icon"></i>
      </div>
    </div>
  </div>
</template>

<script>
export default{
    name: 'FooterComp'

}

</script>

<style scoped>
.circle {
  width: 60px;
  height: 60px;
  border-radius: 50%;
  background-color: #d3d3d3;
}

.curve-svg {
  width: 100%;
  height: 100px;
  display: block;
}

.icon-bar {
  position: absolute;
  top: 0;
  width: 100%;
  height: 100px;
  padding: 10px 0;
  color: #1a1a00;
  font-size: 24px;
}

.icon {
  font-size: 30px;
}

.label {
  font-size: 14px;
}
</style>
