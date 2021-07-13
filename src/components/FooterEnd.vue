<template>
    <div class="footer-end">
        <div class="container flex">
            <div>
                <button>Sign Up Now!</button>
            </div>
            <div class="icons flex">
                <div>FOLLOW UP</div>
                <div>
                    <img src="../assets/footer-facebook.png" alt="">
                </div>
                <div>
                    <img src="../assets/footer-periscope.png" alt="">
                </div>
                <div>
                    <img src="../assets/footer-pinterest.png" alt="">
                </div>
                <div>
                    <img src="../assets/footer-twitter.png" alt="">
                </div>
                <div>
                    <img src="../assets/footer-youtube.png" alt="">
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "FooterEnd",
}
</script>

<style lang="scss" scoped>
    .footer-end{
        height: 80px;
        background-color: rgb(48,48,48);
        position: relative;
        z-index: 2;
        .container{
            align-items: center;
            justify-content: space-between;
            button{
                background-color:rgb(48,48,48);
                font-size: 20px;
                padding: 10px;
                color: white;
                border-color: rgb(2,130,249);
                font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
            }
            .icons{
                align-items: center;
                padding: 0 10px;
                color: rgb(2,130,249);
                div{
                    padding: 0 5px;
                }
            }
        }
    }

</style>