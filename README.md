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
       <img src="https://image.shutterstock.com/image-illustration/ethereum-hits-new-record-neon-260nw-1958528764.jpg" height="100px"/>
       <img src="https://ichef.bbci.co.uk/news/640/cpsprodpb/FD37/production/_116432846_mediaitem116432845.jpg" height="100px"/>
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
