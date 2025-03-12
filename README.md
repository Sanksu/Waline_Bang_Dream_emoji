# Waline_Bang_Dream_emoji
Bang Dream emoji for Waline
```
//cdn.jsdelivr.net/gh/Sanksu/Waline_Bang_Dream_emoji@1.6.0/src/BangDream/
//cdn.jsdelivr.net/gh/Sanksu/Waline_Bang_Dream_emoji@1.6.0/src/Mygo/
//cdn.jsdelivr.net/gh/Sanksu/Waline_Bang_Dream_emoji@1.6.0/src/Popipa/
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
      '//cdn.jsdelivr.net/gh/Sanksu/Waline_Bang_Dream_emoji@1.6.0/src/BangDream/',
      '//cdn.jsdelivr.net/gh/Sanksu/Waline_Bang_Dream_emoji@1.6.0/src/Mygo/',
      '//cdn.jsdelivr.net/gh/Sanksu/Waline_Bang_Dream_emoji@1.6.0/src/Popipa/',
    ],
  });
</script>
```
