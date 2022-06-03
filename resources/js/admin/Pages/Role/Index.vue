<script setup>
import BreezeAuthenticatedLayout from '@/Layouts/Authenticated.vue';
import Container from '@/Components/Container.vue';
import Card from '@/Components/Card.vue';
import { Head } from '@inertiajs/inertia-vue3';
</script>

<template>
    <Head title="Roles" />

    <BreezeAuthenticatedLayout>
        <template #header>
            <h2 class="font-semibold text-xl text-gray-800 leading-tight">
                Roles
            </h2>
        </template>

            <Container>
                <Card>
                    <div class="p-6">
                        Roles
                    </div>
                </Card>
            </Container>
    </BreezeAuthenticatedLayout>
</template>
