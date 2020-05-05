<template>
  <div class="navigation-container">
    <div class="container-fluid link-wrapper">
      <div class="row">
        <div class="col-xl-12 links">
          <router-link :to="{ name: 'Home' }">Home</router-link>
        </div>
        <div class="col-xl-12 links">
          <router-link :to="{ name: 'ManageProfile' }"
            >Manage Profile</router-link
          >
        </div>
        <div class="col-xl-12 links">
          <router-link :to="{ name: 'ManageUsers' }">Manage Users</router-link>
        </div>
        <div class="col-xl-12 links">
          <router-link :to="{ name: 'Home' }">Home</router-link>
        </div>
        <div class="col-xl-12 links">
          <router-link :to="{ name: 'ManageProfile' }"
            >Manage Profile</router-link
          >
        </div>
        <div class="col-xl-12 links">
          <router-link :to="{ name: 'ManageUsers' }">Manage Users</router-link>
        </div>
        <div class="col-xl-12 links">
          <router-link :to="{ name: 'Home' }">Home</router-link>
        </div>
        <div class="col-xl-12 links">
          <router-link :to="{ name: 'ManageProfile' }"
            >Manage Profile</router-link
          >
        </div>
        <div class="col-xl-12 links">
          <router-link :to="{ name: 'ManageUsers' }">Manage Users</router-link>
        </div>
        <div class="col-xl-12 links">
          <router-link :to="{ name: 'Home' }">Home</router-link>
        </div>
        <div class="col-xl-12 links">
          <router-link :to="{ name: 'ManageProfile' }"
            >Manage Profile</router-link
          >
        </div>
        <div class="col-xl-12 links">
          <router-link :to="{ name: 'ManageUsers' }">Manage Users</router-link>
        </div>
        <div class="col-xl-12 links">
          <router-link :to="{ name: 'Home' }">Home</router-link>
        </div>
        <div class="col-xl-12 links">
          <router-link :to="{ name: 'ManageProfile' }"
            >Manage Profile</router-link
          >
        </div>
        <div class="col-xl-12 links">
          <router-link :to="{ name: 'ManageUsers' }">Manage Users</router-link>
        </div>
        <div class="col-xl-12 links">
          <router-link :to="{ name: 'Home' }">Home</router-link>
        </div>
        <div class="col-xl-12 links">
          <router-link :to="{ name: 'ManageProfile' }"
            >Manage Profile</router-link
          >
        </div>
        <div class="col-xl-12 links">
          <router-link :to="{ name: 'ManageUsers' }">Manage Users</router-link>
        </div>
        <div class="col-xl-12 links">
          <router-link :to="{ name: 'Home' }">Home</router-link>
        </div>
        <div class="col-xl-12 links">
          <router-link :to="{ name: 'ManageProfile' }"
            >Manage Profile</router-link
          >
        </div>
        <div class="col-xl-12 links">
          <router-link :to="{ name: 'ManageUsers' }">Manage Users</router-link>
        </div>
        <div class="col-xl-12 links">
          <router-link :to="{ name: 'Home' }">Home</router-link>
        </div>
        <div class="col-xl-12 links">
          <router-link :to="{ name: 'ManageProfile' }"
            >Manage Profile</router-link
          >
        </div>
        <div class="col-xl-12 links">
          <router-link :to="{ name: 'ManageUsers' }">Manage Users</router-link>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'TheNavigation'
}
</script>

<style>
.navigation-container {
  border-radius: 10px;
  width: 100%;
  color: white;
  background-color: lightcoral;
}

.navigation-container a {
  color: black;
  font-size: 13px;
  font-weight: bold;
}
.navigation-container a:hover {
  text-decoration: none;
}
.navigation-container a.router-link-exact-active {
  color: white;
  font-size: 16px;
}
.links {
  margin: 1px 0px;
}
.link-wrapper {
  overflow-y: auto;
  overflow-x: hidden;
}
</style>
