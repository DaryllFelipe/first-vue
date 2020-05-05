<template>
  <div class="profile">
    <div class="profile-image">
      <img src="../assets/businessman-profile-cartoon_18591-58479.jpg" />
    </div>
    <div class="name">
      {{ employee }}
    </div>
    <div class="position">
      {{ position }}
    </div>
  </div>
</template>

<script>
export default {
  name: 'TheProfile',
  data() {
    return {
      employee: 'Juan Dela Cruz',
      position: 'General Manager'
    }
  }
}
</script>

<style>
.profile {
  border-radius: 10px;
  height: inherit;
  text-align: center;
}
.profile img {
  width: 70px;
  padding-top: 10px;
}
.name {
  padding-top: 10px;
  color: black;
  font-weight: bold;
  font-size: 16px;
}
.position {
  color: black;
  font-weight: bold;
  font-size: 16px;
}
</style>
