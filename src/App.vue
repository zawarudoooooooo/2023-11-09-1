<script>
export default{
    data(){
        return{
        }
    },
    methods:{
    }
}
</script>

<template>
<!-- Logo -->
    <div class="logo">
        <h1 class="gradient-text">Ting*s</h1>
    </div>
<!-- Nav -->
    <div class="header">
        <nav class="navbar navbar-expand-lg navbar-light">
            <div class="container-fluid">
                <a class="navbar-brand" href="#">雙11狂歡購</a>
                    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                    </button>
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                        <li class="nav-item">
                            <a class="nav-link active" aria-current="page" href="#">New Arrival</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Live 直播線上購</a>
                        </li>
                        <li class="nav-item dropdown">
                            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">現貨專區</a>
                                <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                                    <li><a class="dropdown-item" href="#">上衣</a></li>
                                    <li><a class="dropdown-item" href="#">下著</a></li>
                                    <li><a class="dropdown-item" href="#">裙裝</a></li>
                                    <li><a class="dropdown-item" href="#">外套</a></li>
                                    <li><hr class="dropdown-divider"></li>
                                    <li><a class="dropdown-item" href="#">換季下殺</a></li>
                                </ul>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">生活選物</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">旅拍企劃</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">ITEMS</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">SALE</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">COLLECTION</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">線上購物</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">會員專區</a>
                        </li>
                    </ul>
                        <form class="d-flex">
                            <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                            <button class="btn btn-sm btn-outline-secondary" type="submit">Search</button>
                        </form>
                </div>
            </div>
        </nav>
    </div>
<!-- ItemArea -->
    <div class="firstItem">
        <img src="../public/發表圖片/item/1-2.jpeg" alt="">
        <img src="../public/發表圖片/item/1-1.jpeg" alt="">
        <img src="../public/發表圖片/item/1-3.jpeg" alt="">
    </div>

    <div class="secondItem">
        <img src="../public/發表圖片/item/2-3.jpg" alt="" loading="lazy">
        <img src="../public/發表圖片/item/2-2.jpg" alt="" loading="lazy">
        <img src="../public/發表圖片/item/2-1.jpg" alt="" loading="lazy">
        <div class="text">
            <span>Life Wear</span>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus architecto neque, eius dolorem et dolore!
            </p>
            <button type="button">More</button>
        </div>
    </div>

    <div class="thirdItem">
        <div class="text">
            <span>Special Edition</span>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellendus, dolorum ad. Accusantium amet reprehenderit itaque.
            </p>
            <button type="button">More</button>
        </div>
        <img src="../public/發表圖片/item/4-2.jpg" alt="" loading="lazy">
        <img src="../public/發表圖片/item/4-3.jpg" alt="" loading="lazy">
        <img src="../public/發表圖片/item/4-1.jpg" alt="" loading="lazy">
    </div>

    <div class="forthItem">
        <img src="../public/發表圖片/item/3-3.jpg" alt="" loading="lazy">
        <img src="../public/發表圖片/item/3-1.jpg" alt="" loading="lazy">
        <img src="../public/發表圖片/item/3-2.jpg" alt="" loading="lazy">
    </div>
<!-- Circle grid裝飾 -->
    <div class="circle">
    </div>
