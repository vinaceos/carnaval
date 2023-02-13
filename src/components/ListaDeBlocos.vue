<template>
    <div>
        {{ myJson }}
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import json from '../assets/blocos.json'

export default defineComponent({
    name: 'ListaDeBlocos',
    data(){
        return{
            myJson: json
        }
    }
})

</script>
