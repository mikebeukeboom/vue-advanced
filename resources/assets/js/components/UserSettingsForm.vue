<template>
    <form class="card" @submit.prevent="submit">
        <h1 class="text-2xl font-bold mb-6">Your Settings</h1>
        <label class="block mb-6">
            <span class="form-label mb-2">Email Address</span>
            <input class="form-input" placeholder="you@example.com">
        </label>
        <div class="mb-8">
            <span class="form-label mb-2">Newsletter</span>
            <div class="flex justify-between item-center">
                <p class="mr-4">Send you occasional news and updates</p>
                <span class="toggle flex-no-shrink"role="checkbox" tabindex="0"></span>
            </div>
        </div>
        <div class="text-right">
            <button class="btn btn-blue">Update Settings</button>
        </div>
    </form>
</template>

<script>
    export default {}
</script>

<style scoped>

</style>