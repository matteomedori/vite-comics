<script>
export default {
  name: "Card",
  props: ["thumb", "title"],
};
</script>

<template>
  <div class="card">
    <img :src="thumb" :alt="title" />
    <h5>{{ title }}</h5>
  </div>
</template>
