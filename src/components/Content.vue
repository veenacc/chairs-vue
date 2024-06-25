  <script>
    import ChairsIndex from "./ChairsIndex.vue";

    export default {
      components: {
      ChairsIndex,
      },

      methods: {
        getData: function() {
          console.log('getting the data...')
          // axios.get("http://localhost:3000/horses.json").then(response => {
          //   console.log(response.data)        
          //   this.horses = response.data
          // })
        }
      },
    };
  </script>

  <template>
    <main>
    
     <button v-on:click="getData">Get the data</button>
     
    </main>
  </template>

  <style></style>