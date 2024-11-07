<template>
    <div style="overflow: hidden;">
        <div class="max-width-1160px mx-auto">
            <div class="columns mx-0 mb-6 pt-4 pb-6">
                <div class="column box py-6">
                    <p>
                        مدیریت آلارم ها
                    </p>
                    <div class="columns my-5">
                        <!-- all box -->
                        <div class="column  mx-4 has-background-danger-light br-red-10" >
                            <!-- in box -->
                            <div class="columns py-2">
                                <div class="column has-text-centered is-1">
                                    <img src="icons8-alarm-24.png" class="has-background-danger p-1 box" alt="">
                                </div>
                                <div class="column mt-2">
                                    <p>
                                        پیغام هشدار!
                                    </p>
                                    <p>
                                        لورم ایپسورم متن ساختگی با تولید ...
                                    </p>
                                </div>
                                <div class="column has-text-left is-1">
                                    <img src="icons8-edit-24.png" alt="">
                                </div>
                            </div>
                        </div>

                        <div class="column has-background-info-light mx-4" style="border: 1px solid #4b78ff;
  border-radius: 10px;">
                            <!-- in box -->
                            <div class="columns py-2">
                                <div class="column has-text-centered is-1">
                                    <img src="icons8-alarm-24.png" class="p-1 box has-background-info" alt="">
                                </div>
                                <div class="column mt-2">
                                    <p>
                                        پیغام هشدار!
                                    </p>
                                    <p>
                                        لورم ایپسورم متن ساختگی با تولید ...
                                    </p>
                                </div>
                                <div class="column has-text-left is-1">
                                    <img src="icons8-edit-24.png" alt="">
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="columns mb-5">
                        <!-- all box -->
                        <div class="column mx-4 has-background-success-light" style="border: 1px solid rgb(75, 255, 145);
  border-radius: 10px;">
                            <!-- in box -->
                            <div class="columns py-2">
                                <div class="column has-text-centered is-1">
                                    <img src="icons8-alarm-24.png" class="p-1 box has-background-success" alt="">
                                </div>
                                <div class="column mt-2">
                                    <p>
                                        پیغام هشدار!
                                    </p>
                                    <p>
                                        لورم ایپسورم متن ساختگی با تولید ...
                                    </p>
                                </div>
                                <div class="column has-text-left is-1">
                                    <img src="icons8-edit-24.png" alt="">
                                </div>
                            </div>
                        </div>
                        <div class="column mx-4">

                        </div>
                    </div>
                    <div class="is-flex is-justify-content-space-between my-4">
                        <span>مدیریت آلارم ها</span>
                        <div class="is-flex is-align-items-center ml-4">
                            <p class="has-text-grey ">
                                ذخیره
                            </p>
                            <img src="icons8-arrow-left-20.png" alt="">
                        </div>
                    </div>
                    <div class="columns">
                        <div class="column box has-background-danger-light mx-4 mb-0 br-red-10">
                            <div class="columns">
                                <div class="column is-2">
                                    <img src="icons8-alarm-24.png" class="p-1 box has-background-danger" alt="">
                                </div>
                                <div class="column">
                                    <p class="br-red-10 bg-red py-3 pr-2">
                                پیغام هشدار
                                    </p>
                                    <div class="bg-red-200 mt-4 p-3">
                                        <p class="is-size-7">
                                            لورم ایپسوم متن ساختگی با تولید ...
                                        </p>
                                    </div>
                                </div>
                                <div class="column is-2">
                                    <img src="icons8-tick-20.png" alt="">
                                </div>
                            </div>
                        </div>
                        <div class="column box  mx-4 mb-0 bg-blue">
                            <div class="columns">
                                <div class="column is-2">
                                    <img src="icons8-alarm-24.png" class="p-1 box has-background-info" alt="">
                                </div>
                                <div class="column">
                                    <p class="bg-blue-title py-3 pr-2">
                                پیغام توصیه ای
                                    </p>
                                    <div class="bg-blue-200 mt-4 p-3">
                                        <p class="is-size-7">
                                            لورم ایپسوم متن ساختگی با تولید ...
                                        </p>
                                    </div>
                                </div>
                                <div class="column is-2">
                                    <img src="icons8-tick-20.png" alt="">
                                </div>
                            </div>
                        </div>
                        <div class="column box has-background-success-light mx-4 mb-0 bg-border-green">
                            <div class="columns">
                                <div class="column is-2">
                                    <img src="icons8-alarm-24.png" class="p-1 box has-background-success" alt="">
                                </div>
                                <div class="column">
                                    <p class="bg-green py-3 pr-2">
                                پیغام معمولی
                                    </p>
                                    <div class="bg-green-h200 mt-4 p-3">
                                        <p class="is-size-7">
                                            لورم ایپسوم متن ساختگی با تولید ...
                                        </p>
                                    </div>
                                </div>
                                <div class="column is-2">
                                    <img src="icons8-tick-20.png" alt="">
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<style>
.bg-border-green {
    background-color: #edfff1;
    border: 1px solid #73ff73;
    border-radius: 5px;
}

.bg-green {
    background-color: #dbffe5;
    border: 1px solid #73ff73;
    border-radius: 5px;
}
.bg-blue-title{
    background-color: #cedcff;
  border: 1px solid #73d1ff;
  border-radius: 5px;
}

.bg-blue{
    background-color: #f0f4ff;
  border: 1px solid #73cbff;
  border-radius: 5px;
}
.bg-blue-200{
    height: 200px;
    border: 1px solid #73cbff;
    border-radius: 5px;
}
.br-red-10{
    border: 1px solid #fd8f8f;
  border-radius: 10px;
}
.bg-red{
    background-color: #ffe6e1;
}
.bg-red-200{
    height: 200px;
    border: 1px solid #fd8f8f;
    border-radius: 5px;
}
.bg-green-h200 {
    height: 200px;
    border: 1px solid #73ff73;
    border-radius: 5px;
}
</style>