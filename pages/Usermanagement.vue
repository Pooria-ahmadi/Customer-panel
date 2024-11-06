<template>
    <div style="overflow: hidden;">
        <div class="max-width-1160px mx-auto">
            <div class="columns mx-0 mb-6 pt-4 pb-6">
                <div class="column box py-6 px-5">
                    <div class="is-flex is-justify-content-space-between my-4">
                        <div>
                            <p class="has-text-black">
                                مدیران مشتریان
                            </p>
                            <p>
                                در این قسمت میتوانید مشتری های خود را مدیریت کنید و همچنین مشتری اضافه کنید.
                            </p>
                        </div>

                        <button class="button p-30 br-15" @click="showModal = true">
      <span class="has-text-centered">
        <span class="is-block color-8D79D1">افزودن مشتری</span>
        <img src="icon.png" alt="icon">
      </span>
    </button>

    <!-- پاپ‌آپ -->
    <div class="modal" :class="{ 'is-active': showModal }">
      <div class="modal-background" @click="closeModal"></div>
      <div class="modal-content">
        <div class="columns is-centered">
          <div class="column is-10">
            <div class="box pt-0">
              <div class="has-text-centered">
                <img src="titlepopup.png" alt="">
                <p class="color-8D79D1">
                  افزودن کاربر
                </p>
              </div>
              <div class="columns mt-4">
                <div class="column" v-for="(form, index) in boxform" :key="index">
                  <p>{{ form.label }}</p>
                  <input class="input" type="text" :placeholder="form.placeholder">
                </div>
              </div>
              <div class="columns">
                <div class="column" v-for="(form2, index) in boxform2" :key="index">
                  <p>{{ form2.label }}</p>
                  <input class="input" type="text" :placeholder="form2.placeholder">
                </div>
              </div>
              <div class="columns">
                <div class="column" :class="form3.isfive" v-for="(form3, index) in boxform3" :key="index">
                  <p>{{ form3.label }}</p>
                  <input class="input" type="text" :placeholder="form3.placeholder">
                </div>
              </div>
              <div class="has-text-centered">
                <button class="button bg-purple has-text-white" @click="closeModal">افزودن ردیف</button>
              </div>
            </div>
          </div>
        </div>
      </div>
      <button class="modal-close is-large" aria-label="close" @click="closeModal"></button>
    </div>
                    </div>
                    <div class="is-flex">
                        <img src="Filter 3.png" alt="">
                        <p>
                            مرتب سازی بر اساس
                        </p>
                        <p class="mx-5">
                            جدیدترین
                        </p>
                        <p>
                            قدیمی ترین
                        </p>
                    </div>
                    <div class="columns is-multiline mx-3 mt-75 br-10-grey">
                        <div class="column has-text-centered ">
                            <div class="column-header has-text-grey"> تعداد مشتری ها: 2</div>
                            <img src="Profile Square 2.png" alt="">
                        </div>
                        <div class="column has-text-centered ">
                            <div class="column-header ">نام و خانوادگی</div>
                            <p>
                                پوریا احمدی
                            </p>
                        </div>
                        <div class="column has-text-centered ">
                            <div class="column-header ">تلفن همراه</div>
                            <p>
                                09102666127
                            </p>
                        </div>
                        <div class="column has-text-centered ">
                            <div class="column-header ">تعداد پیغام ها</div>
                            <p>
                                3
                            </p>
                        </div>
                        <div class="column has-text-centered ">
                            <div class="column-header ">تعداد دستگاه ها</div>
                            <p>
                                3
                            </p>
                        </div>
                        <div class="column has-text-centered ">
                            <div class="column-header ">کدملی</div>
                            <p>
                                1250359318413
                            </p>
                        </div>
                        <div class="column has-text-centered ">
                            <div class="column-header ">تاریخ اضافه شدن</div>
                            <p>
                                1403 / 08 / 09
                            </p>
                        </div>
                        <div class="column has-text-centered  is-align-content-center">
                            <img src="icons8-back-20.png" alt="">
                        </div>
                    </div>
                    <div class="columns is-multiline mx-3 mt-0 br-10-grey is-vcentered py-3">
                        <div class="column has-text-centered ">

                            <img src="Profile Square 2.png" alt="">
                        </div>
                        <div class="column has-text-centered ">

                            <p>
                                پوریا احمدی
                            </p>
                        </div>
                        <div class="column has-text-centered ">

                            <p>
                                09102666127
                            </p>
                        </div>
                        <div class="column has-text-centered ">

                            <p>
                                3
                            </p>
                        </div>
                        <div class="column has-text-centered ">

                            <p>
                                3
                            </p>
                        </div>
                        <div class="column has-text-centered ">

                            <p>
                                1250359318413
                            </p>
                        </div>
                        <div class="column has-text-centered ">

                            <p>
                                1403 / 08 / 09
                            </p>
                        </div>
                        <div class="column has-text-centered  is-align-content-center">
                            <img src="icons8-back-20.png" alt="">
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

</template>
<script>
export default {
  data() {
    return {
      showModal: false,
      boxform: [
        { label: 'نام', placeholder: 'نام خود را وارد کنید' },
        { label: 'نام خانوادگی', placeholder: 'نام خانوادگی خود را وارد کنید' },
        { label: 'شماره تلفن', placeholder: 'شماره تلفن خود را وارد کنید' },
        { label: 'کد ملی', placeholder: 'کد ملی خود را وارد کنید' }
      ],
      boxform2: [
        { label: 'ایمیل', placeholder: 'ایمیل را وارد کنید' },
        { label: 'مدل دستگاه', placeholder: 'مدل دستگاه را وارد کنید' },
        { label: 'شماره سریال دستگاه', placeholder: 'شماره سریال دستگاه را وارد کنید' },
        { label: 'استان', placeholder: 'استان را وارد کنید' }
      ],
      boxform3: [
        { label: 'نام کاربری', placeholder: 'نام کاربری را وارد کنید' },
        { label: 'رمز عبور', placeholder: 'رمز عبور خود را وارد کنید' },
        { label: 'آدرس', placeholder: 'آدرس خود را وارد کنید', isfive: 'is-6' }
      ]
    };
  },
  methods: {
    closeModal() {
      this.showModal = false;
    },
  }
};
</script>
<style>
button {
    transition: all 0.3s ease;
}

.button:hover {
    background-color: #D0D0D0;
}

.modal-content {
    max-width: 100%;
    width: 100%;
    max-height: 100%;
    overflow: hidden;
}

.column-header {
    position: relative;
    top: -50px;
}

.mt-75 {
    margin-top: 75px;
}
</style>