<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <ul>
      <li>
        <router-link
            :to="{ name: 'Post', params: {id: 1, title: 'My 1st post' } }"
        >
          First Post
        </router-link>
      </li>
      <li>
        <router-link
            :to="{ name: 'Post', params: {id: 2, title: 'My 2nd post' } }"
        >
          Second Post
        </router-link>
      </li>
      <li>
        <router-link
            :to="{ name: 'Post', params: {id: 3, title: 'My 3rd post' } }"
        >
          Third Post
        </router-link>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Home',

}
</script>

<style>
ul {
  list-style: none;
  padding: 0;
}
</style>
