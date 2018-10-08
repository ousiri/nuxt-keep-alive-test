
<template>
    <div>
        <p>{{message}}</p>
        <nuxt-link to="/bar">go to /bar</nuxt-link>
    </div>
</template>

<script>
  export default {
    data(){
      console.log('foo.data')
      return {
        message: 'foo'
      }
    },
    created(){
      console.log('foo.created')
    },
    mounted(){
      console.log('foo.mounted')
    },
    activated(){
      console.log('foo.activated')
    },
    deactivated(){
      console.log('foo.deactivated')
    },
    beforeDestroy(){
      console.log('foo.beforeDestroy')
    }
  }
</script>
