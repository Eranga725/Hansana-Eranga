<!DOCTYPE html>
<html lang="en">
    <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE-edge">
    <meta name="viewport" content="width-device-width, initial-scale=1.0">
    <title>My portfolio</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://kit.fontawesome.com/10dd7df1a0.js" crossorigin="anonymous"></script>
    </head>
    <body>
        <div id="header">
        <div class="container">
            <nav>
                <img src="images/logo.png" class="logo">
                <ul id="sidemenu">
                    <li><a href="#header">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#portfolio">Portfolio</a></li>
                    <li><a href="#contact">Contact</a></li>
                    <i class="fas fa-times" onclick="closemenu()"></i>
                </ul>
                <i class="fas fa-bars" onclick="openmenu()"></i>
            </nav>
            <div class="header-text">
                <p>UI/UX Designer</p>
                <h1>Hi, I'm<span> Hansana</span><br>Eranga From Sri lanka</h1>
            </div>
        </div>
        </div>

<!-- ----------About information-------- -->
        <div id="about">
                <div class="container">
                    <div class="row">
                        <div class="about-col-1">
                        <img src="images/user.png">
                        </div>
                        <div class="about-col-2">
                            <h1 class="sub-title">About Me</h1>
                            <p>I‘m a UX/UI Designer with over two years experience conceptualizing and crafting digital products,
                            helping businesses and non-profits expand their capacity for impact.</p>  
                            <div class="tab-titles">
                                <p class="tab-links active-link" onclick="opentab('skills')">Skills</p>
                                <p class="tab-links" onclick="opentab('experience')">Experience</p>
                                <p class="tab-links" onclick="opentab('education')">Education</p>
                            </div>
                            <div class="tab-contents active-tab" id="skills">
                                <ul>
                                    <li><span>UI/UX</span><br>Designing web/app interfaces</li>
                                    <li><span>NFT Design</span><br>Create Nft Artwork</li>
                                    <li><span>Logo Design</span><br>Company Logo,businesses</li>
                                </ul>
                            </div>
                            <div class="tab-contents" id="experience">
                                <ul>
                                    <li><span>2018-2021</span><br>Working with java institue advance technology</li>
                                    <li><span>2001-2022</span><br>learn and self-studies</li>
                                    <li><span>2019-2022</span><br>Start my own design platform</li>
                                </ul>
                            </div>
                            <div class="tab-contents" id="education">
                                <ul>
                                    <li><span>School</span><br>St'thomas collage matele</li>
                                    <li><span>Certificated courses</span><br>ocjp-java, digital markting</li>
                                    <li><span>Universitys</span><br>Undergraduate at Sri lanka technologycal campus</li>
                                </ul>
                            </div>
                            </div>
                    </div>
                </div>
        </div>
        <!---------------services--------------->
        <div id="services">
            <div class="container">
                <h1 class="sub-title">My Services</h1>
                <div class="services-list">
                    <div>
                        <i class="fa-solid fa-code"></i>
                        <h2>Web Design</h2>
                        <p>what's your idea into website.I'm familiar with css and javascript. And now i try to developed web using react</p>
                            <a href="#">Learn more</a>
                    </div>
                    <div>
                        <i class="fa-solid fa-hippo"></i>
                        <h2>NFT Design</h2>
                        <p>NFT Logo Disign, 100+ Collection Genarates, 1000+ Collection Genarates</p>
                            <a href="#">Learn more</a>
                    </div>
                    <div>
                        <i class="fa-solid fa-pen-nib"></i>
                        <h2>Logo Design</h2>
                        <p>Abstract mark, Moscot logo, combination mark, Emblem logo, Lettermark, Pictorial mark, Wordmark</p>
                            <a href="#">Learn more</a>
                    </div>
                </div>
            </div>
        </div>
