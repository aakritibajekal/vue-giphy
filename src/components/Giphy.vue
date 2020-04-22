<template>
  <section>
    <h1>GIPHY API App</h1>
    <form action="#" method="GET">
      <div class="field">
        <label class="label">Name</label>
        <div class="control">
          <input class="input" type="text" placeholder="Text input" />
        </div>
      </div>
      <div class="field is-grouped">
        <div class="control">
          <button class="button is-link">Submit</button>
        </div>
        <div class="control">
          <button class="button is-link is-light">Cancel</button>
        </div>
      </div>
    </form>
  </section>
</template>

<script>
export default {
  name: "Giphy"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
