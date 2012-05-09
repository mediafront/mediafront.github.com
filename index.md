---
layout: page
osmplayer:
  template: default
  debug: true
tagline: Open Source Media
---
{% include JB/setup %}
<script type="text/javascript">
  $(function() {
    $("#osmplayer").osmplayer({
      playlist: '/assets/osmplayer/playlist.xml',
      logo: '/assets/osmplayer/logo.png',
      height: '400px'
    });
  });
</script>
<div class="row">
  <div class="span12">
    <div class="alert">
      Notice anything different? MediaFront is evolving!  With the latest 2.0 release of the Open Standard Media Player, we are also working very hard to bring you a new http://mediafront.org website.  There will be a lot of changes around here, so check back regularly!
    </div>
  </div>
</div>
<div class="row">
  <div class="span4">
    <p>The mediafront platform is an open source (GPLv3) front end media solution for the web. Through its <a href="http://drupal.org/project/mediafront">integration with popular content management systems</a>, it employs an innovative and intuitive interface that allows any website administrator to completely customize the front end media experience for their users without writing any code!
    In addition, this platform offers two industry changing - open source media players that can be used free of charge on any website! Including the Open Standard Media (OSM) Player ( as shown ), which is an open source (GPLv3) all-in-one HTML5 media player for the web!</p>
    We hope you enjoy MediaFront!
  </div>
  <div class="span8">
    <h3>Introducing the Open Standard Media Player 2.0!</h3>
    <div id="osmplayer"></div>
  </div>
</div>
<div class="row">
  <div class="span8">
    <h3>Thank you to our Sponsors!</h3>
    <a href="http://alethia-inc.com/"><img src="/assets/sponsors/alethia.png" /></a>
    <a href="http://cybersafe.com/"><img src="/assets/sponsors/cyber_logo.png" /></a>
    <a href="http://www.mile3.com/"><img src="/assets/sponsors/mile3.png" /></a>
  </div>
</div>