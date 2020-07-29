# websitePertamaByme

<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8" />
        <title>Mami's Diner & Daddy's Carwash</title>
        <link rel="stylesheet" href="styles.css">
    </head>
    <body>
        <div class="container">
            <div class="nav-wrapper">
                <div class="left-side">
                    <div class="nav-link-wrapper active-nav-link">
                        <a href="index.html">HOME</a>
                    </div>

                    <div class="nav-link-wrapper">
                        <a href="About.html">ABOUT</a>
                    </div>
                    
                </div>

                <div class="right-side">
                    <div class="brand">
                        <div>Mami's DIner & Daddy's Carwash</div>
                    </div>
                </div>
            </div>
            <div class="content-wrapper">
                <div class="portfolio-items-wrapper">
                    
                    <div class="portfolio-item-wrapper">
                        <div class="portfolio-img-background" style="background-image:url(gambar/foto2.jpg);"></div>
                        
                        <div class="img-text-wrapper">
                            <div class="logo-wrapper">
                                <img src="gambar/spoon.png">
                            </div>
                            <div class="subtitle">
                                Check out our authentic American food!
                            </div>
                        </div>
                    </div>
                

                    <div class="portfolio-item-wrapper">
                        <div class="portfolio-img-background" style="background-image:url(gambar/foto1.jpg)"></div>
                        
                        <div class="img-text-wrapper">
                            <div class="logo-wrapper">
                                <img src="gambar/fork1.png">
                            </div>
                            <div class="subtitle">
                                Check out our authentic American food!
                            </div>
                        </div>
                    </div>
                
                    
                   <div class="portfolio-item-wrapper">
                        <div class="portfolio-img-background" style="background-image:url(gambar/foto3.jpg)";></div>
                        
                        <div class="img-text-wrapper">
                            <div class="logo-wrapper">
                                <img src="gambar/spoon.png">
                            </div>
                            <div class="subtitle">
                                Check out our authentic American food!
                            </div>
                        </div>
                    </div>

                    <div class="portfolio-item-wrapper">
                        <div class="portfolio-img-background" style="background-image:url(gambar/foto4.jpg);"></div>
                        
                        <div class="img-text-wrapper">
                            <div class="logo-wrapper">
                                <img src="gambar/hot.png">
                            </div>
                            <div class="subtitle">
                                Check out our authentic American food!
                            </div>
                        </div>
                    </div>

                    <div class="portfolio-item-wrapper">
                        <div class="portfolio-img-background" style="background-image:url(gambar/foto5.jpg);"></div>
                        
                        <div class="img-text-wrapper">
                            <div class="logo-wrapper">
                                <img src="gambar/burg.png">
                            </div>
                            <div class="subtitle">
                                Check out our authentic American food!
                            </div>
                        </div>
                    </div>
                
                    <div class="portfolio-item-wrapper">
                        <div class="portfolio-img-background" style="background-image:url(gambar/foto6.jpg);"></div>
                        
                        <div class="img-text-wrapper">
                            <div class="logo-wrapper">
                                <img src="gambar/sand.png">
                            </div>
                            <div class="subtitle">
                                Check out our authentic American food!
                            </div>
                        </div>
                    </div>
                
                
                </div>

            </div>
        </div>
    </body>
    <script>
        const portfolioItems = document.querySelectorAll('.portfolio-item-wrapper')

        portfolioItems.forEach(portfolioItem =>{
            portfolioItem.addEventListener('mouseover',() => {
                console.log(portfolioItem.childNodes[1].classList);
                portfolioItem.childNodes[1].classList.add('img-darken');

            })

            portfolioItem.addEventListener('mouseout',() => {
                portfolioItem.childNodes[1].classList.remove('img-darken');

            })
        })
    </script>
    
</html>
