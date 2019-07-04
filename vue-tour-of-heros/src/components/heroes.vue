<template>
  <div>
    <label>name:
      <input v-model="hero.name" placeholder="name"/>
    </label>
  {{ hero }}
  </div>
</template>

<script>
export default {
  name: 'Heroes',
  data(){
    return {
      hero: 'Windstorm'
    }
  }
}
</script>

<style>

</style>
