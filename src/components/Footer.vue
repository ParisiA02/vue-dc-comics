<template>
  <footer>
      <div class="upper-footer">
          <div class="left-upper-footer">
                <div class="footer-links">
                    <h3>DC COMICS</h3>
                    <ul>
                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>TV</li>
                        <li>Games</li>
                        <li>Videos</li>
                        <li>News</li>
                    </ul>
                </div>
                <div class="footer-links">
                    <h3>DC</h3>
                    <ul>
                        <li>Term Of Use</li>
                        <li>Privacy policy</li>
                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>TV</li>
                        <li>Games</li>
                        <li>Videos</li>
                        <li>News</li>
                    </ul>
                </div>
                <div class="footer-links">
                    <h3>SITES</h3>
                    <ul>
                        <li>Term Of Use</li>
                        <li>Privacy policy</li>
                        <li>Characters</li>
                        <li>Comics</li>
                    </ul>
                </div>
                <div class="footer-links">
                    <h3>SHOP</h3>
                    <ul>
                        <li>Term Of Use</li>
                        <li>Privacy policy</li>
                    </ul>
                </div>            
          </div>
          <div class="right-upper-footer">
          </div>
      </div>
      <div class="under-footer">
            <div class="under-footer-container">
                <div class="left-under-footer">
                    <button class="btn footer-btn">SING-UP NOW!</button>
                </div>
                <div class="right-under-footer">
                    <span class="footer-text">FOLLOW US</span>
                    <ul>
                        <li><img src="../assets/footer-facebook.png" alt="facebook icon"></li>
                        <li><img src="../assets/footer-twitter.png" alt="twitter icon"></li>
                        <li><img src="../assets/footer-youtube.png" alt="youtube icon"></li>
                        <li><img src="../assets/footer-pinterest.png" alt="pinterest icon"></li>
                        <li><img src="../assets/footer-periscope.png" alt="periscope icon"></li>
                    </ul>
                </div>
            </div>
      </div>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    footer{
        width: 100%;
        height: 400px;
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
        background-image: url("../assets/footer-bg.jpg");

        .upper-footer{
            width: 60%;
            height: 300px;
            margin: auto;

            .left-upper-footer{
                width: 50%;
                height: 100%;
                float: left;
                text-align: left;
                display: flex;
                flex-wrap: wrap;

                .footer-links{
                    margin-top: 10px;
                    margin-right: 50px;
                    color: white;

                    h3{
                        margin-bottom: 10px;
                    }

                    li{
                        list-style-type: none;
                        color: grey;
                    }
                }
            }

            .right-upper-footer{
                width: 50%;
                height: 100%;
                float: right;
                background-position: center;
                background-repeat: no-repeat;
                background-image: url("../assets/dc-logo-bg.png");
            }
        }
        .under-footer{
            width: 100%;
            height: 100px;
            background-color: #303030;

            .under-footer-container{
                width: 60%;
                height: 100%;
                margin: auto;
                display: flex;
                    
                .left-under-footer{
                    width: 50%;
                    height: 100%;
                    display: flex;
                    align-items: center;

                    .btn.footer-btn{
                        float: left;
                    }
                }

                .right-under-footer{
                    width: 50%;
                    height: 100%;
                    display: flex;
                    align-items: center;
                    justify-content: flex-end;

                    .footer-text{
                        font-size: 30px;
                        font-weight: bold;
                        color: #0282F9;
                    }

                    ul{
                        margin-left: 30px;
                        display: flex;

                        li{
                            list-style-type: none;
                            margin-right: 20px;
                        }
                    }
                }
            }
        }
        .btn{
            width: 150px;
            height: 50px;
            background-color: transparent;
            color: white;
            border: 2px solid #0282F9;
        }
    }
</style>
