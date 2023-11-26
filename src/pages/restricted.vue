<script setup lang="ts">
import { useAuthStore} from '@/stores/auth';

const auth = useAuthStore();
</script>

<template>
    <div v-if="auth.username `!=` ''">
        Lorem ipsum dolor sit amet consectetur adipisicing 
        elit. Magnam deserunt quo sapiente quidem eos vero 
        delectus dolorum dolorem distinctio, officia animi, 
        nihil odit inventore ullam repudiandae enim! Quidem,
         voluptatibus libero?
    </div>
    <div v-else>
        Please login first to see the content
    </div>
</template>
