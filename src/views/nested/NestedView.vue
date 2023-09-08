<template>
  <div>
    <ul class="nav nav-pills">
      <li class="nav-item">
        <RouterLink
          class="nav-link text-dark"
          active-class="text-bg-dark text-white"
          :to="{ name: 'NestedOne', replace: true }"
          >Nested One</RouterLink
        >
      </li>
      <li class="nav-item">
        <RouterLink
          class="nav-link text-dark"
          active-class="text-bg-dark text-white"
          :to="{ name: 'NestedTwo', replace: true }"
          >Nested Two</RouterLink
        >
      </li>
    </ul>
    <hr class="my-4" />
    <RouterView></RouterView>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped></style>