<!-- Grid -->
    <div class="gridContainer">
        <span>Show Your Style</span>
        <div class="item">
            <img src="../public/發表圖片/grid/1.jpg" alt="" loading="lazy">
        </div>
        <div class="item">
            <img src="../public/發表圖片/grid/2.jpg" alt="" loading="lazy">
        </div>
        <div class="item">
            <img src="../public/發表圖片/grid/14.jpg" alt="" loading="lazy">
        </div>
        <div class="item">
            <img src="../public/發表圖片/grid/4.jpg" alt="" loading="lazy">
        </div>
        <div class="item">
            <img src="../public/發表圖片/grid/5.jpg" alt="" loading="lazy">
        </div>
        <div class="item">
            <img src="../public/發表圖片/grid/10.jpg" alt="" loading="lazy">
        </div>
        <div class="item">
            <img src="../public/發表圖片/grid/9.jpg" alt="" loading="lazy">
        </div>
        <div class="item">
            <img src="../public/發表圖片/grid/8.jpg" alt="" loading="lazy">
        </div>
        <div class="item">
            <img src="../public/發表圖片/grid/7.jpg" alt="" loading="lazy">
        </div>
        <div class="item">
            <img src="../public/發表圖片/grid/6.jpg" alt="" loading="lazy">
        </div>
        <div class="item">
            <img src="../public/發表圖片/grid/11.jpg" alt="" loading="lazy">
        </div>
        <p>Show Your Confidence</p>
        <div class="item">
            <img src="../public/發表圖片/grid/12.jpg" alt="" loading="lazy">            
        </div>
        <div class="item">
            <img src="../public/發表圖片/grid/13.jpg" alt="" loading="lazy">
        </div>
        <div class="item">
            <img src="../public/發表圖片/grid/17.jpg" alt="" loading="lazy">
        </div>
        <div class="item">
            <img src="../public/發表圖片/grid/15.jpg" alt="" loading="lazy">
        </div>
        <div class="item">
            <img src="../public/發表圖片/grid/16.jpg" alt="" loading="lazy">
        </div>
        <div class="item">
            <img src="../public/發表圖片/grid/3.jpg" alt="" loading="lazy">
        </div>
        <div class="item">
            <img src="../public/發表圖片/grid/18.jpg" alt="" loading="lazy">
        </div>
        <div class="item">
            <img src="../public/發表圖片/grid/19.jpg" alt="" loading="lazy">
        </div>
        <div class="item">
            <img src="../public/發表圖片/grid/20.jpg" alt="" loading="lazy">
        </div>
        <div class="item">
            <img src="../public/發表圖片/grid/21.jpg" alt="" loading="lazy">
        </div>

    </div>

<!-- Footer -->
    <div class="footer">
        <div class="iconarea">
            <i class="fa-brands fa-facebook"></i>
            <i class="fa-brands fa-instagram"></i>
            <i class="fa-brands fa-twitter"></i>
            <i class="fa-brands fa-youtube"></i>
            <i class="fa-brands fa-tiktok"></i>
        </div>
        <ul>
            <li>最新消息</li>
            <li>常見問題</li>
            <li>門市資訊</li>
            <li>會員權益</li>
            <li>售後服務</li>
        </ul>
    </div>

</template>

