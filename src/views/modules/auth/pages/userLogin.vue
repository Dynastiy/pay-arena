<template>
    <div>
        <div>
            <div>
                <div class="text-center pt-5">
                    <img src="@/assets/img/logo.png" width="200" alt="">
                </div>
                <div class="login--container">
                    <div class="login--content">
                    <div class="left--side">
                        <h3 class="text-white mb-3">Don't have an account? Register here.</h3>
                        <p style="color:var(--gray-200)">Login to follow a simple, nimble, easy-to-adopt and cost-effective way of carrying out identity and educational verification services.</p>
                        <div class="mt-4">
                            <button>Get Started</button>
                        </div>
                    </div>
                    <div class="right--side">
                        <div>
                            <h2 class="mb-2">Sign in</h2>
                            <p>Login with email address</p>
                        </div>
                        <form action="" class="mt-4">
                            <div class="mb-4">
                                <input type="text" placeholder="email">
                            </div>
                            <div class="mb-4 password-field">
                                <input :type=' visible ? "password" : "text" ' placeholder="password">
                                <span class="material-icons" @click="visible = !visible" role="button" style="color:var(--gray-400)">
                                    {{ visible ? 'visibility' : 'visibility_off' }}
                                </span>
                            </div>
                            <div class="mb-3">
                                <button>Submit</button>
                            </div>
                            <div>
                                <small>Having trouble logging in? Reset your password <a href="#">here</a></small>
                            </div>
                        </form>
                    </div>
                </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    data(){
        return {
            visible: false
        }
    }
}
</script>