<template>
    <div class="w-100 sign-up__wrap bg-secondary">
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <div class="mt-5"></div>
                    <div class="welcom-msg d-flex align-items-center justify-content-center flex-column">
                        <h1 class="text-center">Reset your password</h1>
                        <p class="text-center">The verification email will be sent to your mailbox. Please check it.</p>
                    </div>
                    <div class="mt-5"></div>
                    <div class="d-flex justify-content-center">
                        <div class="form-wrap bg-white rounded p-5">
                            <ResetPwForm />
                        </div>
                    </div>
                </div>
                
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name:'Signin',
    layout: 'user',
}
</script>

<style scoped>
.sign-up__wrap{
    height: 100vh;
}
.welcom-msg p, .welcom-msg h1{
    max-width: 444px ;
}
.form-wrap{
    width: 500px;
}
</style>