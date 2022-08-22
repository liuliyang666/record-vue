<template>
  <Layout class-prefix="layout">
    <NumberPad />
    <Types />
    <Notes />
    <Tags />
  </Layout>
</template>

<script lang="ts">
import NumberPad from "@/components/NumberPad.vue";
import Notes from "@/components/Notes.vue";
import Types from "@/components/Types.vue";
import Tags from "@/components/Tags.vue";

export default {
  components: { NumberPad, Notes, Tags, Types },
  name: "Money",
};
</script>

<style lang="scss">
.layout-content {
  display: flex;
  flex-direction: column-reverse;
}
</style>
