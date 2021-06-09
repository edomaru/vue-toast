<template>
  <div class="toast">
    <div class="toast-icon">
      <IconSuccess />
    </div>
    <div class="toast-content">
      <div class="toast-title">Success</div>
      <div class="toast-message">Data has been saved</div>
    </div>
    <button class="toast-button">&times;</button>
  </div>
</template>

<script>
import IconError from "./IconError.vue";
import IconWarning from "./IconWarning.vue";
import IconSuccess from "./IconSuccess.vue";

export default {
  components: {
    IconError,
    IconWarning,
    IconSuccess,
  },
};
</script>
