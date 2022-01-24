<template>
  <div>
    <GmapMap 
    :center="center"
    :zoom="7"
    map-type-id="terrain"
    style="width:500px; height:300px"
    ></GmapMap>
  </div>
</template>
<script>
export default {
    name:"AddMap",
    data(){
        return{
            center:{lat: -87.0799, lng: 20.6274}
        }
    }
}
</script>
