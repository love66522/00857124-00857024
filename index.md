<html>
<title>fooooods</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="style.css">
<body>

                      <h2>基隆美食</h2>
<div class="w3-content" style="max-width:800px;position:relative;margin-left: auto; margin-right: auto;">

<a href="page2.html"><img class="mySlides" src="https://cdn.walkerland.com.tw/images/upload/poi/p27177/m25490/d3b0cb3e0c093b0d00f872d23ed87d6ca519c5d6.jpg" style="width:100%;height:80%" title="阿華炒麵"><br></a>
<a href="page3.html"><img class="mySlides" src="https://images.zi.org.tw/meidin/2019/11/19212439/1574169877-dacb83a91616d9dc888ddfc5a45819f3.jpg" style="width:100%;height:80%" title="暖鍋物" ><br></a>
<a href="page4.html"><img class="mySlides" src="https://media-cdn.tripadvisor.com/media/photo-s/15/c6/6e/1c/10.jpg" style="width:100%;height:80%" title="張記魚丸" ></a>
<a href="page5%20.html"><img class="mySlides" src="https://lh3.googleusercontent.com/DHNhl7_qpbp7FEyCAyvheRYk4fRHCR3Aov1REZy6svY3IItyjcUOu35X3sUPjvrau-zs0xae_J02ravX98fyUX6x_yApHlg=s600" style="width:100%;height:80%" title="聖托里尼海景餐廳" ></a>
<a href="page6%20.html"><img class="mySlides" src="https://img.tiffany0118.com/uploads/20191101134101_20.jpg" style="width:100%;height:80%" title="海龍珠海鮮餐廳" ></a>

<a class="w3-btn-floating" style="position:absolute;top:45%;left:0" onclick="plusDivs(-1)"> ❮ </a>
<a class="w3-btn-floating" style="position:absolute;top:45%;right:0" onclick="plusDivs(1)"> ❯ </a>

</div>

<script>
var slideIndex = 1;
showDivs(slideIndex);

function plusDivs(n) {
  showDivs(slideIndex += n);
}

function showDivs(n) {
  var i;
  var x = document.getElementsByClassName("mySlides");
  if (n > x.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = x.length} ;
  for (i = 0; i < x.length; i++) {
     x[i].style.display = "none";  
  }
  x[slideIndex-1].style.display = "block";  
}
</script>
 <div id="footerWrapper"> 
    <div id="footer"> 
      <a href="00857124+00857024.pptx" shape="rect">說明文件</a>
    </div> 
 </div>
</body>
</html> 

