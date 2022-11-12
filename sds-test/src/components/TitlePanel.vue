<script setup>
import IconUserInfo from './icons/IconUserInfo.vue'
</script>


<template>
  <div class="title-panel">
    <icon-user-info class="title-panel__icon" />
    <div class="title-panel__text">Title Big mob</div>
    <button class="title-panel__button">Label mob</button>
  </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Manrope:wght@500;600;700&display=swap');

.title-panel {
    position: relative;
    display: flex;
    width: 100%;
    height: 52px;
    padding: 8px 8px 8px 16px;
    box-sizing: border-box;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
    background: linear-gradient(90deg, #E81F2F 0%, #FF8983 100%);
    border-radius: 20px;
    font-family: 'Manrope', sans-serif;
}
.title-panel__icon {
  flex-shrink: 0;
}
.title-panel__text {
    padding-left: 19px;
    flex-grow: 1;
    font-style: normal;
    font-weight: 700;
    font-size: 20px;
    color: #fff;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
}
.title-panel__button {
    height: 36px;
    padding: 8px 16px;
    flex-shrink: 0;
    background: #FFFFFF;
    border-radius: 12px;
    outline: none;
    border: none;
    font-style: normal;
    font-weight: 500;
    font-size: 14px;
    line-height: 20px;
    text-align: center;
    letter-spacing: 0.0025em;
    color: #E81F2F;
}
</style>