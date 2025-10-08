# Waline_Bang_Dream_emoji
Bang Dream emoji for Waline
```
//cdn.jsdelivr.net/gh/Sanksu/Waline_Bang_Dream_emoji@1.8.0/src/BangDream/
//cdn.jsdelivr.net/gh/Sanksu/Waline_Bang_Dream_emoji@1.8.0/src/Popipa/
//cdn.jsdelivr.net/gh/Sanksu/Waline_Bang_Dream_emoji@1.8.0/src/Afterglow/
//cdn.jsdelivr.net/gh/Sanksu/Waline_Bang_Dream_emoji@1.8.0/src/RAS/
//cdn.jsdelivr.net/gh/Sanksu/Waline_Bang_Dream_emoji@1.8.0/src/PastelPalettes/
//cdn.jsdelivr.net/gh/Sanksu/Waline_Bang_Dream_emoji@1.8.0/src/Mygo/
//cdn.jsdelivr.net/gh/Sanksu/Waline_Bang_Dream_emoji@1.8.0/src/AveMujica/
```
## Example:
```
<div id="waline"></div>
<script type="module">
  import { init } from 'https://unpkg.com/@waline/client@v3/dist/waline.js';

  init({
    el: '#waline',
    serverURL: '<YOUR SERVER URL>',

    // 设置 emoji
    emoji: [
      '//cdn.jsdelivr.net/gh/Sanksu/Waline_Bang_Dream_emoji@1.8.0/src/BangDream/',
      '//cdn.jsdelivr.net/gh/Sanksu/Waline_Bang_Dream_emoji@1.8.0/src/Popipa/',
      '//cdn.jsdelivr.net/gh/Sanksu/Waline_Bang_Dream_emoji@1.8.0/src/Afterglow/',
      '//cdn.jsdelivr.net/gh/Sanksu/Waline_Bang_Dream_emoji@1.8.0/src/RAS/',
      '//cdn.jsdelivr.net/gh/Sanksu/Waline_Bang_Dream_emoji@1.8.0/src/PastelPalettes/',
      '//cdn.jsdelivr.net/gh/Sanksu/Waline_Bang_Dream_emoji@1.8.0/src/Mygo/',
      '//cdn.jsdelivr.net/gh/Sanksu/Waline_Bang_Dream_emoji@1.8.0/src/AveMujica/',
    ],
  });
</script>
```