<!-----------portfolio----------->
<div id="portfolio">
    <div class="container">
        <h1 class="sub-title">My Work</h1>
        <div class="work-list">
            <div class="work">
                <img src="images/work-1.png">
                <div class="layer">
                    <h3><b>Online market place App</b></h3>
                    <p>A long time ago I created an advertising website for selling vehicles. You can see that website in the link below.</p>
                    <a href="https://k8zh2k8u7yunmn3gscq38w.on.drv.tw/www.Unicorn.com/HOME.html"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                </div>
            </div>
            <div class="work">
                <img src="images/work-2.png">
                <div class="layer">
                    <h3><b>NFT</b></h3>
                    <p>You can create and Genarates any type of NFT art Collection you want</p>
                    <a href="https://www.instagram.com/p/CViK0XhPGOT/?utm_source=ig_web_copy_link"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                </div>
            </div>
            <div class="work">
                <img src="images/work-3.png">
                <div class="layer">
                    <h3><b>Graphic Design</b></h3>
                    <p>I am designing different kinds of graphic design like photoshop manipulation and flyer design. You can see an example below the link. </p>
                    <a href="https://www.instagram.com/hansanaeranga/"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                </div>
            </div>
        </div>
        <a href="#" class="btn">See more</a>
    </div>
</div>
<!-------------contact-->
<div id="contact">
    <div class="container">
        <div class="row">
            <div class="contact-left">
                <h1 class="sub-title">Contact Me</h1>
                <p><i class="fa-sharp fa-solid fa-paper-plane"></i>hansana.eranga.jayarathna2001@gmail.com</p>
                <p><i class="fa-solid fa-square-phone-flip"></i>0756558986</p>
                <div class="social-icons">
                    <a href="https://www.facebook.com/hansana.eranga"><i class="fa-brands fa-facebook"></i></a>
                    <a href="https://twitter.com/hjayarthna"><i class="fa-brands fa-twitter-square"></i></a>
                    <a href="https://www.instagram.com/hansanaeranga/"><i class="fa-brands fa-instagram"></i></a>
                    <a href="https://www.linkedin.com/in/hansana-eranga-22500123a/?originalSubdomain=lk"><i class="fa-brands fa-linkedin"></i></a>
                </div>
                <a href="images/my-cv.pdf" download class="btn btn2">Download Cv</a>
            </div>
            <div class="contact-right">
                <form name="submit-to-google-sheet">
                    <input type="text" name="Name" placeholder="Your Name" required>
                    <input type="email" name="Email" placeholder="Your Email" required>
                    <textarea name="Message" rows="6" placeholder="Your Message"></textarea>
                    <button type="submit" class="btn btn2">Submit</button>
                </form>
                <span id="msg"></span>
            </div>
        </div>
    </div>
    <div class="copyright">
        <p>copyright @ Hansana. Made with HEJ design</p>
    </div>
</div>


        <script>
            var tablinks = document.getElementsByClassName("tab-links")
            var tabcontents = document.getElementsByClassName("tab-contents")

            function opentab(tabname){
                for(tablink of tablinks){
                    tablink.classList.remove("active-link");
                }
                for(tabcontent of tabcontents){
                    tabcontent.classList.remove("active-tab");
                }
                event.currentTarget.classList.add("active-link");
                document.getElementById(tabname).classList.add("active-tab")
            }
        </script>
        <script>
            var sidemenu = document.getElementById("sidemenu");
            function openmenu(){
                sidemenu.style.right = "0";
            }
            function closemenu(){
                sidemenu.style.right = "-200px";
            }
        </script>
        <script>
            const scriptURL = 'https://script.google.com/macros/s/AKfycbxNVL5nNrxfTHxjlzPgE7-8NF0jZTkpTHVDqw0pHG4kNs5HqTfvoi3vCFLy_ee1iKjcKg/exec'
            const form = document.forms['submit-to-google-sheet']
            const msg = document.getElementById("msg")
            form.addEventListener('submit', e => {
              e.preventDefault()
              fetch(scriptURL, { method: 'POST', body: new FormData(form)})
                .then(response => {
                    msg.innerHTML = "Message sent successfully"
                    setTimeout(function(){
                        msg.innerHTML = ""
                    },5000)
                    form.reset()
                })
                .catch(error => console.error('Error!', error.message))
            })
          </script>
    </body>
</html>
