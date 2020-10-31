---
description: position定位
---

## position定位

### 静态定位 `static`
```css
position: static;
```

### 固定定位 `fixed`

<div id="fixed">
</div>
<style>
  #fixed{
    position: fixed;
    top: 1em;
    right: 1em;
    width: 20%;
    background: #0091cc;
  }
</style>

```css
position: fixed;
```

### 粘性定位 sticky

<style>
  #content-wrapper .inner{
    display: flex;
    min-height: 100vh;
  }
  #content-wrapper .inner section{
    flex: 1 80%;
  }
  #content-wrapper .inner aside{
    flex: 20%;
    position: sticky;
    top: 1em;
  }
  
</style>
