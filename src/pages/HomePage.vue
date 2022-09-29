<template>
  <div class="p-3 col-4 shadow rounded ">
    <form action="">
      <label for="">
        <p>Name</p>
        <input type="text" name="" id="" placeholder="Employee Name">
      </label>
      <button class="btn btn-success">submit</button>
    </form>
  </div>
  <div class="d-flex justify-content-evenly pt-3">
    <h1>Employees</h1>
    <h1>Number of Doughnuts</h1>
  </div>
</template>

<script>
export default {
  name: 'Home'
}
</script>

<style scoped lang="scss">
.home{
  display: grid;
  height: 80vh;
  place-content: center;
  text-align: center;
  user-select: none;
  .home-card{
    width: 50vw;
    > img{
      height: 200px;
      max-width: 200px;
      width: 100%;
      object-fit: contain;
      object-position: center;
    }
  }
}
</style>
