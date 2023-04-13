<script setup>
import AppLayout from '@/Layouts/AppLayout.vue';

defineProps({
    list: Array[Number]
});


</script>

<template>
    <AppLayout title="Список">
        <template #header>
            <h2 class="font-semibold text-xl text-gray-800 leading-tight">
                Список желаний
            </h2>
        </template>

        <div class="py-12">
            <div class="max-w-7xl mx-auto sm:px-6 lg:px-8">
                <div class="bg-white overflow-hidden shadow-xl sm:rounded-lg">
                    <template v-for="item in list">{{item}}-</template>
                </div>
            </div>
        </div>
    </AppLayout>
</template>
