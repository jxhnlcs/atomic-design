<template>
  <div class="component">
    <Logo />
    <NavItem text="Home" to="/home" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { Logo } from '@/components/atoms'
import { NavItem } from '@/components/atoms'

export default defineComponent({
  components: {Logo, NavItem}
});
</script>

<style lang="scss" scoped>
.component{
  width: 300px;
}
</style>
