<template>
  <div class="top">
    <ul>
      <li>
        <form>
          <span>
            <input class="txtsearch" type="text" name="txtsearch" />
          </span>
          <span class="formSearch">
            <button name="btnsearch" type="submit">
              <img class="searchIcon" src="../assets/search.png" />
            </button>
          </span>
        </form>
      </li>
      <li>
        <div>
          <img class="homeIcon" src="../assets/home.png" />
        </div>
      </li>
      <li>
        <div>
          <span><img class="notifIcon" src="../assets/notif.png"/></span>
        </div>
      </li>
      <li>
        <div>
          <span><img class="profileIcon" src="../assets/profile.jpg"/></span>
        </div>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'TheTopBar'
}
</script>

<style>
.top {
  padding: 10px 15px;
  text-align: right;
}
.formSearch {
  margin-left: -20px;
}

.searchIcon {
  width: 20px;
}
.homeIcon {
  margin-bottom: 1px;
  width: 25px;
}
.notifIcon {
  margin-bottom: 1px;
  width: 22.5px;
}
.profileIcon {
  margin-bottom: 1px;
  width: 30px;
  height: 26px;
}
.top li {
  list-style: none;
  display: inline-block;
  padding-right: 10px;
}
</style>
