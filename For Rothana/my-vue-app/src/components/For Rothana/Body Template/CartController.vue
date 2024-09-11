<template >
    <div class="bg-emerald-400">
        <!-- Header controller -->
        <div>
            <!-- Title + button view more -->
            <div class="flex justify-between items-center bg-blue-400">
                <!-- Title -->
                <div>
                    <h1 class="text-2xl font-bold">Top Sale</h1>
                    <h2>Dell top sales.</h2>
                </div>
                <!-- Button View more -->
                <div>
                    <button class="py-3 px-4 bg-green-500 font-bold rounded-md text-white">View More</button>
                </div>
            </div>
        </div>
        <!-- All need cart -->
        <div>
            <!-- Cart right here -->
            <CartDetail></CartDetail>
        </div>
    </div>
</template>
<script setup>
import CartDetail from './CartDetail.vue';

</script>