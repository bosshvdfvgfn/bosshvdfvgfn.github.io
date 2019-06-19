# bosshvdfvgfn.github.io
body{
    background-color: tomato;
}
.center{
    text-align: center;
}
h1.center{
    color: black;
}
.btn {
    background-color: rgb(33, 243, 68);
    color: black;
    padding: 16px;
    font-size: 16px;
    border: none;
    outline: none;
  }

  .dropdown {
    position: absolute;
    display: inline-block;
  }
  
  .dropdown-content {
    display: none;
    position: absolute;
    background-color: #f1f1f1;
    min-width: 160px;
    z-index: 1;
  }
  
  .dropdown-content a {
    color: red;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
  }
  
  .dropdown-content a:hover {background-color: #ddd}
  
  .dropdown:hover .dropdown-content {
    display: block;
  }
  
  .btn:hover, .dropdown:hover .btn  {
    background-color: #0b7dda;
  }
  .popup {
    position: relative;
    display: inline-block;
    cursor: pointer;
  }
  
  .popup .popuptext {
    visibility: hidden;
    width: 400px;
    background-color: #555;
    color: #fff;
    text-align: center;
    border-radius: 6px;
    padding: 8px 0;
    position: absolute;
    z-index: 1;
    bottom: 125%;
    left: 50%;
    margin-left: -80px;
  }
  
  .popup .popuptext::after {
    content: "";
    position: absolute;
    top: 100%;
    left: 50%;
    margin-left: -5px;
    border-width: 5px;
    border-style: solid;
    border-color: #555 transparent transparent transparent;
  }
  
  .popup .show {
    visibility: visible;
    -webkit-animation: fadeIn 1s;
    animation: fadeIn 1s
  }
  
  @-webkit-keyframes fadeIn {
    from {opacity: 0;} 
    to {opacity: 1;}
  }
  
  @keyframes fadeIn {
    from {opacity: 0;}
    to {opacity:1 ;}
  }

.modal {
  display: none; 
  position: fixed;
  z-index: 1; 
  left: 0;
  top: 0;
  height: 100%; 
  overflow: auto; 
  background-color: rgb(0,0,0); 
  background-color: rgba(0,0,0,0.4); 
}

.modal-content {
  background-color: #fefefe;
  margin: 15% auto; 
  padding: 20px;
  border: 1px solid #888;
  width: 30%;
}

.close {
  color: #aaa;
  float: right;
  font-size: 28px;
  font-weight: bold;
}

.close:hover,
.close:focus {
  color: black;
  text-decoration: none;
  cursor: pointer;
}
* {box-sizing:border-box}

.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
}

.mySlides {
  display: none;
}

.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  margin-top: -22px;
  padding: 16px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
}

.text {
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active, .dot:hover {
  background-color: #717171;
}

.fade {
  -webkit-animation-name: fade;
  -webkit-animation-duration: 1.5s;
  animation-name: fade;
  animation-duration: 1.5s;
}

@-webkit-keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}
<!DOCTYPE html>
<html>
<head>
<title>Kittipong Yoonirundorn</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
    <link rel="stylesheet" href="test(CSS).css">
    <link rel="stylesheet" href="D:\">
