<template>
    <div class="shopping-mall">
        <header>
            <div class="shopping-mall-left">
                <span>欢迎来到药兜网</span>
            </div>
            <div class="shopping-mall-right">右边</div>
        </header>
    </div>
</template>
<style lang="scss" scoped>
    .shopping-mall {
        height: 30px;
        line-height: 30px;
        background-color: rgba(246,246,246,1);
        header {
            margin: 0 auto;
            width: 1200px;
            display: flex;
            justify-content: space-between;
            .shopping-mall-left {
            }
            .shopping-mall-right {
                width: 200px;
                background: pink;
            }
        }
    }
</style>