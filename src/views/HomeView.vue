<script>
import NavItem from "../components/Nav.vue";
export default {
  name: "HomeView",
  components: {
    NavItem,
  },
  
};
</script>

<template>
  <NavItem />
  <h5 >Rejeki lancar dengan melakukan donasi kepada mereka yang membutuhkan</h5>
  <div class="row">
  <div class="col-md-4 my-3" style="width: 18rem;">
    <img src="../assets/images.jpg" class="card-img-top" alt="...">
    <div class="card-body">
      <h5 class="card-title">Masjid Alhuda</h5>
      <p class="card-text">Masjid ini sangat perlu direhab pada bagian atap, plafon, dan sekeliling masjid.</p>
      <a href="#" class="btn btn-danger mx-4" >Delete</a>
      <a href="#" class="btn btn-primary">Donate</a>
    </div>
  </div>
  <div class="col-md-4 my-3" style="width: 18rem;">
    <img src="../assets/masjid2.jpg" class="card-img-top" alt="...">
    <div class="card-body">
      <h5 class="card-title">Masjid Ar-Rahim</h5>
      <p class="card-text">Masjid perlu dana untuk melanjutkan pembangunan demi kenyamanan dalam beribadah.</p>
      <a href="#" class="btn btn-danger mx-4" >Delete</a>
      <a href="#" class="btn btn-primary">Donate</a>
    </div>
  </div>
  <div class="col-md-4 my-3" style="width: 18rem;">
    <img src="../assets/masjid3.jpg" class="card-img-top" alt="...">
    <div class="card-body">
      <h5 class="card-title">Masjid Al-muttaqin</h5>
      <p class="card-text">Masjid ini mulai rusak akibat hujan badai sehingga perlu direhab 100%.</p>
      <a href="#" class="btn btn-danger mx-4" >Delete</a>
      <a href="#" class="btn btn-primary">Donate</a>
    </div>
  </div>
  </div>
</template>


<style scoped>

</style>