<style lang="scss" scoped>
    .logo{
        width: 100vw;
        height: 30vh;
        text-align: center;
        margin-left: 10vmin;

        h1 {
        font-family: 'Poppins', sans-serif;
        font-size: 20vmin;
        line-height: 26vmin;
        margin: 0;
        }
    .gradient-text {
        color: transparent;
        background: conic-gradient(
            #D9D7F1 12%, 
            #BAABDA 12%, #BAABDA 33%, 
            #E7FBBE 33%, #E7FBBE 55%, 
            #FFCBCB 55%, #FFCBCB 70%, 
            #B5DEFF 70%, #B5DEFF 87%, 
            #F7D1BA 87%);
            background-size: 50%;
            background-clip: text;  
            -webkit-background-clip: text;
            animation: expand-rev 0.5s ease forwards;
            cursor: pointer;
    }
    .gradient-text:hover {
        animation: expand 0.5s ease forwards;
    }
    @keyframes expand {
        0% {
            background-size: 50%;
            background-position: 0 0;
        }
        20% {
            background-size: 55%;
            background-position: 0 1em;
        }
        100% {
            background-size: 325%;
            background-position: -10em -4em;
        }
    }
    @keyframes expand-rev {
        0% {
            background-size: 325%;
            background-position: -10em -4em;
        }
        20% {
            background-size: 55%;
            background-position: 0 1em;
        }
        100% {
            background-size: 50%;
            background-position: 0 0;
        }
    }

    }

    .header{
    width: 90vw;
    height: 10vh;
    background-color: #FBF8F1;
    margin-left: 17vmin;
    }

    .firstItem{
    width: 75vw;
    height: 80vh;
    margin-top: 5vmin;
    margin-left: 32vmin;
    position: relative;
    overflow: hidden;

        img{
        width: 25vw;
        height: 75vh;
        border-radius: 8px;
        opacity: 1;
        transition: ease-in;
        backface-visibility: hidden;

        &:hover{
            scale: 1.03;
            opacity: 0.3;
        }
        &:active{
            scale: 0.95;
        }
        }

    }

    .secondItem{
    width: 100vw;
    height: 80vh;
    margin-top: 10vmin;
    display: flex;
    position: relative;
    overflow: hidden;

        img{
        width: 25vw;
        height: 75vh;
        border-radius: 8px;

        &:hover{
            scale: 1.03;
            opacity: 0.3;
        }

        &:active{
            scale: 0.95;
        }
        }

        .text{
        width: 15vw;
        height: 45vh;
        text-align: center;
        margin-top: 10vmin;
        margin-left: 10vmin;

        span{
            font-size: 36pt;
        }

        p{
            font-size: 16pt;
            margin-top: 5vmin;

        }

        button{
            border-style: none;
            border-radius: 5px;
            box-shadow: 2px 2px 2px #aabdcd;
            margin-top: 3vmin;

            &:hover{
                background-color: #BAABDA;
                color: aliceblue;
            }

            &:active{
                background-color: aliceblue;
                color: #BAABDA;
            }
        }
        }
    }

    .thirdItem{
    width: 100vw;
    height: 80vh;
    margin-top: 10vmin;
    margin-left: 15vmin;
    display: flex;
    position: relative;
    overflow: hidden;

        img{
        width: 25vw;
        height: 75vh;
        border-radius: 8px;

        &:hover{
            scale: 1.03;
            opacity: 0.3;
        }

        &:active{
            scale: 0.95;
        }
        } 
        .text{
        width: 15vw;
        height: 45vh;
        text-align: center;
        margin-top: 5vmin;
        margin-right: 10vmin;

        span{
            font-size: 36pt;
        }

        p{
            font-size: 16pt;
            margin-top: 5vmin;

        }

        button{
            border-style: none;
            margin-top: 3vmin;
            border-radius: 5px;
            box-shadow: 2px 2px 2px #aabdcd;
            margin-right: 2vmin;

            &:hover{
                background-color: #BAABDA;
                color: aliceblue;
            }

            &:active{
                background-color: aliceblue;
                color: #BAABDA;
            }
        }
        }
    }

    .forthItem{
    width: 75vw;
    height: 80vh;
    margin-top: 10vmin;
    margin-bottom: 15vmin;
    margin-left: 35vmin;
    position: relative;
    overflow: hidden;

        img{
        width: 25vw;
        height: 75vh;
        border-radius: 8px;

        &:hover{
            scale: 1.03;
            opacity: 0.3;
        }

        &:active{
            scale: 0.95;
        }
        }
    }

    .circle{
    width: 50vw;
    height: 50vw;
    border-radius: 50%;
    background-color: #BAABDA;
    position: absolute;
    left: 0;
    bottom: 28%;
    opacity: 0.5;
    z-index: -1;

        // &::before{
        // content: "";
        // width: 150px;
        // height: 300px;
        // background-color: #FBF8F1;
        // position: absolute;
        // left: 0;
        // }
    }

    .gridContainer{
    width: 90vw;
    height: 250vh;
    display: flex;
    grid-template-columns: 5vmin 5vmin 5vmin;
    grid-template-rows: 15vmin 15vmin 15vmin ;
    grid-gap: 10px;
    padding: 10px;
    flex-wrap: wrap;
    column-count: 5;
    position: relative;
    margin-left: 25vmin;

        &::before{
        content: "";
        width: 0;
        height: 0;
        border: 100vmin solid #FFCBCB;
        border-color: transparent #FFCBCB transparent transparent;
        position: absolute; 
        top: 11.5%;
        z-index: -1;
        opacity: 0.5;
        }

        span{
        margin-top: 20vmin;
        margin-right: 10vmin;
        margin-left: 5vmin;
        color: #FBF8F1;
        font-size: 36pt;
        }

        p{
        margin-top: 20vmin;
        margin-left: 15vmin;
        font-size: 30pt;
        color: #aabdcd;
        }

        .item{
            img{
            width: 15vw;
            height: 50vh;
            border-radius: 8px;
            opacity: 1;
            transition: .5s ease;
            backface-visibility: hidden;

                &:hover{
                scale: 1.03;
                opacity: 0.3;
                transform: rotate(5deg);
                }

                &:active{
                scale: 0.95;
                }
            }
        }
    }

    .footer{
    width: 100vw;
    height: 20vh;
    background-color: #aabdcd ;
    margin-top: 20vmin;
    margin-left: 5vmin;
    position: relative;

        .iconarea{
            width: 15vw;
            display: flex;
            font-size: 16pt;
            color: #FBF8F1;
            justify-content: space-around;
            margin-left: 90vmin;
            position: absolute;
            top: 5vmin;
        }

        ul{
            width: 50vw;
            display: flex;
            font-size: 12pt;
            justify-content: space-around;
            color: #FBF8F1;
            margin-left: 50vmin;
            position: absolute;
            top: 12vmin;
            
        }
    }

    @media(max-width:992px){
        .logo{
            height: 18vh;
            margin-left: 7vmin;
            margin-top: 3vmin;
        }

        .header{
            height: 8vh;
            margin-left: 13vmin;
            background-color: #FBF8F1;

            .container-fluid{
                background-color: #FBF8F1;

                ul{
                    height: 33vh;
                    overflow: scroll;
                    overflow-x: hidden;
                    z-index: 3;
                }
            }
        }

        .firstItem{
            height: 30vh;
            margin-left: 21vmin;
            z-index: -1;

            img{
                height: 28vh;
            }
        }

        .secondItem{
            height: 30vh;
            margin-left: 10vmin;

            img{
                width: 23vw;
                height: 28vh;
            }

            .text{
                width: 20vw;
                height: 28vh;
                margin-left: 5vmin;
                margin-top: 2vmin;

                span{
                    font-size: 26pt;
                }

                p{
                    font-size: 13pt;
                    margin-top: 2vmin;
                }

                button{
                    font-size: 2vmin;
                    margin-left: 0;
                }
            }
        }

        .thirdItem{
            height: 30vh;
            margin-left: 12vmin;

            img{
                width: 23vw;
                height: 28vh;
            }

            .text{
                width: 20vw;
                height: 28vh;
                margin-top: 2vmin;
                margin-right: 3vmin;

                span{
                    font-size: 23pt;
                }

                p{
                    font-size: 11pt;
                    margin-top: 2vmin;
                }

                button{
                    font-size: 2vmin;
                    margin-left: 0;
                    margin-top: 0;
                }
            }

        }

        .forthItem{
            width: 80vw;
            height: 30vh;
            margin-left: 21vmin;
            margin-bottom: 6vmin;

            img{
                height: 28vh;
            }
        }

        .circle{
            bottom: 40%;
        }

        .gridContainer{
            width: 80vw;
            height: 150vh;
            margin-left: 18.5vmin;
            margin-bottom: 0;
            grid-gap: 5px;

            &::before{
                top: 31%;
                border: 40vmin solid #FFCBCB;
                border-color: transparent #FFCBCB transparent transparent;
                right: -10%;
            }
            

            span{
                font-size: 29pt;
                color: lightslategrey;
                margin-top: 9vmin;
                margin-left: 5vmin;
            }

            P{
                font-size: 20pt;
                margin-top: 11vmin;
                margin-left: 1vmin;
                color: rosybrown;
            }


            .item{
                img{
                    width: 18vw;
                    height: 20vh;
                }
            }

        }

        .footer{
            width: 110vw;
            height: 10vh;
            margin-top: 5vmin;

            .iconarea{
                width: 30vw;
                font-size: 19pt;
                margin-left: 35vmin;
                top: 4vmin;
            }

            ul{
                width: 70vw;
                font-size: 12pt;
                margin-left: 15vmin;
                top: 9vmin;
            }
        }

    }

    @media(max-width:768px){
        .logo{
            height: 20vh;
            margin-left: 7vmin;
            margin-top: 3vmin;
        }

        .header{
            height: 8vh;
            margin-left: 13vmin;
            background-color: #FBF8F1;

            .container-fluid{
                background-color: #FBF8F1;

                ul{
                    height: 33vh;
                    overflow: scroll;
                    overflow-x: hidden;
                    z-index: 3;
                }
            }
        }

        .firstItem{
            height: 30vh;
            margin-left: 20vmin;
            z-index: -1;

            img{
                height: 28vh;
            }
        }

        .secondItem{
            height: 30vh;
            margin-left: 10vmin;

            img{
                width: 23vw;
                height: 28vh;
            }

            .text{
                width: 20vw;
                height: 28vh;
                margin-left: 5vmin;
                margin-top: 2vmin;

                span{
                    font-size: 24pt;
                }

                p{
                    font-size: 11pt;
                    margin-top: 1vmin;
                }

                button{
                    font-size: 2vmin;
                    margin-left: 0;
                }
            }
        }

        .thirdItem{
            height: 30vh;
            margin-left: 12vmin;

            img{
                width: 23vw;
                height: 28vh;
            }

            .text{
                width: 20vw;
                height: 28vh;
                margin-top: 2vmin;
                margin-right: 3vmin;

                span{
                    font-size: 23pt;
                }

                p{
                    font-size: 10pt;
                    margin-top: 1vmin;
                }

                button{
                    font-size: 2vmin;
                    margin-left: 0;
                    margin-top: 0;
                }
            }

        }

        .forthItem{
            width: 80vw;
            height: 30vh;
            margin-left: 20vmin;
            margin-bottom: 6vmin;

            img{
                height: 28vh;
            }
        }

        .circle{
            bottom: 41.5%;
        }

        .gridContainer{
            width: 80vw;
            height: 150vh;
            margin-left: 18.5vmin;
            margin-bottom: 0;
            grid-gap: 5px;

            &::before{
                top: 29.5%;
                border: 40vmin solid #FFCBCB;
                border-color: transparent #FFCBCB transparent transparent;
                right: -10%;
            }
            

            span{
                font-size: 28pt;
                color: lightslategrey;
                margin-top: 9vmin;
                margin-left: 5vmin;
            }

            P{
                font-size: 20pt;
                margin-top: 10vmin;
                margin-left: 1vmin;
                color: rosybrown;
            }


            .item{
                img{
                    width: 18vw;
                    height: 20vh;
                }
            }

        }

        .footer{
            width: 110vw;
            height: 10vh;
            margin-top: 5vmin;

            .iconarea{
                width: 30vw;
                font-size: 8pt;
                margin-left: 35vmin;
                top: 4vmin;
            }

            ul{
                width: 70vw;
                font-size: 8pt;
                margin-left: 15vmin;
                top: 7.5vmin;
            }
        }

    }

    @media(max-width:576px){
        .logo{
            height: 12vh;
            text-align: center;
            margin-top: 5vmin;
        }

        .header{
            height: 8vh;
            margin-left: 13vmin;
            background-color: #FBF8F1;

            .container-fluid{
                background-color: #FBF8F1;

                ul{
                    height: 33vh;
                    overflow: scroll;
                    overflow-x: hidden;
                    z-index: 3;
                }
            }
        }

        .firstItem{
            width: 80vw;
            height: 30vh;
            margin-left: 20vmin;
            z-index: -1;

            img{
                height: 28vh;
            }
        }

        .secondItem{
            height: 30vh;
            margin-left: 10vmin;

            img{
                width: 23vw;
                height: 28vh;
            }

            .text{
                width: 20vw;
                height: 28vh;
                margin-left: 5vmin;
                margin-top: 2vmin;

                span{
                    font-size: 18pt;
                }

                p{
                    font-size: 8pt;
                    margin-top: 0;
                }

                button{
                    font-size: 3vmin;
                    margin-left: 0;
                }
            }
        }

        .thirdItem{
            height: 30vh;
            margin-left: 12vmin;

            img{
                width: 23vw;
                height: 28vh;
            }

            .text{
                width: 20vw;
                height: 28vh;
                margin-top: 2vmin;
                margin-right: 3vmin;

                span{
                    font-size: 15pt;
                }

                p{
                    font-size: 8pt;
                    margin-top: 0;
                }

                button{
                    font-size: 3vmin;
                    margin-left: 0;
                    margin-top: 0;
                }
            }

        }

        .forthItem{
            width: 80vw;
            height: 30vh;
            margin-left: 20vmin;
            margin-bottom: 6vmin;

            img{
                height: 28vh;
            }
        }

        .circle{
            bottom: 50%;
        }

        .gridContainer{
            height: 175vh;
            margin-left: 18.5vmin;
            margin-bottom: 18vmin;
            grid-gap: 5px;

            &::before{
                top: 38%;
                border: 60vmin solid #FFCBCB;
                border-color: transparent #FFCBCB transparent transparent;
                right: 0;
            }
            

            span{
                font-size: 22pt;
                color: lightslategrey;
                margin-top: 0;
                margin-left: 7vmin;
            }

            P{
                font-size: 20pt;
                margin-top: 5vmin;
            }


            .item{
                img{
                    width: 23vw;
                    height: 20vh;
                }
            }

        }

        .footer{
            width: 110vw;
            height: 10vh;
            margin-top: 20vmin;

            .iconarea{
                width: 30vw;
                font-size: 8pt;
                margin-left: 37vmin;
            }

            ul{
                width: 70vw;
                font-size: 8pt;
                margin-left: 14vmin;
                top: 10vmin;
            }
        }

    }

    @media(max-width:414px){
        .logo{
            height: 15vh;
            margin-left: 6vmin;
        }

        .header{
            height: 8vh;
            background-color: #FBF8F1;

            .container-fluid{
                background-color: #FBF8F1;

                ul{
                    height: 30vh;
                    overflow: scroll;
                    overflow-x: hidden;
                }
            }
        }

        .firstItem{
            margin-left: 20vmin;
        }

        .secondItem{

            .text{
                margin-top: 0;

                span{
                    font-size: 16pt;
                }

                p{
                    font-size: 6pt;
                    margin: 0;

                }

                button{
                    font-size: 2vmin;
                }
            }
        }

        .thirdItem{
            height: 30vh;
            margin-left: 12vmin;

            .text{

                span{
                    font-size: 13pt;
                }

                p{
                    font-size: 6pt;
                    margin: 0
                }

                button{
                    font-size: 2vmin;
                }
            }

        }

        .forthItem{
            margin-left: 20vmin;
        }

        .circle{
            bottom: 48%;
        }

        .gridContainer{
            margin-left: 17vmin;

            &::before{
                top: 39%;
                border: 55vmin solid #FFCBCB;
                border-color: transparent #FFCBCB transparent transparent;
                right: 0;
            }
            

            span{
                font-size: 20pt;
                margin-left: 5vmin
            }

            P{
                font-size: 17pt;
            }
        }

        .footer{

            .iconarea{
                margin-left: 38vmin;
            }

            ul{
                font-size: 7pt;
                margin-left: 15vmin;
            }
        }

    }

</style>
