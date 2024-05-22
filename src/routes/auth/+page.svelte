<script>
    import { Icon } from 'svelte-icons-pack';
    import { FaBrandsGoogle } from "svelte-icons-pack/fa";
    import { AiFillGithub } from "svelte-icons-pack/ai";
</script>

<div class="flex items-center justify-center h-screen">
    <div class="h-[500px] w-[450px] rounded-xl border-2 border-[#D4163C] bg-[#0C0A09] bg-opacity-50">
        <div class="flex-col p-5 ">
            <h1 class="text-2xl font-black text-white">
                Sign In to your account
            </h1>
            <p class="text-white">Enter your email below to login your account</p>
            <div class="flex mt-8">
                <a href="/" class="btn variant-filled rounded-lg w-[200px] hover:bg-[#D4163C] hover:text-white">
                    <Icon src={FaBrandsGoogle} />
                    <span>Google</span>
                </a>
                <a href="/" class="btn variant-filled rounded-lg w-[200px] ml-6 hover:bg-[#D4163C] hover:text-white">
                    <Icon src={AiFillGithub} />
                    <span>Github</span>
                </a>
            </div>
            <div class="mt-8 relative flex items-center justify-center">
                <p class="relative bg-[#101014] px-2 z-10 text-[#949494]">OR CONTINUE WITH</p>
                <div class="w-full h-[2px] bg-[#949494] rounded-full absolute top-1/2 transform -translate-y-1/2"></div>
            </div>
            <div class="flex-col mt-6">
                <label class="label">
                    <span class="ml-1 text-lg font-bold">Username</span>
                    <input class="input rounded-lg" type="text" placeholder="Enter your email or username" />
                </label>
                <label class="label mt-5">
                    <span class="ml-1 text-lg font-bold">Password</span>
                    <input class="input rounded-lg" type="text" placeholder="Enter your password" />
                </label>
                <button type="button" class="btn mt-8 w-full rounded-lg bg-[#D4163C] text-white font-semibold ">Button</button>
            </div>

        </div>
    </div>
</div>
