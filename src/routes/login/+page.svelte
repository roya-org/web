<svelte:head>
    <title>Roya | Login</title>
</svelte:head>

<main class="flex items-center justify-center h-dvh">
    <section class="bg-black-800 border-2 border-black-700 rounded-xl w-4/5 p-12">
        <h1 class="text-4xl font-bold text-center">Welcome Back</h1>

        <form class="mt-8 space-y-6">
            <div>
                <label for="email" class="block text-sm font-medium"
                    >Email</label
                >
                <input
                    name="email"
                    id="email"
                    type="email"
                    class="rounded-lg w-full h-10 px-2 border-none outline-none bg-black-700"
                />
            </div>

            <div>
                <label for="password" class="block text-sm font-medium"
                    >Password</label
                >
                <input
                    name="password"
                    id="password"
                    type="password"
                    class="rounded-lg w-full h-10 px-2 border-none outline-none bg-black-700"
                />
            </div>

            <div>
                <button class="text-center w-full h-10 rounded-lg bg-blue"
                    >Continue</button
                >
                <p class="text-center text-sm font-medium mt-2">
                    You don't have an account? <a
                        href="/signup"
                        class="underline">Create one!</a
                    >
                </p>
            </div>
        </form>
    </section>
</main>
