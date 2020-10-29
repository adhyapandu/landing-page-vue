<template>
    <b-container class="bv-example-row bv-example-row-flex-cols" style="margin-bottom:5%">
  <b-row align-v="start">
    <b-col>
      <h2 class="sansserif" style="margin-bottom:6%; text-align:left; ">Contact</h2>
      <p style="text-align:left;">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Molestias voluptatibus quo vitae neque perferendis necessitatibus veritatis optio.</p>
    </b-col>
    <b-col>
      <div>
        <b-form inline style="margin-left:3% ">
            <label class="sr-only" for="inline-form-input-First Name">First Name</label>
              <b-input
                id="inline-form-input-First Name"
                class="mb-2 mr-sm-2 mb-sm-0"
                placeholder="First Name">
              </b-input>
            <label class="sr-only" for="inline-form-input-Last Name">Last Name</label>
            <b-input-group class="mb-2 mr-sm-2 mb-sm-0">
              <b-input 
              id="inline-form-input-Last Name" 
              placeholder="Last Name">
              </b-input>
            </b-input-group>
        </b-form>
        <div class="col-md-12">
         <input type="text" placeholder="Subject" class="form-control">
        </div> 
        <div class="col-md-12">
          <textarea placeholder="Message" rows="4" class="form-control">
          </textarea>
        </div> 
        <div class="col-md-8">
          <b-button type="submit" value="Send" variant="info" class="form-control text-uppercase">Send</b-button>
        </div>
      </div>
    </b-col>
  </b-row>
</b-container>
</template>

<script>
export default {
    name: 'contact',
}
</script>

<style>

</style>