</head>
<body>
<h1 class="center" style="font-family:'Courier New', Courier, monospace">Welcome to me site</h1>
    <div class="center">
        <img src="https://scontent.fbkk14-1.fna.fbcdn.net/v/t1.0-9/26167534_1273701816068424_8251963759742830982_n.jpg?_nc_cat=111&_nc_eui2=AeEEQDmRh4OPw1bvQyhdvYxszCKVem5bxLnZXvcDeRYOL93hR9g2vP1xCNrankJ2YbctJEvON5gjsSRgtv12tFZOKD3l0aPdUSEWC6AVZYpLLQ&_nc_oc=AQmJ3dqBLu3WnA9gksJtanTA2F4_haDfz5PrwcWxhQStFU1x0HhBVE2dkkMEbVh7yRi5ItHu1W04oG1BcSZGPasN&_nc_ht=scontent.fbkk14-1.fna&oh=f395a345242c5966124e1639ae1f9ef2&oe=5D841B86" width="380" height="400">
    </div>

        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
        <button class="btn">Menu</button>
        <div class="dropdown">
            <button class="btn" style="border-left:1px solid rgb(47, 128, 0)">
                <i class="fa fa-caret-down"></i>
            </button>
            <div class="dropdown-content">
                <div class="popup" onclick="myFunction()">About me
                    <span class="popuptext" id="myPopup">My name is Kittipong Yoonirundorn I'm 21 years old. I'm study at Kasetsart university Faculty of Computer Science. Now in year 2, going up year 3, Free time, I like to watch movies, listen to music and coding. My favorite sport is basketball. I have twins, he studying at Thammasat university Faculty of Civil Engineering.</span>
                </div>
                <script>
                        function myFunction() {
                          var popup = document.getElementById("myPopup");
                          popup.classList.toggle("show");
                        }
                        </script>
            </div>
        </div>

        <div class="center">
            <button id="myBtn">Photo</button>
            <div id="myModal" class="modal">
                <div class="modal-content">
                    <span class="close">&times;</span>  
                    <div class="slideshow-container">
                        <div class="mySlides fade">
                          <div class="numbertext">1 / 3</div>
                          <img src="https://scontent.fbkk14-1.fna.fbcdn.net/v/t1.0-9/1509199_452387534866527_88718471_n.jpg?_nc_cat=104&_nc_oc=AQnO7ijCAS3eo6GHqL_QoxTQaHtBU9-Q3M0PvBBm9f5eo8RJ3zXHVP0lAukCTbmmyYY&_nc_ht=scontent.fbkk14-1.fna&oh=a440fa763c0ae9a5453c2ccced5b6ece&oe=5D83B954" width="380" height="400">
                        </div>
                      
                        <div class="mySlides fade">
                          <div class="numbertext">2 / 3</div>
                          <img src="https://scontent.fbkk14-1.fna.fbcdn.net/v/t1.0-9/1655833_476033192501961_1585920130_n.jpg?_nc_cat=106&_nc_oc=AQlIZuSxqOm3H95qP44X8FOaNj2Fhx_Uo6XExZVVOW0fDXmBwn-PZ8TeMtZPMveB2Qw&_nc_ht=scontent.fbkk14-1.fna&oh=a7bd320552d006f9ca538cd6a54f0aab&oe=5D79C7A8" width="380" height="400">
                        </div>
                      
                        <div class="mySlides fade">
                          <div class="numbertext">3 / 3</div>
                          <img src="https://scontent.fbkk10-1.fna.fbcdn.net/v/t1.0-9/12342682_751447118293899_4339689312507198545_n.jpg?_nc_cat=102&_nc_oc=AQn8o5vA5o4HqBZMDvlSDlErJ1PCelEFO6mbaAfGGrm_hQXGIh69Dvs3XMTDIqscGu4&_nc_ht=scontent.fbkk10-1.fna&oh=258deb66b4ba055291447579d3e865de&oe=5DC4C23A" width="380" height="400">
                        </div>
                      </div>
                      <br>
                      
                      <div style="text-align:center">
                        <span class="dot" onclick="currentSlide(1)"></span> 
                        <span class="dot" onclick="currentSlide(2)"></span> 
                        <span class="dot" onclick="currentSlide(3)"></span> 
                      </div>
                    <script>
                            var slideIndex = 0;
                            showSlides();
                            function showSlides() {
                              var i;
                              var slides = document.getElementsByClassName("mySlides");
                              var dots = document.getElementsByClassName("dot");
                              for (i = 0; i < slides.length; i++) {
                                slides[i].style.display = "none";  
                              }
                              slideIndex++;
                              if (slideIndex > slides.length) {slideIndex = 1}    
                              for (i = 0; i < dots.length; i++) {
                                dots[i].className = dots[i].className.replace(" active", "");
                              }
                              slides[slideIndex-1].style.display = "block";  
                              dots[slideIndex-1].className += " active";
                              setTimeout(showSlides, 2000); 
                            }
                            </script>
                </div>
            </div>
            <script>
                var modal = document.getElementById("myModal");
                var btn = document.getElementById("myBtn");
                var span = document.getElementsByClassName("close")[0];
                btn.onclick = function() {
                    modal.style.display = "block";
                }
                span.onclick = function() {
                    modal.style.display = "none";
                }
                window.onclick = function(event) {
                    if (event.target == modal) {
                        modal.style.display = "none";
       
