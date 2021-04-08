<script>
  export let image_profile;
  export let comment;
  export let source_text;
</script>
<style>
  .comment-row{
  border-top: 2px solid #ffe2d3;
  border-left: 2px solid #ffe2d3;
  border-radius: 24px;
  background-color: rgba(255,255,255,0.2);
  
  }
</style>
<div class="Comment">
  <div class="container">
    <div class="row mx-auto my-5 comment-row p-3">
      <div class="col-12 text-center">
        <img class="p-3"src="{image_profile}" alt="imagen persona">
      </div>
      <div class="col-12">
        <p class="d-block mx-auto font-weight-bold">{comment}</p>
        <small class="d-block mx-auto">{source_text}</small>
      </div>
    </div>
  </div>
</div>