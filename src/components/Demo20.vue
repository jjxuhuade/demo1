<template>
    <div class="component">
        <div class="container">
            <div class="row">
                <router-link to="/demo19/11">/demo19/11</router-link> <br/>
                <router-link to="/demo20/22/child">/demo20/22/child</router-link> <br/>
                params:{{$route.params.id}} <br/>
                <router-view></router-view>
            </div>
        </div>
    </div>
</template>

<script>
  export default {
    data: function () {
      return {
      }
    },
    methods: {
    },
    mounted: function () {
      console.log('mounted')
    },
    watch: {
      '$route': function (to, from) {
        console.log(to)
      }
    }
  }
</script>


