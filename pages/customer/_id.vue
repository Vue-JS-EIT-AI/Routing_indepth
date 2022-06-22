<template>
    <div>
        <h1>Customer  id:{{$route.params.id}}</h1>
    </div>
</template>


<script>
export default {
    //special property by Nuxt
    validate(data){
     /*   console.log(data)
        return true

        */
      // return data.params.id ==1

          //regular expression
      return /^\d+$/.test(data.params.id)

   

    }
}
</script>