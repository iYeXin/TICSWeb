<template>
  <div class="members-overlay">
    <div class="overlay-content">
      我社正发生大规模人事变动，具体人事详情尚未统计完毕，故该页面暂时不进行展示。
    </div>
  </div>
</template>

<style scoped>
.members-overlay {
  position: absolute;
  inset: 0;
  background-color: rgba(0, 0, 0, 0.8);
  backdrop-filter: blur(4px);
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: 10;
  overflow: hidden;
  height: 100%;
}

.overlay-content {
  color: white;
  font-size: 1.5rem;
  text-align: center;
  padding: 2rem;
  max-width: 80%;
  line-height: 1.6;
  background-color: rgba(0, 0, 0, 0.5);
  border-radius: 1rem;
  box-shadow: 0 0 20px rgba(0, 0, 0, 0.3);
}
</style>