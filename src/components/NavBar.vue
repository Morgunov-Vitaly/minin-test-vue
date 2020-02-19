<template>
      <nav class="purple darken-2">
      <div class="nav-wrapper">
        <router-link to="/" class="brand-logo">Task manager</router-link>
        <ul id="nav-mobile" class="right hide-on-med-and-down">
          
            <router-link 
                tag="li"
                to="/"
                exact
                class='link' 
            >Create</router-link>
            <router-link
                tag="li"
                to="/list"
                class='link' 
            >List</router-link>
            <router-link
                tag="li"
                to="/task/id"
                class='link' 
            >Task</router-link>
          
        </ul>
      </div>
    </nav>
</template>

<script>
export default {

}
</script>

<style scoped>
.nav-wrapper{
    padding: 0;
    max-width: 70%;
    margin: auto;
}
.link{
    padding: 0 20px;
    cursor: pointer;
}
</style>