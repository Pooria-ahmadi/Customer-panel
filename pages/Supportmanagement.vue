<template>
    <div style="overflow: hidden;">
        <div class="max-width-1160px mx-auto">
            <!-- for mobile -->
            <div class="columns mx-4 mb-6 pt-4 pb-6 is-hidden-desktop is-hidden-only-tablet">
                <div class="column box py-6 px-5 has-text-centered">
                    <p class="has-text-right">
                        مدیریت شرکت های پشتیبانی
                    </p>

                    <div class="columns mt-6">
                        <div class="column mx-3 mt-3 br-grey has-text-centered py-6 mb-0" v-for="(slide, index) in manage"
                            :key="index">
                            <img :src="slide.image" alt="">
                            <p>
                                {{ slide.caption }}
                            </p>
                        </div>
                    </div>
                    <button class="button p-30 br-15 mt-5">
                        <span class="has-text-centered">
                            <span class="is-block color-8D79D1">افزودن شرکت</span>
                            <img src="icon.png" alt="icon">
                        </span>
                    </button>
                </div>
            </div>
            <!-- for desktop -->
            <div class="columns mx-0 mb-6 pt-4 pb-6 is-hidden-mobile is-hidden-only-tablet">
                <div class="column box py-6 px-5 has-text-centered">
                    <p class="has-text-right">
                        مدیریت شرکت های پشتیبانی
                    </p>

                    <div class="columns mt-6">
                        <div class="column mx-3 br-grey has-text-centered py-6 mb-0" v-for="(slide, index) in manage"
                            :key="index">
                            <img :src="slide.image" alt="">
                            <p>
                                {{ slide.caption }}
                            </p>
                        </div>
                    </div>
                    <button class="button p-30 br-15 mt-5">
                        <span class="has-text-centered">
                            <span class="is-block color-8D79D1">افزودن شرکت</span>
                            <img src="icon.png" alt="icon">
                        </span>
                    </button>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    data() {
        return {
            manage: [
                { image: 'Vector.png', caption: 'شرکت اخوان' },
                { image: 'Vector.png', caption: 'شرکت اخوان' },
                { image: 'Vector.png', caption: 'شرکت اخوان' },
                { image: 'Vector.png', caption: 'شرکت اخوان' },
                { image: 'Vector.png', caption: 'شرکت اخوان' },
            ]
        }
    }
}
</script>
<style>
.br-grey {
    border: 1px solid #d9d9d9;
    border-radius: 10px;

}

.color-8D79D1 {
    color: #8D79D1;
}
</style>