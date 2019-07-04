<template>
  <div>
    <h2>{{hero.name | uppercase }} Details</h2>
    <div>
      <span>id: </span> {{ hero.id }}
    </div>
    <div>
      <label>name:  <input v-model="hero.name" placeholder="name"/></label>
    </div>
  </div>

</template>

<script>
export default {
  name: 'Hero',
  data () {
    return {
      hero: {
        id: 1,
        name: 'Windstorm'
      }
    }
  }
}
</script>

<style></style>
