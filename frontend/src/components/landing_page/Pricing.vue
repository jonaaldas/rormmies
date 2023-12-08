<template>
    <section class="py-8 lg:py-20" id="pricing">
        <div class="container">
            <div class="text-center">
                <h2 class="text-4xl font-semibold">🐣 Early Bird Special</h2>
                <p class="mt-2 text-lg">The first 5 families will ...</p>
            </div>
            <div class="mt-8 grid justify-center">
                <div class="card border border-base-content/10 p-3 shadow-sm max-w-sm">
                    <div class="card bg-base-200 p-6 text-base-content">
                        <h3 class="text-xl font-semibold">Early Bird</h3>
                        <p class="mt-2 flex items-baseline">
                            <span class="text-5xl font-bold tracking-tight line-through">{{ pricing.regular }}</span>
                            <span class="ml-1 text-xl font-semibold mr-4">/year</span>

                            <span class="text-5xl font-bold tracking-tight">{{ pricing.earlyBird }}</span>
                            <span class="ml-1 text-xl font-semibold">/year</span>
                        </p>
                        <p class="mt-4">Experience essential features at no cost, setting the foundation for your business growth.</p>
                    </div>
                    <div class="p-6">
                        <ul class="list-inside list-disc space-y-3 text-base-content" role="list">
                            <li>
                                <span class="ms-3">For Personal Use</span>
                            </li>
                            <li>
                                <span class="ms-3">20 products</span>
                            </li>
                            <li>
                                <span class="ms-3">Limited Integrations</span>
                            </li>
                        </ul>
                    </div>
                    <button class="btn btn-outline btn-primary btn-block mt-auto">Get it Now</button>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
    export default {
        data() {
            return {
                period: 'annual',
                pricing: {
                    regular: '$100',
                    earlyBird: '$25',
                },
            };
        },
    };
</script>

<style></style>
