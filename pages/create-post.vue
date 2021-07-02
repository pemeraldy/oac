<template>
  <div>
    <div class="container mt-5 pb-4">
      <div class="create-post__wrapper">
        <h1 class="heading-sm">Support communities</h1>
        <div class="mt-5">
          <h1 class="intro">Start a new conversation</h1>
        </div>

        <form>
          <div class="mt-5">
            <div class="post-title">
              <h3 class="title-heading">Title</h3>
              <div class="form-group required">
                <input
                  type="text"
                  class="form-control p-4"
                  placeholder="Type in your post title here"
                />
              </div>
            </div>
          </div>

          <div class="mt-5">
            <h3 class="detail-heading">Details</h3>
            <div>
              <TextEditor />
            </div>
            <div class="row mt-5">
              <div class="col-md-3 col-12">
                <div class="form-group">
                  <label for="categories">Category</label>
                  <select id="categories" class="form-control">
                    <option value="">Select Category</option>
                  </select>
                </div>
              </div>
              <div class="col-md-5 col-12">
                <div class="form-group">
                  <label for="categories">Category</label>
                  <input type="text" placeholder="Add tags" class="form-control">
                </div>
              </div>
              <div class="col-md-4 col-12 d-flex align-items-center">
                  <div>
                      <button class="btn post-disc-btn btn-primary mt-md-3">Post discussion</button>
                  </div>
              </div>
            </div>
          </div>
        </form>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  layout: "user"
};
</script>

<style scoped>
.create-post__wrapper {
  /* padding-left: 168px;
        padding-right:168px ; */
}
.heading-sm {
  font-weight: 500;
  font-size: 26px;
}
.intro,
.title-heading {
  font-family: Merriweather;
}
@media screen and (max-width: 500px) {
  .create-post__wrapper {
    padding-left: 20px;
    padding-right: 20px;
  }
  .heading-sm {
    font-size: 16px;
  }
  .intro {
    font-size: 28px;
  }
  .title-heading {
    font-size: 24px;
  }
  .detail-heading {
    font-family: Merriweather;
  }
}
.ql-toolbar.ql-snow {
  border-top-left-radius: 8px !important;
  border-top-right-radius: 8px !important;
}
.ql-editor {
  height: 500px !important;
}
.btn.post-disc-btn.btn-primary{
    border-radius: 25px;
}
</style>
