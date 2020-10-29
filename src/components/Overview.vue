<template>
    <b-container class="bv-example-row bv-example-row-flex-cols" style="margin-top:5%;">
  <b-row align-v="start">
    <b-col style="text-align:left;">
      <h3 style="margin-bottom:5%;">Lorem ipsum dolor sit amet consectetur adipisicing.</h3>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ullam deleniti, facilis fugit harum consequuntur perspiciatis a alias dicta repudiandae nostrum odit amet suscipit.</p>
        <a href="#" style="color:red; font-style:italic;">Learn More >></a>
    </b-col>
    <b-col>
    <div>
  <youtube :video-id="videoId"></youtube>
   </div>
    </b-col>
  </b-row>
</b-container>
</template>

<script>
export default {
    name: 'Overview',
    data () {
    return {
        text: '',
        videoId: "VuN8qwZoego"
      }
  }
}
</script>

<style>

</style>