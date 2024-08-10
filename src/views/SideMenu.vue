    <script setup>

    </script>
    <template>
    <div>
        <div class="menu-top box">
        <div class="box-in-side">
            <div><p class="menu-text" style="color: aliceblue;"><i class="fa-solid fa-house menu-icon" ></i> Home</p></div>
            <div><p class="menu-text"><i class="fa-solid fa-magnifying-glass menu-icon"></i> Search</p></div>
        </div>
        </div>
    <div class="menu-bottom box">
        <div class="box-in-side" style="
    display: flex;
    justify-content: space-around;
    padding-left: 0px;
        ">
         <div>
           <p class="menu-text"><i class="fa-solid fa-lines-leaning  menu-icon" ></i>Your Library</p>
        </div>
        <div>
            <i class="fa-solid fa-plus"
            style="
    font-size: 20px;
    margin-right: 13px;
    color: #989898;
"
            ></i>
            <i class="fa-solid fa-arrow-right-long"
            style="
    font-size: 20px;
    margin-left: 7px;
    color: #989898;"
            ></i>
        </div>
        </div>
    
        <div class="box-in-side2">
            <div>
            <div class="menu-btn">Playlists</div>
            <div class="search-list">
                <div>
                    <i class="fa-solid fa-magnifying-glass"
                    style="padding: 12px;"
                    ></i>
                </div>
                <div>
                    <p
                    style="
                        margin-right: 20px;
                        font-size: smaller;
                        padding-top: 7px;
                    "
                    >Recents <i class="fa-solid fa-list"
                    style="font-size: 18px;"
                    ></i></p>
                </div>
            </div>
           </div>
           <div style="display: flex;">
            <div class="playlist-box">
                <i class="fa-solid fa-music"></i>
            </div>
            <div class="list-user">
                <p
                style="
                        font-size: 17px;
                        font-weight: 400;
                        color: white;
                    "
                >My Playlist #1</p>
               <p
               style="font-size: 15px; color: #989898;"
               >playlist:vineet kushwaha</p>
            </div>
           </div>
        </div>
    </div>
    </div>
    </template>
    <style scoped>
    .menu-top {
        height: 110px;
        width: 300px;
        margin-bottom: 6px;
        font-size: larger;
    }
    .menu-bottom{
        height: 400px;
        width: 300px;
        font-size: larger;
    }
    .box-in-side{
    padding: 15px 0px 0px 26px;
    }
    .menu-text{
    font-size: 17px;
    font-weight: bolder;
    color: #989898;
    }
    .menu-icon{
        min-width: 24px;
        margin-right: 12px;
        font-size: 23px;
    }
    .menu-btn{
        border-radius: 20px;
        height: 30px;
        font-size: 14px;
        font-weight: 500;
        background-color: #2a2a2a;
        width: 85px;
        text-align: center;
        line-height: 28px;
        color: white;
    }
    .box-in-side2{
    padding: 12px 0px 0px 17px;
    }
    .search-list{
        display: flex;
        justify-content: space-between;
        margin-top: 7px;
        color: #989898;
    }
    .playlist-box{
        background-color: #282828;
        width: 53px;
        height: 49px;
        border-radius: 6px;
        text-align: center;
        line-height: 51px;
        font-size: 26px;
        color: wheat;
    }
    .list-user{
        margin-left: 13px;
    line-height: 10px;
    padding-top: 10px;
    }
    </style>
