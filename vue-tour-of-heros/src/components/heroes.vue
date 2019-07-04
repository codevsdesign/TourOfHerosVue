<template>
  <div>
    <h2>My Heroes</h2>
    <ul class="heroes">
      <li v-for="hero in heros" :key="hero.id">
        <span class="badge">{{hero.id}}</span> {{hero.name}}
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Heroes',
  data () {
    return {
      heros: [
        { id: 11, name: 'Dr Nice' },
        { id: 12, name: 'Narco' },
        { id: 13, name: 'Bombasto' },
        { id: 14, name: 'Celeritas' },
        { id: 15, name: 'Magneta' },
        { id: 16, name: 'RubberMan' },
        { id: 17, name: 'Dynama' },
        { id: 18, name: 'Dr IQ' },
        { id: 19, name: 'Magma' },
        { id: 20, name: 'Tornado' }
      ]
    }
  }
}
</script>

<style>

</style>
