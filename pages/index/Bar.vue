
<template>
    <div>
        <p>{{message}}</p>
        <nuxt-link to="/foo">go to /foo</nuxt-link>
    </div>
</template>

<script>
    export default {
      data(){
        console.log('bar.data')
        return {
          message: 'bar'
        }
      },
      created(){
        console.log('bar.created')
      },
      mounted(){
        console.log('bar.mounted')
      },
      activated(){
        console.log('bar.activated')
      },
      deactivated(){
        console.log('bar.deactivated')
      },
      beforeDestroy(){
        console.log('bar.beforeDestroy')
      }
    }
</script>
