# 使用

---



````html
<input id="input" placeholder="ctrl+enter"/>
````

````javascript
seajs.use(['index','jquery'], function(Kemo,$) {
  Kemo(document).on('keydown', '.input,#input', 'ctrl+return', function(e) {
    alert('ctrl+enter normal');
  }).on('keydown', null, 'up', function(e) {
    e.preventDefault();
    console.log('up');
  }).on('keydown', null, 'down', function(e) {
    e.preventDefault();
    console.log('down');
  })
  $('#input').before('<input class="input" placeholder="ctrl+enter 2"/>');
  $('#input').before('<input class="input" placeholder="ctrl+enter 3"/>');
});
````