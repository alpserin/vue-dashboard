<template>
  <div class="top-bar">
    <h2 class="title">
      <font-awesome-icon :icon="['fas', 'bolt']" />
      Last 3 Days for the Campaign - Our Online Appointment Platform is Open!
    </h2>
    <div class="button">
      <button id="detail-button" type="button" class="btn btn-primary btn-sm">
        Details
      </button>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.top-bar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: white;
  border-radius: 9px;
  padding-top: 12px;
  padding-bottom: 4px;
  margin-left: 10px;
  margin-right: 225px;
  height: 46px;
}

.title {
  font-size: 16px;
  margin-left: 20px;
  color: rgb(0, 102, 219);
}

.button {
  margin-right: 10px;
  margin-bottom: 5px;
}
</style>
