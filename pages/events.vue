<template>
  <div class="">
      <div class="container mt-5">
          <div class="row">
              <div class="col-md-6 col-12">
                  <h2>Awareness Activities</h2>
              </div>
              <div class="col-md-6 col-12 d-md-flex justify-content-md-end ">
                  <button class="btn submit-event btn-primary">Submit your event</button>
              </div>
          </div>
          <div class="row mt-5">
              <div class="col-md-6 mt-3 mt-md-3">
                  <PostCard />
              </div>
              <div class="col-md-6 mt-3 mt-md-3">
                  <PostCard />
              </div>
              <div class="col-md-6 mt-3 mt-md-3">
                  <PostCard />
              </div>
              <div class="col-md-6 mt-3 mt-md-3">
                  <PostCard />
              </div>
          </div>
          <!-- Pagination -->
          <div class="mt-5">
              <div class="row">
                  <div class="col-12 d-flex justify-content-center">
                      <div class="w-25 d-flex justify-content-around">
                            <div class="btn pagination-btn"><i class="fa fa-angle-left"></i></div>
                            <div class="btn pagination-btn">1</div>
                            <div class="btn pagination-btn">3</div>
                            <div class="btn">...</div>
                            <div class="btn pagination-btn">10</div>
                            <div class="btn pagination-btn"><i class="fa fa-angle-right"></i></div>
                      </div>
                  </div>
              </div>
          </div>
      </div>
  </div>
</template>

<script>
export default {
    layout: 'user'
}
</script>

<style scoped>
.submit-event{
    border-radius: 25px;
}
.slide-card{
    width:100% !important;
}
.btn.pagination-btn{
    border: 1px solid #C6CBD4;
    border-radius: 2px;
}
</style>