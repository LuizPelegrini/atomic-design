<template>
  <form class="search-form">
    <input type="search" placeholder="Search" />
    <button type="submit">
      <img src="@/assets/images/icons/search.svg" alt="Search" />
    </button>
  </form>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({});
</script>

<style lang="scss" scoped>
.search-form {
  position: relative;
  width: max-content;
  input {
    width: 100%;
    border-radius: 1rem;
    padding: 0.5rem 1rem;
    border: none;
    box-shadow: 0 5px 5px rgba(#000000, 0.08);
    &::placeholder {
      color: #a9b0be;
    }
  }
  button {
    position: absolute;
    right: 3px;
    background-color: #ff895f;
    border: none;
    width: 30px;
    height: 30px;
    border-radius: 5rem;
    cursor: pointer;
    top: 50%;
    transform: translateY(-50%);
    display: grid;
    align-items: center;
    justify-items: center;
  }
}
</style>
