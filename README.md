# ubuntu-sinhala-font

download FM-Abhaya.ttf and put it under /usr/share/fonts/truetype/sinhala/

create ~/.config/fontconfig/conf.d/55-sinhala.conf as below,

```xml
<?xml version="1.0"?>
<!DOCTYPE fontconfig SYSTEM "fonts.dtd">
<fontconfig>
<alias>
  <family>sans-serif</family>
  <prefer>
   <family>UN-Abhaya</family>
   <family>FreeSerif</family>
  </prefer>
 </alias>

<alias>
  <family>serif</family>
  <prefer>
   <family>UN-Abhaya</family>
   <family>FreeSerif</family>
  </prefer>
 </alias>
</fontconfig>
```
