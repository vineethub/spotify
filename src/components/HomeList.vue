<script setup>
</script>
<template>
    <div class="list-box">
        <div class="list-header box-in-side">
            <div style="display: flex; justify-content: space-between;">
                <div style="display: flex;">
                    <div class="list-header-arrow" style="margin-right:10px;"><i class="fa-solid fa-chevron-left"></i></div>
                    <div class="list-header-arrow"><i class="fa-solid fa-chevron-right"></i></div>
                </div>
                <div style="display: flex;">
                    <div class="explore-btn">Explore Premium</div>
                    <div class="install-btn"><i class="fa-regular fa-circle-down"
                        style="
                            font-size: 15px;
                            margin-right: 3px;
                            margin-top: 2px;
                        "
                        ></i>Install App</div>
                    <div class="list-header-arrow" style="margin-right:10px;"><i class="fa-regular fa-bell"></i></div>
                    <div class="list-header-arrow" style=" margin-right: 10px; font-weight: bolder; color: rgb(207, 136, 42);">V</div>
                </div>
            </div>
            <div style="display: flex; gap: 10px; margin-top: 20px;">
                <div class="btn-all">All</div>
                <div class="btn-music">Music</div>
                <div class="btn-podcast">Podcast</div>
            </div>
        </div>
    </div>
</template>
<style scoped>
.list-box{
    height: 500px;
    background-color: #121212;
    border-radius: 8px;
   width: 1033px;
   margin-left: -15px;
}
.list-header-arrow{
    width: 33px;
    height: 33px;
    border-radius: 100%;
    color: #989898;
    background-color: black;
    text-align: center;
    line-height: 33px;
}
.box-in-side{
    padding: 15px 0px 0px 26px;
    }
    .explore-btn{
    background-color: white;
    width: 175px;
    border-radius: 22px;
    text-align: center;
    line-height: 32px;
    font-size: smaller;
    font-weight: bold;
    margin-right: 10px;
    color: black;
    }
    .install-btn{
    background-color: black;
    width: 115px;
    border-radius: 22px;
    text-align: center;
    line-height: 29px;
    font-size: smaller;
    font-weight: bolder;
    color: white;
    margin-right: 10px;
    }
    .btn-all{
        text-align: center;
        padding: 8px;
        border-radius: 16px;
        background: white;
        color: black;
        width: 45px;
        height: 33px;
        line-height: 15px;
    }
    .btn-music{
        text-align: center;
        padding: 8px;
        border-radius: 16px;
        background-color: #343434;
        color: white;
        width: 71px;
        height: 33px;
        line-height: 15px;
    }
    .btn-podcast{
        text-align: center;
        padding: 8px;
        border-radius: 16px;
        background-color: #343434;
        color: white;
        width: 80px;
        height: 33px;
        line-height: 15px;
    }
</style>