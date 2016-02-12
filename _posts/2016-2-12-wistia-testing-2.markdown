---
layout: post
title:  "Wistia Testing Page Second Edition"
date:   2016-2-12 15:13:06
categories: boston
author: Jay Holman
thumbnail:
---
<div>
<!-- Facebook Pixel Code -->
<script>
!function(f,b,e,v,n,t,s){if(f.fbq)return;n=f.fbq=function(){n.callMethod?
n.callMethod.apply(n,arguments):n.queue.push(arguments)};if(!f._fbq)f._fbq=n;
n.push=n;n.loaded=!0;n.version='2.0';n.queue=[];t=b.createElement(e);t.async=!0;
t.src=v;s=b.getElementsByTagName(e)[0];s.parentNode.insertBefore(t,s)}(window,
document,'script','//connect.facebook.net/en_US/fbevents.js');

fbq('init', '188988671466939');
fbq('track', "PageView");</script>
<noscript><img height="1" width="1" style="display:none"
src="https://www.facebook.com/tr?id=188988671466939&ev=PageView&noscript=1"
/></noscript>
<!-- End Facebook Pixel Code -->
</div>
Videos that I'm currently testing things on!
<div>
<script charset="ISO-8859-1" src="//fast.wistia.com/assets/external/E-v1.js" async></script><div class="wistia_responsive_padding" style="padding:177.5% 0 0 0;position:relative;"><div class="wistia_responsive_wrapper" style="height:100%;left:0;position:absolute;top:0;width:100%;"><div class="wistia_embed wistia_async_5f5bgx9sf1 videoFoam=true" style="height:100%;width:100%">&nbsp;</div></div></div>

</div>
<div>
<script>
window._wq = window._wq || [];

_wq.push({ "5f5": function(video) {

  video.bind("conversion", function(email) {

    console.log("This at least partly worked");
    fbq('track', 'Lead');
  });

}});
</script>
</div>
