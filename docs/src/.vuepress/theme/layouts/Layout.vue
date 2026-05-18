<!-- .vuepress/theme/layouts/Layout.vue -->
<script setup>
import ParentLayout from '@vuepress/theme-default/layouts/Layout.vue'
</script>

<template>
  <ParentLayout>
    <template #page-bottom>
      <footer class="my-global-footer">
        <p>LocalGov Drupal is an open source collaboration between UK councils and Drupal developers. </p>
        <p>Drupal is a registered trademark of Dries Buytaert.</p>
      </footer>
    </template>
  </ParentLayout>
</template>

<style>
.my-global-footer {
  text-align: center;
  padding: 2rem 0;
  border-top: 1px solid var(--c-border);
  color: var(--c-text-light);
}
</style>
