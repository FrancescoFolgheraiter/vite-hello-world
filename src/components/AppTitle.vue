<script>
export default {
    data() {
        return { text:"La mia prima app con Vite!"}
    }
};
</script>

<template>
    <div>
      <div class="my-container">
        <h3>
          {{ text }}
        </h3>
      </div>
    </div>
</template>

<style scoped>
.my-container{
  max-width: 1200px;
  border:2px dashed blue;
  text-align: center;
  margin:0 auto;
  color:lightcoral
}
</style>
