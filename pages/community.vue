<template>
  <div>
      <div class="container mt-5">
          <div class="comm-heading">
              <h1>Support Communities</h1>
          </div>
          <div class="row">
              <div class="col-md-10 col-12">
                  <div class="d-flex w-100 flex-col flex-column flex-md-row align-items-center">
                      <div class="total-topics btn btn-primary d-flex justify-content-center align-items-center">290 topics</div>
                        <div class="topic-tabs ml-md-auto">
                            <nav class="nav nav-pills flex-column flex-sm-row">
                                <a class="flex-sm-fill text-sm-center mx-3 nav-link text-center active" href="#">TRENDING</a>
                                <a class="flex-sm-fill text-sm-center mx-3 nav-link text-center text-muted" href="#">A - Z</a>
                                <a class="flex-sm-fill text-sm-center mx-3 nav-link text-center text-muted" href="#">BY TOPIC</a>
                                <a class="flex-sm-fill text-sm-center mx-3 nav-link text-center text-muted" href="#">OTHERS</a>
                            </nav>
                        </div>
                  </div>
              </div>
          </div>
          <div class="row mt-4">
              <div class="col-md-10 col-12">
                  <form class="form">
                      <div class="form-group required">                        
                        <input type="text" class="form-control p-4" placeholder="Search community here..." >
                    </div>
                  </form>
                    
                  <div class="rounded w-100 bg-secondary mt-3 create-discussion p-4">
                      <div class="d-flex flex-column align-items-center justif flex-md-row">
                          <p class="m-0">Can’t find what you’re looking for?</p>
                          <div class="btn btn-primary ml-md-3">Create a new discussion</div>
                      </div>
                  </div>

                  <!-- list of trendings -->
                  <div class="mt-5">
                      <div class="topics">
                          
                          <div class="row lists-of-trend">                            
                            <div class="col-md-6 col-12 mt-3">
                                <h3>Diabetes</h3>
                                <ul class="list-group pl-md-0">
                                    <nuxt-link to="/" class="list-group-item">Diabetes (Español)</nuxt-link>
                                    <nuxt-link to="/" class="list-group-item">Diabetes - Gestational</nuxt-link>
                                    <nuxt-link to="/" class="list-group-item">Diabetes - Type 1</nuxt-link>
                                    <nuxt-link to="/" class="list-group-item">Diabetes - Type 2</nuxt-link>                                
                                </ul>
                            </div>
                            <div class="col-md-6 col-12 mt-3">
                                <h3>Diabetes</h3>
                                <ul class="list-group pl-md-0">
                                    <nuxt-link to="/" class="list-group-item">Diabetes (Español)</nuxt-link>
                                    <nuxt-link to="/" class="list-group-item">Diabetes - Gestational</nuxt-link>
                                    <nuxt-link to="/" class="list-group-item">Diabetes - Type 1</nuxt-link>
                                    <nuxt-link to="/" class="list-group-item">Diabetes - Type 2</nuxt-link>                                
                                </ul>
                            </div>
                            <div class="col-md-6 col-12 mt-3">
                                <h3>Pregnancy</h3>
                                <ul class="list-group pl-md-0">
                                    <nuxt-link to="/" class="list-group-item">DNA/Fertility</nuxt-link>
                                    <nuxt-link to="/" class="list-group-item">Pregnancy</nuxt-link>                                                                   
                                </ul>
                            </div>
                            <div class="col-md-6 col-12 mt-3">
                                <h3>Pregnancy</h3>
                                <ul class="list-group pl-md-0">
                                    <nuxt-link to="/" class="list-group-item">DNA/Fertility</nuxt-link>
                                    <nuxt-link to="/" class="list-group-item">Pregnancy</nuxt-link>                                                                   
                                </ul>
                            </div>
                          </div>
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

<style lang="scss" scoped>
.comm-heading{
    font-size: 26px;
    font-weight: 500;
}
.total-topics.btn{
    border-radius: 90px;
    width: 102px;
    height:26px;
}
.list-group-item{
    padding:0;
    border: 0;
    color: rgba(59, 140, 215, 1);
}
.nav.nav-pills a{
    background: transparent;
    &.active{
        border-bottom: 2px solid #119859;
        border-radius: 0;
        color: #119859
    }
}

</style>