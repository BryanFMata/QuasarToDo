<template>
<div>
    <h5>{{nome}}</h5>
    <h6>{{dataHora}}</h6>
</div>
</template>

<script>
  export default {
  name: 'UserName',
  components: {},
  props:['nome'],
  data () {
    return {
        dataHora: Date.now()
    }
  },
  mounted () {
  },
  computed: {
  },
  methods: {
  },
  watch: {
  }
}    
</script>