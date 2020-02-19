<template>
  <div class="wrapper">
    <h1>Create</h1>
    <div class="row">
      <form class="col s12 l6 offset-l3">

          <div class="input-field ">
            <input placeholder="Write here" id="title" type="text" class="validate" required/>
            <label for="title">Title</label>
          </div>
          <div class="chips" ref="chips"></div>

      </form>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
export default {
  name: 'create',
  mounted(){
    M.Chips.init(this.$refs.chips, {placeholder:'Task tags'});
  }
};
</script>
