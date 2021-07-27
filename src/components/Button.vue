<template>
<div>
    <button :style="{background: color}" class="btn">
        {{text}}
    </button>
</div>
    
</template>

<script>

export default {
        name: 'Button',
        props:{
            text: String,
            color: String
        }
}
</script>