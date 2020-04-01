<template>
    <img 
        :src="data.url"
        :alt="data.desc"
    />
</template>

<script>
export default {
    name: 'image',
    props: [
        'data'
    ]
}
</script>