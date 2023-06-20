<script>
export default {
    
}
</script>

<template>
<div class="background">
    <footer>
        <!-- sezione comics, merchandise, subscription, shop locator, power visa -->
        <div class="acquisti">
            <div>
                <img src="../assets/img/buy-comics-digital-comics.png">
                <span>digital comics</span>
            </div>
            <div>
                <img src="../assets/img/buy-comics-merchandise.png">
                <span>dc merchandise</span>
            </div>
            <div>
                <img src="../assets/img/buy-comics-subscriptions.png">
                <span>subscription</span>
            </div>
            <div>
                <img src="../assets/img/buy-comics-shop-locator.png">
                <span>comic shop locator</span>
            </div>
            <div>
                <img src="../assets/img/buy-dc-power-visa.svg">
                <span>dc power visa</span>
            </div>
        </div>
        <div class="container">
        <!-- sezione link utili -->
        <div class="link-utili">
            <!-- dc comics -->
            <div>
                <ul>
                    <h3>dc comics</h3>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                </ul>
            </div>
            <!-- shop -->
            <div>
                <ul>
                    <h3>shop</h3>
                    <li>Shop DC</li>
                    <li>Shop DC Collectibles</li>
                </ul>
            </div>
             <!-- dc -->
            <div>
                <ul>
                    <h3>dc</h3>
                    <li>Terms Of Use</li>
                    <li>Privacy policy (New)</li>
                    <li>Ad Chioces</li>
                    <li>Advertising</li>
                    <li>Jobs</li>
                    <li>Subscriptions</li>
                    <li>Talent Workshops</li>
                    <li>CPSC Certificates</li>
                    <li>Ratings</li>
                    <li>Shop Help</li>
                    <li>Contact Us</li>
                </ul>
            </div>
            <!-- sites -->
            <div>
                <ul>
                    <h3>sites</h3>
                    <li>DC</li>
                    <li>MAD Magazine</li>
                    <li>DC Kids</li>
                    <li>DC Universe</li>
                    <li>DC Power Visa</li>
                </ul>
            </div>
        </div>
        <!-- dc logo -->
        <img src="../assets/img/dc-logo-bg.png">
        </div>
        <!-- sezione collegamenti social -->
        <div class="social">
            <!-- sign up -->
            <div>
                <button>sign-up now!</button>
            </div>
            <!-- social -->
            <div>
                <span>follow us</span>
                <img src="../assets/img/footer-facebook.png">
                <img src="../assets/img/footer-twitter.png">
                <img src="../assets/img/footer-youtube.png">
                <img src="../assets/img/footer-pinterest.png">
                <img src="../assets/img/footer-periscope.png">
            </div>
        </div>
    </footer>
</div>
</template>

<style scoped lang="scss">
@use '../styles/partials/variables' as *;
@use '../styles/generals.scss' as *;
    .background {
        background-image: url('../assets/img/footer-bg.jpg');
        background-size: cover;
        height: 100%;
    }

    footer {
        width: 100vw;
        height: 100%;
        position: relative;

        .acquisti {
            display: flex;
            margin: 0 auto;
            padding: 50px 50px;
            background-color: $color-primary;
            align-items: center;
            justify-content: space-around;

            div {
                display: flex;
                align-items: center;
                margin: 0 10px;

                img {
                    width: 40px;
                }

                span {
                    color: white;
                    text-transform: uppercase;
                    margin-left: 10px;
                    font-size: 12px;
                }
            }
        }

        .container {
            display: flex;
            position: relative;

            .link-utili {
            height: 30vh;
            display: flex;
            flex-direction: column;
            flex-wrap: wrap;
            justify-content: flex-start;

                ul {
                    color: white;
                    list-style: none;
                    margin: 10px 0;

                    h3 {
                        margin: 5px 0;
                        text-transform: uppercase;
                    }

                    li {
                        font-size: 12px;
                        color: grey;
                        margin: 3px 0;
                    }
                }

                div {
                    margin: 0 20px;
                }
            }

            img {
                position: absolute;
                right: 50px;
                top: -30px;
                height: 130%;
            }
        }

        .social {
            background-color: rgb(48, 48, 48);
            position: absolute;
            left: 0;
            right: 0;
            bottom: -100px;
            height: 100px;
            display: flex;
            justify-content: space-around;
            align-items: center;

            button {
                border: 1px solid $color-primary;
                padding: 10px;
                background-color: rgb(48, 48, 48);
                color: white;
                text-transform: uppercase;
            }

            div {
                display: flex;
                align-items: center;

                img {
                    margin: 0 10px;
                }

                span {
                    margin-right: 20px;
                    text-transform: uppercase;
                    font-weight: bold;
                    color: $color-primary;
                }
            }

        }
    }
</style>