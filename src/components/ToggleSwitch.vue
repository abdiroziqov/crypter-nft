<template>
  <label class="switch">
    <input type="checkbox" checked />
    <span class="slider round"></span>
  </label>
</template>

<script>
export default {};
</script>

<style>
.switch {
  position: relative;
  display: inline-block;
  width: 48px;
  height: 24px;
}

.switch input {
  opacity: 0;
  width: 0;
  height: 0;
}

.slider {
  position: absolute;
  cursor: pointer;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-color: #ccc;
  -webkit-transition: 0.4s;
  transition: 0.4s;
}

.slider:before {
  position: absolute;
  content: "";
  left: 4px;
  bottom: 4px;
  transition: 0.4s;
  width: 16px;
  height: 16px;
  background: #fcfcfd;
  border-radius: 32px;
}

input:checked + .slider {
  background-color: #3772ff;
}

input:focus + .slider {
  box-shadow: 0 0 1px #2196f3;
}

input:checked + .slider:before {
  -webkit-transform: translateX(26px);
  -ms-transform: translateX(26px);
  transform: translateX(26px);
}

/* Rounded sliders */
.slider.round {
  border-radius: 32px;
}

.slider.round:before {
  border-radius: 32px;
}
</style>
