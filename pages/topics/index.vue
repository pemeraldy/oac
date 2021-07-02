<template>
  <div>
    <div class="container mt-4">
      <div class=" mb-3 d-flex justify-content-between align-items-center">
        <div>
          <nav aria-label="breadcrumb ">
            <ol class="breadcrumb m-0 p-0">
              <li class="breadcrumb-item"><a href="#">Home</a></li>
              <li class="breadcrumb-item active" aria-current="page">Topics</li>
            </ol>
          </nav>
          <h3>Topics</h3>
        </div>
        <div>
          <button class="post-btn__lg btn btn-primary">Create New Topic</button>
        </div>
      </div>
      <div class="row">
        <div class="col-12">
          <div class="d-flex justify-content-end">
            <div class="form-group required">
              <select class="form-control sort-select">
                <option class="webster" value="">Status: Pending</option>
              </select>
            </div>
            <div class="form-group required ml-2">
              <select class="form-control sort-select">
                <option class="webster" value="">Category: All</option>
              </select>
            </div>
          </div>
        </div>
      </div>

      <div class="row">
        <div class="col-12">
          <AppTable />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  layout: "admin"
};
</script>

<style scoped>
.post-btn__lg {
  background: #119859;
  width: 160px;
  height: 42px;
  border-radius: 25px;
}
.breadcrumb {
  background: transparent;
}
.sort-select {
  width: 185px;
  border-radius: 6px;
  height: 40px;
}
</style>
