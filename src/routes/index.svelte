<script lang="ts">
    import Logo from '$lib/Logo/Logo.svelte';
</script>

<main>
    <div class="flex flex-row content-evenly justify-evenly">
        <div class="flex flex-col w-1/2">
            <h1>SvelteKit</h1>
            <a href="https://kit.svelte.dev">Documentation</a>
        </div>
        <div class="flex flex-col w-1/2">
            <h1>Tailwind</h1>
            <a href="tailwindcss.com/docs/">Documentation</a>
        </div>
    </div>
    <div class="flex flex-row content-evenly justify-evenly">
        <div class="flex flex-col w-1/2 text-center items-center">
            <Logo name="svelte"/>
        </div>
        <div class="flex flex-col w-1/2 items-center justify-center">
            <Logo name="tailwind"/>
        </div>
    </div>
</main>

<style lang="postcss">
    main{
        @apply flex flex-col h-full justify-center;
    }
    h1{
        @apply text-4xl text-center;
    }
    a{
        @apply text-center p-4;
    }
</style>