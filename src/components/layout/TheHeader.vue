<template>
    <div class="m-header">
        <div class="m-header-left">
            <div class="m-sitebar"></div>
            <div class="m-logo"></div>
        </div>
        <div class="m-header-right">
            <div class="m-header-right-section">
                <select data-selected="">
                    <option value="" selected="selected" disabled="disabled">Chọn nhà hàng</option>
                    <option value="1">Ocean Wall</option>
                    <option value="2">Skate Park</option>
                </select>
            </div>
            <div class="m-header-right-section">
                <div class="m-account-avatar siteHeader__item"></div>
                <div class="m-account-name siteHeader__item"> Nguyễn Văn Mạnh </div>
                <div class="m-account-setting siteHeader__item"></div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "TheHeader",
    components: {
    },
    setup() {

    },
}
</script>

<style scoped>
@import url(../../style/layout/header.css);
</style>