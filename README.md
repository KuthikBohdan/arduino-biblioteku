<!DOCTYPE html>
<html>
     <link rel="rdrsheet"
            href="rdr.css">
<head>
    <style>
        .screenpage { display: none; }
.show { display: block }
    </style>
    <script src="/scripts/snippet-javascript-console.min.js?v=1"></script>
</head>
<body>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>
<div class=container>
  <div id="page0" class="screenpage show">
       <nav><a href="https://github.com/KuthikBohdan/randoms/edit/main/README.md"> <img src="https://image.shutterstock.com/image-illustration/ethereum-hits-new-record-neon-260nw-1958528764.jpg" height="100px"/></a></nav>
       <img src="https://ichef.bbci.co.uk/news/640/cpsprodpb/FD37/production/_116432846_mediaitem116432845.jpg" height="100px"/>
    <a href="https://github.com/KuthikBohdan/randoms/edit/main/README.md">   <img src="https://st.depositphotos.com/1637332/2929/v/450/depositphotos_29298565-stock-illustration-button-down-arrow-pointer.jpg" width="300px"  height="370px"</a>
       <a href="sample.html"><img src="https://thumb.tildacdn.com/tild6264-6339-4238-b636-346565623037/-/format/webp/0-02-05-6822e8ca7678.jpg" width="300px"  height="370px"</a>
        <a href="sample.html"><img src="https://thumb.tildacdn.com/tild6664-3965-4361-b631-663461643039/-/format/webp/0-02-05-6d20ecf00906.jpg" width="300px"  height="370px"</a>
          <a href="sample.html"><img src="https://thumb.tildacdn.com/tild6264-6339-4238-b636-346565623037/-/format/webp/0-02-05-6822e8ca7678.jpg" width="300px"  height="370px"</a>
    <div class="close">close</div>
  </div>
  <div id="page1" class="screenpage">2
    <div class="close">close</div>
  </div>
  <div id="page2" class="screenpage">3
    <div class="close">close</div>
  </div>
  <div id="page3" class="screenpage">4
    <div class="close">close</div>
  </div>
  <div id="page4" class="screenpage">5
    <div class="close">close</div>
  </div>
  <div id="page5" class="screenpage">6
    <div class="close">close</div>
  </div>
  <div id="page6" class="screenpage">7
    <div class="close">close</div>
  </div>
  <div id="page7" class="screenpage">8
    <div class="close">close</div>
  </div>
  <div id="page8" class="screenpage">9
    <div class="close">close</div>
  </div>
  <div id="page9" class="screenpage">10
    <div class="close">close</div>
  </div>
</div>
    <script type="text/javascript">
        $('.close').click(function() {
  $('.screenpage:visible').hide().siblings().eq(Math.floor(Math.random() * 9)).show();
});
    </script>
</body>
</html>
