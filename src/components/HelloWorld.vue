<template>
  <div class="greetings">
    <div>{{ $t("message.title") }}</div>
  </div>
</template>

<script>
import { useMouse } from "../composables/useMouse.js";

export default {
  name: "HelloWorld",
  props: {
    msg: {
      type: String,
      required: true,
    },
  },
};
</script>
