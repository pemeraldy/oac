<template>
  <div class="pb-5">
    <div class="container mt-5">
      <nav aria-label="breadcrumb">
        <ol class="breadcrumb bg-white">
          <li class="breadcrumb-item"><a href="#">COMMUNITY</a></li>
          <li class="breadcrumb-item"><a href="#">MENTAL HEALTH</a></li>
          <li class="breadcrumb-item active" aria-current="page">
            <a href="">ANXIEY DISORDER</a>
          </li>
        </ol>
      </nav>

      <div class="topic-detail__wrap p-2 p-md-4 ">
        <h1 class="topic-heading">
          Scared help!! Severe anxiety and arms and legs feel tired/weak
        </h1>
        <div class="my-4">
          <img
            class="topic-img"
            src="~/assets/images/icons/topic-icon.png"
            alt="topic img"
          />
          <span class="webster topic-img__text ml-2">Soanxious</span>
        </div>
        <p class="webster topic-content">
          Does anyone feel weak like tired muscles in the legs and arms with
          anxiety and have no energy. I also have burning feeling in arms
          sometimes. I know I'm tense but 8n still panic. I have had severe
          anxiety for the last 3 months and it's scaring me alot. I juat eant to
          feel normal again. I feel like I'm not myself at all like I'm just in
          a daze all the time.
        </p>

        <div
          class="my-3 extras d-flex justify-content-start align-items-center"
        >
          <span class="badge badge-pill webster green-pill p-2"
            >230 Replies</span
          >
          <span class="badge badge-pill webster green-pill p-2 ml-2"
            >June 12, 2021</span
          >
          <span class="badge badge-pill webster red-pill p-2 ml-2">
            <i class="fa fa-flag text-danger"></i> Flag post</span
          >
        </div>
      </div>

      <div class="my-5">
        <div class="d-flex align-items-center">
          <img src="~/assets/images/icons/profile-pic.png" alt="user" />
          <span class="webster ml-2 username">Techymunched</span>
        </div>
      </div>
      <div>
        <form>
          <TextEditor />
          <div
            class="mt-3 d-flex justify-content-center justify-content-md-end align-items-center"
          >
            <button class="btn btn-primary reply-btn">Post reply</button>
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

<style>
.reply-btn {
  border-radius: 25px;
  width: 208px;
  height: 48px;
  line-height: 33px;
}
.username {
  font-weight: 700;
  font-size: 18px;
}
.breadcrumb .breadcrumb-item a {
  color: #3b8cd7 !important;
}
.topic-detail__wrap {
  background: #f7f7fa;
  border-radius: 16px;
}
.topic-heading {
  font-family: Merriweather;
  font-size: 48px;
  font-style: normal;
  font-weight: 700;
  line-height: 60px;
  letter-spacing: -0.04em;
  text-align: left;
}
.topic-img {
  width: 50px;
  height: 50px;
}
.topic-img__text {
  font-size: 18px;
  font-weight: 700;
}
.topic-content {
  font-weight: 400;
  font-size: 18px;
}
.green-pill {
  background: #1198592c;
  width: 100px;
  height: 35px;
  line-height: 17px;
}
.red-pill {
  background: #eb575738;
  width: 100px;
  height: 35px;
  line-height: 17px;
}

@media screen and (max-width: 500px) {
    .topic-heading{
        line-height: 36px;
        font-size: 32px;
    }
}
</style>
