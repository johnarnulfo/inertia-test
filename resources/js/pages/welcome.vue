<template>
    <div class="text-white p-10 m-10 rounded border">
        <h1>Hello World</h1>
        <p>{{ name }}</p>

        <input type="text" name="name" id="name" class="w-full border rounded p-2">
    </div>
</template>

<script>
    export default {
        props: {
            name: String,
        },
    };
</script>
