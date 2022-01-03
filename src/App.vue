<template>
  <div>{{ $t("message.hello", { msg: "hello" }) }}</div>
</template>

<script>
export default {
  components: {},
  data() {
    return {
      message: {
        hello: "{msg} world",
      },
    };
  },
  methods: {},
};
</script>

<style></style>
