# caduletas
Cadu Barletta
<link href="http://vjs.zencdn.net/6.0.0/video-js.css" rel="stylesheet">
<style>.video-js .vjs-time-control{display: none;}.video-js .vjs-progress-control{display: none;}</style>
<video id="player_webtv" class="video-js vjs-big-play-centered "  muted controls preload="auto" width="640" height="480" data-setup="{ 'fluid':true,'aspectRatio':'16:9' }" >
   <source src="http://stmv2.srvstm.com/cadubarletta/cadubarletta/playlist.m3u8" type="application/x-mpegURL">
</video>
<script src="//vjs.zencdn.net/6.0.0/video.js"></script>
<script src="//cdnjs.cloudflare.com/ajax/libs/videojs-contrib-hls/5.9.0/videojs-contrib-hls.min.js"></script>
<script>var myPlayer=videojs('player_webtv',{},function(){var player=this;player.on("pause",function(){player.one("play",function(){player.load();player.play();});});})</script>
