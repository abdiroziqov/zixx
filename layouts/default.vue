<template>
  <div>
    <NuxtLoadingIndicator />
    <header class="bg-green-100">
      <nav>
        <ul>
          <li>
            <RouterLink to="/"> Home </RouterLink>
            <RouterLink to="/about"> About </RouterLink>
          </li>
        </ul>
      </nav>
    </header>
    <NuxtPage />
    <footer>Some copyright things</footer>
  </div>
</template>
<script setup lang="ts"></script>
