<template><textarea :id="uid" rows="8" v-model="model.body.value"></textarea></template>
<script>
export default {
  props: ["uid", "model", "meta"]
}
</script>