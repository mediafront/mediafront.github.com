---
layout: post
title: "minPlayer"
osmplayer:
  debug: true
  template: default
tagline: "because less IS more!"
category:
tags: []
---
{% include JB/setup %}

##Overview
The goal of minPlayer is to provide a slim, well documented, object oriented,
plugin-based "core" media player in which other players and libraries can build
on top of. It is written using object oriented JavaScript and is continuously
integrated using JSLint, JSDoc, and Google Closure.

###YouTube Integration
{% highlight html %}
<script type="text/javascript">
  $(function() {
    $("#youtube").minplayer();
  });
</script>
<video id="youtube" src="http://www.youtube.com/watch?v=dTAAsCNK7RA"></video>
{% endhighlight %}
<script type="text/javascript">
  $(function() {
    console.log('here');
    $("#youtube").minplayer();
  });
</script>
<div style="height:400px">
<video id="youtube" src="http://www.youtube.com/watch?v=dTAAsCNK7RA"></video>
</div>
<div style="clear:both;">&nbsp;</div>

###Vimeo Integration
{% highlight html %}
<script type="text/javascript">
  $(function() {
    console.log('here');
    $("#vimeo").minplayer();
  });
</script>
<video id="vimeo" src="http://vimeo.com/5606758"></video>
{% endhighlight %}
<script type="text/javascript">
  $(function() {
    console.log('here');
    $("#vimeo").minplayer();
  });
</script>
<div style="height:400px;">
  <video id="vimeo" src="http://vimeo.com/5606758"></video>
</div>
