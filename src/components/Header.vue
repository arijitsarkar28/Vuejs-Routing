<template>
  <ul class="nav nav-pills">
    <!-- <li class="nav-item"><router-link to="/">Home</router-link></li>
    <li class="nav-item"><router-link to="/user">User</router-link></li> -->
    <router-link to="/" tag="li" active-class="active" exact><a>Home</a></router-link>
    <router-link to="/user" tag="li" active-class="active"><a>user</a></router-link>

  </ul>
</template>