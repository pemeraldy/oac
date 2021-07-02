<template>
  <div>
      <div class="container mt-5">
          <div class="create-post__wrapper">
              <h1 class="heading-sm">Support communities</h1>
              <div class="mt-5">
                  <h1 class="intro">Start a new conversation</h1>
              </div>

              <div class="mt-5">
                  <div class="post-title">
                    <h3 class="title-heading">Title</h3>
                    <div class="form-group required">                    
                        <input type="text" class="form-control p-4" placeholder="Type in your post title here" >
                    </div>
                  </div>
              </div>

              <div class="mt-5">
                  <h3 class="detail-heading">Details</h3>
                  <div>
                      <TextEditor />
                  </div>
              </div>
          </div>
      </div>
  </div>
</template>

<script>
export default {
    layout: 'user',
    
}
</script>

<style scoped>
    .create-post__wrapper{
        /* padding-left: 168px;
        padding-right:168px ; */
    }
    .heading-sm{    
        font-weight: 500;
        font-size: 26px;
    }
    .intro, .title-heading{
        font-family: Merriweather;
    }
    @media screen and (max-width: 500px) {
        .create-post__wrapper{
            padding-left: 20px;
            padding-right:20px ;
        }
        .heading-sm{
            font-size: 16px;
        }
        .intro{
            font-size: 28px;
        }
        .title-heading{
            font-size: 24px;
        }
        .detail-heading{
            font-family: Merriweather;
        }
    }
</style>