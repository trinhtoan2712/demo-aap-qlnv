<template>
    <div class="m-navbar">
        <a class="m-navbar-item">
            <div class="m-navbar-icon icon-dashboard"></div>
            <div class="m-navbar-text">
                Tổng quan
            </div>
        </a>
        <a class="m-navbar-item">
            <div class="m-navbar-icon icon-report"></div>
            <div class="m-navbar-text">
                Báo cáo
            </div>
        </a>
        <a class="m-navbar-item">
            <div class="m-navbar-icon icon-shopping"></div>
            <div class="m-navbar-text">
                Mua hàng
            </div>
        </a>
        <a class="m-navbar-item">
            <div class="m-navbar-icon icon-employee"></div>
            <div class="m-navbar-text">
                Danh mục nhân viên
            </div>
        </a>
        <a class="m-navbar-item">
            <div class="m-navbar-icon icon-setting"></div>
            <div class="m-navbar-text">
                Thiết lập hệ thống
            </div>
        </a>
    </div>
</template>

<script>
export default {
    name: "TheMenu",
    components: {},
    setup() {
    },
}
</script>

<style scoped>
@import url(../../style/layout/menu.css);
</style>
