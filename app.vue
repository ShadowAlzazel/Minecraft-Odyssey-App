<script setup>
  const logs = reactive({})
</script>


<template>
  <div class="container">
    <h1>Minecraft Odyssey</h1>
    <p>The Official Website for Minecraft Odyssey!</p>
    <div class="dev-logs-container">
    </div>
    <div class="dev-links-container">
        <h4>Quick Links</h4>
        <div class="dev-link-buttons">
          <button 
          class="github-link-button">Github
          
          </button>
        </div>
      </div>
  </div>
</template>



<style scoped>
.container {
  font-family: Arial, Arial, Helvetica, sans-serif;
  color: rgb(242, 195, 39);
  max-width: 50rem;
  margin: 0 auto;
  text-align: center;
}
.container h1 {
  font-size: 3rem;
}

.dev-links-container {
  background-color: rgb(56, 54, 47);
  border-radius: 3rem;
  padding: 1rem;
  width: 95%;
  margin: 0 auto;
  margin-top: 4rem;
  position: relative;
}

.github-link-button {
  background: rgb(33, 110, 204);
  outline: 0.15rem solid rgb(242, 195, 39);
  border: none;
  padding: 0.55rem;
  border-radius: 0.35rem;
  color: rgb(242, 195, 39);
  cursor: pointer;
}

</style>
