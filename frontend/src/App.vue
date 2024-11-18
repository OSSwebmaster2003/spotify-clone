<script setup lang="ts">
import { SignedIn, SignedOut, SignInButton, UserButton } from 'vue-clerk'
</script>

<template>
  <SignedOut>
    <SignInButton>
      <el-button>Sign In</el-button>
    </SignInButton>
  </SignedOut>
  <SignedIn>
    <UserButton />
  </SignedIn>
</template>

<style scoped>

</style>
