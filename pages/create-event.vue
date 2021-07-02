<template>
  <div>
    <div class="container mt-5 pb-5">
      <div class="row">
        <div class="col-12">
          <h3 class="">Add New Event</h3>
          <h1 class="heading mt-md-4">Tell us about your event</h1>
        </div>
      </div>
      <div class="mt-3">
        <div class="row">
          <div class="col-12">
            <form>
              <div class="row">
                <div class="col-md-6 col-12 form-group">
                  <label for="">Title</label>
                  <input
                    type="text"
                    class="form-control"
                    placeholder="Type in your event title here"
                  />
                </div>
                <div class="col-md-6 col-12 form-group">
                  <label for="">Event date</label>
                  <input
                    type="text"
                    class="form-control"
                    placeholder="Enter your event date here"
                  />
                </div>
                <div class="col-md-6 col-12 form-group">
                  <label for="">Start time</label>
                  <input
                    type="text"
                    class="form-control"
                    placeholder="Enter your event date here"
                  />
                </div>
                <div class="col-md-6 col-12 form-group">
                  <label for="">End time</label>
                  <input
                    type="text"
                    class="form-control"
                    placeholder="Enter your event date here"
                  />
                </div>
                <div class="col-md-6 col-12 form-group">
                  <label for="">Your organization</label>
                  <input
                    type="text"
                    class="form-control"
                    placeholder="Enter your event date here"
                  />
                </div>
                <div class="col-md-6 col-12 form-group">
                  <label for="">Category</label>
                  <select class="form-control">
                    <option value="">Select category</option>
                  </select>
                </div>
                <div class="col-md-6 col-12 form-group">
                  <label for="">Your Name</label>
                  <input
                    type="text"
                    class="form-control"
                    placeholder="Enter your name"
                  />
                </div>
                <div class="col-md-6 col-12 form-group">
                  <label for="">Your Email</label>
                  <input
                    type="email"
                    class="form-control"
                    placeholder="Enter your email"
                  />
                </div>
                <div class="col-md-12 col-12 form-group">
                  <label for="">Event description</label>
                  <textarea class="form-control" id="description" rows="4"></textarea>
                </div>

                <div class="col-md-6 col-12 form-group">
                  <label for="">Website Information</label>
                  <input
                    type="web"
                    class="form-control"
                    placeholder="Enter website address here"
                  />
                </div>
                <div class="col-md-6 col-12 form-group">
                  <label for="">Contact for more information</label>
                  <input
                    type="web"
                    class="form-control"
                    placeholder="Enter your contact information here"
                  />
                </div>

                <div class="col-md-12 col-12 form-group">
                  <label for="">Event banner</label>
                  <div class="banner-select form-control flex-column d-flex justify-content-center align-items-center">
                      <div class="add-img">
                          <img src="~/assets/images/icons/add-image-icon.png" alt="add">
                      </div>
                      <p class="mt-2 mb-0">Add event attachment</p>
                  </div>
                </div>
                <div class="col-md-12 d-md-flex justify-content-end">
                    <button class="btn-primary btn submit-event">Submit Event</button>
                </div>
              </div>
            </form>
          </div>
        </div>
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
.heading {
  font-family: Merriweather;
  font-weight: 600;
  font-size: 40px;
}
.banner-select{
    width: 100%;
    height: 130px;
}
.submit-event{
    border-radius: 25px;
}
.add-img{
    cursor: pointer;
}
</style>
