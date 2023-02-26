<template>
    <div>
        <div> This is Main Page</div>
        <Counter />
        <div>
            x: {{ x }}
            y: {{ y }}
        </div>
    </div>
</template>



<script setup>
const {x, y} = useMouse()
</script>