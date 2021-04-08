<script>
  export let title;
  export let image_project;
  export let description;
</script>
<style>
  .bg-color {
  background-color: #00e6b6;
   border: 2px solid #000;
    border-radius: 90px;
}
.bg-transparent{
  background-color: transparent;
   border: 2px solid #000;
    border-radius: 90px;
}
.text-color{
  color: #00e6bb;
  border-bottom: 4px solid white;
  border-left: 4px solid white;
}
</style>
<div class="Project">
  <div class="container">
    <div class="row mb-5">
      <div class="col-12 col-lg-6">
        <img class="img-fluid d-block mx-auto" src="{image_project}" alt="imagen computador y telefono">
      </div>
      <div class="col-12 col-lg-6 my-auto mx-auto">
        <h5 class="bg-dark text-center mb-4 text-color">
          {title}
        </h5>
        <p class="mb-4">{description}</p>
        <div class="buttons-container d-flex flex-column my-3">
          <button class=" text-center bg-transparent mb-3 font-weight-bold">
            <img   src="../assets/icon-github.svg" alt="button ver codigo">
            VER CÓDIGO</button>
          <button class=" text-center bg-color font-weight-bold">VER PROYECTO</button>
        </div>
      </div>
    </div>
  </div>
</div>