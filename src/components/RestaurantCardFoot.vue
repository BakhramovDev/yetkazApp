<template>
    <div class="area_foot">
        <div class="item_card">
            <div class="img_area">
                <img src="../assets/reastoran1.jpg" class="foot_img" alt="">
            </div>

            <div class="card_nav">
                <div class="top_nav">
                    <h1>
                        DODO PIZZA
                    </h1>
                    <svg
                        width="24"
                        height="24"
                        viewBox="0 0 24 24"
                        fill="none"
                        xmlns="http://www.w3.org/2000/svg">       
                        <path
                        fill-rule="evenodd"
                        clip-rule="evenodd"
                        d="M7.95005 4.70005C5.53863 4.70005 3.70005 6.50673 3.70005 8.76043C3.70005 10.1572 4.34678 11.4842 5.64265 13.0078C6.9456 14.5397 8.82312 16.1787 11.1551 18.2123L11.1561 18.2132L12.0018 18.9536L12.8444 18.2215C12.8447 18.2212 12.845 18.221 12.8453 18.2207C15.1771 16.1829 17.0543 14.5421 18.3573 13.009C19.6533 11.4842 20.3 10.1573 20.3 8.76043C20.3 6.50673 18.4615 4.70005 16.05 4.70005C14.7212 4.70005 13.4401 5.28291 12.5893 6.20109C12.2715 6.54408 11.7286 6.54408 11.4108 6.20109C10.56 5.28291 9.27895 4.70005 7.95005 4.70005ZM2.30005 8.76043C2.30005 5.6825 4.81747 3.30005 7.95005 3.30005C9.45991 3.30005 10.9147 3.87481 12 4.82447C13.0854 3.87481 14.5402 3.30005 16.05 3.30005C19.1826 3.30005 21.7 5.6825 21.7 8.76043C21.7 10.6353 20.8168 12.2771 19.424 13.9157C18.0527 15.5292 16.1091 17.2277 13.8368 19.2135L13.7657 19.2757L13.7642 19.277L12.525 20.3536C12.2232 20.6158 11.7741 20.615 11.4733 20.3516L10.234 19.2666L10.1867 19.2254C7.90443 17.2351 5.9523 15.5328 4.5762 13.9148C3.18332 12.2771 2.30005 10.6353 2.30005 8.76043Z"
                        fill="#1A1A18"
                        ></path>
                    </svg>
                </div>

                <!--  -->

                <div class="int_nav">
                    <p>
                        Minimal buyurtma miqdori 0 so'm
                    </p>
                </div>
            </div>
        </div>
    </div>
</template>



<style scoped>
    .area_foot{
        width: 100%;
        height: 300px;
        box-shadow: 5px 5px 5px -5px rgba(0, 0, 0, 0.6) ;
        border: 0.3px solid rgba(129, 129, 129, 0.491);
        background-color: rgb(255, 255, 255);
    }
    .item_card{
        width: 100%;
        height: 330px;
    }
    .img_area{
        height: 200px;
        width: 100%;
    }
    .foot_img{
        height: 100%;
        width: 100%;
        object-fit: cover;
    }
    .card_nav{
        width: 100%;
        margin-top: 8px;
    }
    .top_nav{
        width: 95%;
        margin: 0 auto;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    .int_nav{
        width: 95%;
        font-weight: 500;
        color: rgba(171, 171, 171, 0.611);
        margin: 0 auto;
        display: flex;
        align-items: center;
        justify-content: left;
    }
</style>