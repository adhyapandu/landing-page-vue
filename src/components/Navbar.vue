<template>
    <div>
          <div>
  <b-navbar toggleable="lg" type="dark" variant="info" style="padding-top:2%;" >
    <font-awesome-icon icon="cloud" style="color:white; font-size:135%; margin-right:6px;"/>
    <b-navbar-brand href="#">CLOUDBUDGET</b-navbar-brand>
    <div style="float: none; position: absolute; left: 25%; right: 25%;" >
      <b-navbar-brand href="#" >Overview</b-navbar-brand>
      <b-navbar-brand href="#" >Features</b-navbar-brand>
      <b-navbar-brand href="#" >Technology</b-navbar-brand>
      <b-navbar-brand href="#" >Contact</b-navbar-brand>
      <b-navbar-brand href="#" >Sign Up</b-navbar-brand>
    </div>
    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">

        <b-nav-item-dropdown text="EN" right>
          <b-dropdown-item href="#">EN</b-dropdown-item>
          <b-dropdown-item href="#">ES</b-dropdown-item>
          <b-dropdown-item href="#">RU</b-dropdown-item>
          <b-dropdown-item href="#">FA</b-dropdown-item>
        </b-nav-item-dropdown>

        <b-nav-item-dropdown right>
          <!-- Using 'button-content' slot -->
          <template #button-content>
            <em>User</em>
          </template>
          <b-dropdown-item href="#">Profile</b-dropdown-item>
          <b-dropdown-item href="#">Sign Out</b-dropdown-item>
        </b-nav-item-dropdown>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</div>
      </div>
</template>

<script>
export default {
    name: 'Navbar',
}
</script>

<style>

</style>