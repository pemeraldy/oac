<template>
    <div class="w-100 sign-up__wrap bg-secondary">
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <div class="mt-5"></div>
                    <div class="welcom-msg d-flex align-items-center justify-content-center flex-column">
                        <h1 class="text-center">Welcome to DAI Community!</h1>
                        <p class="text-center">You are about to join our community of over a  thousand members, congratulations! 👏</p>
                    </div>
                    <div class="mt-5"></div>
                    <div class="d-flex justify-content-center">
                        <div class="form-wrap bg-white rounded p-4">
                            <SignUpForm />
                        </div>
                    </div>
                </div>
                
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name:'login',
    layout: 'user',
}
</script>

<style scoped>
.sign-up__wrap{
    min-height: 100vh;
}
.welcom-msg p, .welcom-msg h1{
    max-width: 444px ;
}
.form-wrap{
    width: 500px;
    margin-bottom: 40px;
}
</style>