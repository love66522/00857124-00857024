<!DOCTYPE html>
<html>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="style.css">
<body>
<table width="800" border="0" align="center" cellpadding="10" cellspacing="0">
        <tr> 
          <td align="center"> 
                  <table width="200" border="0" cellspacing="0" cellpadding="0" align="center">
                    <tr> 
                      <td align="center" bgcolor="6FE3E3"  color="#FFFFFF"; class="title">基隆美食</td>
                    </tr>
                  </table>
          </td>
        </tr>
</table>
<div class="w3-content" style="max-width:800px;position:relative;margin-left: auto; margin-right: auto;">

<a href="page2.html"><img class="mySlides" src="https://cdn.walkerland.com.tw/images/upload/poi/p27177/m25490/d3b0cb3e0c093b0d00f872d23ed87d6ca519c5d6.jpg" style="width:100%;height:80%" title="阿華炒麵"><br></a>
<a href="page3.html"><img class="mySlides" src="https://images.zi.org.tw/meidin/2019/11/19212439/1574169877-dacb83a91616d9dc888ddfc5a45819f3.jpg" style="width:100%;height:80%" title="暖鍋物" ><br></a>
<a href="page2.html"><img class="mySlides" src="3.jpg" style="width:100%;height:80%" title="不厭亭" ></a>
<a href="page2.html"><img class="mySlides" src="4.jpg" style="width:100%;height:80%" title="外木山" ></a>
<a href="page2.html"><img class="mySlides" src="5.png" style="width:100%;height:80%" title="情人湖" ></a>

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
      <a href="B98570016.pptx" shape="rect">說明文件</a>
    </div> 
 </div>
</body>
</html> 

