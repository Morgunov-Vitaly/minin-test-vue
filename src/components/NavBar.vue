<template>
      <nav class="purple darken-2">
      <div class="nav-wrapper">
        <router-link to="/" class="brand-logo">Task manager</router-link>
        <ul id="nav-mobile" class="right hide-on-med-and-down">
          
            <router-link 
                tag="li"
                to="/"
                exact 
                active-class="active">
                <a href="#">Create</a>
            </router-link>
            <router-link
                tag="li"
                to="/List"
                exact
                 active-class="active">
                <a href="/List">List</a>
            </router-link>
            <router-link
                tag="li"
                to="/link3"
                exact
                 active-class="active">
                <a href="/link3">Link 3</a>
            </router-link>
          
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
</style>