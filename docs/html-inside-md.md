---
title: html-inside-md
---

Because you **mix html and md**, 

<div style="margin-left: -100px; margin-right: -100px; border: 1px solid #eee; padding: 10px; text-align: center;">
it can contain any markup and even js
</div>

<div style="margin: 30px 0;">
For example <button onclick="incCounter()">click</button> <span id="counter">0</span>
</div>
<script>
function incCounter() {
	var span = document.getElementById('counter')
	var cur = parseInt(counter.innerText)
	counter.innerText = (cur + 1).toString()
}
</script>

```php
$v = array_map(fn($x) => $x+1, $arr);
```

