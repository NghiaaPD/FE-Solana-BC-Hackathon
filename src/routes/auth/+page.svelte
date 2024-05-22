<script>
    import LoginForm from "./LoginForm.svelte";
    import BgLogin from "./BgLogin.svelte";
</script>

<div class="relative">
    <div class="absolute inset-0">
        <BgLogin />
    </div>
    <div class="relative z-10">
        <LoginForm />
    </div>
</div>

