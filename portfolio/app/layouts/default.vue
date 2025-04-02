<template>
  <nav>
    <ul>
      <li>
        <NuxtLink to="/">Main</NuxtLink>
      </li>
      <li>
        <NuxtLink to="/about">about</NuxtLink>
        <!-- <a href="/about">about</a> -->
      </li>
    </ul>
  </nav>
  <div>
    <slot />
  </div>
</template>
