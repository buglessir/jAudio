# jAudio
A jQuery plugin for convert &lt;A> tags to simple audio player


## How to use ?

First add jAudio css file between head tag :

``` html
<link rel="stylesheet" href="jquery.jAudio.css">
```

Add the latest version of jQuery and after that insert jAudio script file :

``` html
<script type="text/javascript" src="jquery.min.js"></script>
<script type="text/javascript" src="jquery.jAudio-1.0.0.js"></script>
```

Add your <a> tags :
  
``` html
<a href="sound.mp3">Sample Music One</a>
<br>
<a href="sound.mp3">Sample Music Two</a>
<br>
<a href="sound.mp3">Sample Music Three</a>
```

Now select <a> tags and make jAudio players :
  
``` html
<script type="text/javascript">
    $('a').jAudio();
</script>
```

Consider, This just supported MP3 file formats.

