---
layout: article
title: Broadcast
permalink: /broadcast
---
<head> 
  <script type="text/javascript" src="//player.wowza.com/player/latest/wowzaplayer.min.js"></script> 
</head>
<body> 
  <div id="playerElement" style="width:100%; height:0; padding:0 0 56.25% 0"></div> 
  <script type="text/javascript">
  WowzaPlayer.create("playerElement",
      {
      "license":"PLAY2-6rcFk-h6Xpx-mrnGu-yxGn8-BVaRc",
      "sources":[{
      "sourceURL":"http://205.123.31.30:1935/live/Channel01/playlist.m3u8?DVR"
      },
      {
      "sourceURL":""
      }],
      "title":"KAPS News Broadcast",
      "description":"",
      "autoPlay":true,
      "mute":false,
      "volume":75
      }
  );
  </script>
</body>
