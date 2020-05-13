<template>
  
<div>
      
            <label for="countries">Choose a Country</label>
            <select v-model="selectedCountry" name="#" id="country">
                <option  v-for="(country, index) in countries" :value="country"> {{ country.name }}  </option>
                 </select>
               
     

</div>

</template>

<script>
export default {
name: 'country-selected'
}
</script>

<style>

</style>