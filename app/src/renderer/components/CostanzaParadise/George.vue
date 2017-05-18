<template>
  <img class="ourlordandsaviour" src="./george.jpg" />
</template>

<script type="text/javascript">

</script>

<style>
.ourlordandsaviour {
  animation: threesixty infinite 2s ease-out;
  border-radius: 50%;
}

@keyframes threesixty {
  0% { transform: scale(0.2, 0.2); }
  10% { transform: rotate(0deg); }
  20% { transform: rotate(90deg); }
  30% { transform: rotate(180deg); }
  40% { transform: rotate(270deg); }
  50% { transform: rotate(360deg); }
  60% { transform: rotate(270deg); }
  70% { transform: rotate(180deg); }
  80% { transform: rotate(90deg); }
  90% { transform: rotate(0deg); }
  100% { transform: scale(0.2, 0.2); }
}
</style>