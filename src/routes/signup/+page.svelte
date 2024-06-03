<svelte:head>
    <title>Roya | Signup</title>
</svelte:head>

<main class="flex items-center justify-center h-dvh">
    <section class="bg-slate rounded-xl w-4/5 h-fit p-12">
        <h1 class="text-3xl font-bold text-center">Create an account</h1>

        <form class="mt-8 space-y-4">
            <div>
                <label for="display-name" class="block text-sm font-medium"
                    >Display Name</label
                >
                <input
                    name="display-name"
                    id="display-name"
                    type="text"
                    class="rounded-lg w-full h-10 px-2 border-none outline-none bg-deepslate"
                />
            </div>

            <div>
                <label for="username" class="block text-sm font-medium"
                    >Username</label
                >
                <input
                    name="username"
                    id="username"
                    type="text"
                    class="rounded-lg w-full h-10 px-2 border-none outline-none bg-deepslate"
                />
            </div>

            <div>
                <label for="email" class="block text-sm font-medium"
                    >Email</label
                >
                <input
                    name="email"
                    id="email"
                    type="email"
                    class="rounded-lg w-full h-10 px-2 border-none outline-none bg-deepslate"
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
                    class="rounded-lg w-full h-10 px-2 border-none outline-none bg-deepslate"
                />
            </div>

            <div>
                <button class="text-center w-full h-10 rounded-lg bg-blue"
                    >Continue</button
                >
                <p class="text-center text-sm font-medium mt-2">
                    Already created an account? <a
                        href="/login"
                        class="underline">Use it!</a
                    >
                </p>
            </div>
        </form>
    </section>
</main>
