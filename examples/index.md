# Usage

---


<style>
       * {font-family: Helvetica, Verdana, Arial; font-size:0.95em}
            .eventNotifier{width: 100px; float: left; color:navy; border: dotted 1px navy; padding: 4px; background-color:white; margin:3px}
            .dirty{border: solid 1px #0ca2ff; color:white; background-color:#0ca2ff}
</style>

````html

<input id="input" placeholder="ctrl+enter"/>

 <h2>Special Keys</h2><div id="_esc" class="eventNotifier">esc</div><div id="_tab" class="eventNotifier">tab</div><div id="_space" class="eventNotifier">space</div><div id="_return" class="eventNotifier">return</div><div
 id="_backspace" class="eventNotifier">backspace</div><div id="_scroll" class="eventNotifier">scroll</div><div id="_capslock" class="eventNotifier">capslock</div><div id="_numlock" class="eventNotifier">numlock</div><div id=
"_pause" class="eventNotifier">pause</div><div id="_insert" class="eventNotifier">insert</div><div id="_home" class="eventNotifier">home</div><div id="_del" class="eventNotifier">del</div><div id="_end" class="eventNotifier">

end</div><div id="_pageup" class="eventNotifier">pageup</div><div id="_pagedown" class="eventNotifier">pagedown</div><div id="_left" class="eventNotifier">left</div><div id="_up" class="eventNotifier">up</div><div id="_right"
class="eventNotifier">right</div><div id="_down" class="eventNotifier">down</div><div id="_f1" class="eventNotifier">f1</div><div id="_f2" class="eventNotifier">f2</div><div id="_f3" class="eventNotifier">f3</div><div id="_f4"
class="eventNotifier">f4</div><div id="_f5" class="eventNotifier">f5</div><div id="_f6" class="eventNotifier">f6</div><div id="_f7" class="eventNotifier">f7</div><div id="_f8" class="eventNotifier">f8</div><div id="_f9" class=
"eventNotifier">f9</div><div id="_f10" class="eventNotifier">f10</div><div id="_f11" class="eventNotifier">f11</div><div id="_f12" class="eventNotifier">f12</div><div style="clear: both;"/>

<h2>0-9 Digits</h2>
<div id="_1" class="eventNotifier">1</div>
<div id="_2" class="eventNotifier">2</div>
<div id="_3" class="eventNotifier">3</div>
<div id="_4" class="eventNotifier">4</div>
<div id="_5" class="eventNotifier">5</div>
<div id="_6" class="eventNotifier">6</div>
<div id="_7" class="eventNotifier">7</div>
<div id="_8" class="eventNotifier">8</div>
<div id="_9" class="eventNotifier">9</div>
<div id="_0" class="eventNotifier">0</div>
<div style="clear: both;"/>
<h2>A-Z Letters</h2>

<div id="_a" class="eventNotifier">a</div>
<div id="_b" class="eventNotifier">b</div><div id="_c" class="eventNotifier">c</div><div id="_d" class="eventNotifier">d</div><div id="_e" class="eventNotifier">e</div><div id="_f" class="eventNotifier">

f</div><div id="_g" class="eventNotifier">g</div><div id="_h" class="eventNotifier">h</div><div id="_i" class="eventNotifier">i</div><div id="_j" class="eventNotifier">j</div><div id="_k" class="eventNotifier">k</div><div id=
"_l" class="eventNotifier">l</div><div id="_m" class="eventNotifier">m</div><div id="_n" class="eventNotifier">n</div><div id="_o" class="eventNotifier">o</div><div id="_p" class="eventNotifier">p</div><div id="_q" class=
"eventNotifier">q</div><div id="_r" class="eventNotifier">r</div><div id="_s" class="eventNotifier">s</div><div id="_t" class="eventNotifier">t</div><div id="_u" class="eventNotifier">u</div><div id="_v" class="eventNotifier">v

</div><div id="_w" class="eventNotifier">w</div><div id="_x" class="eventNotifier">x</div><div id="_y" class="eventNotifier">y</div><div id="_z" class="eventNotifier">z</div><div style="clear: both;"/><h2>Special Modifiers</h2
><div style="clear: both;"/><strong>Ctrl</strong><div id="_Ctrl_a" class="eventNotifier">Ctrl+a</div><div id="_Ctrl_b" class="eventNotifier">Ctrl+b</div><div id="_Ctrl_c" class="eventNotifier">Ctrl+c</div><div id="_Ctrl_d"
class="eventNotifier">Ctrl+d</div><div id="_Ctrl_e" class="eventNotifier">Ctrl+e</div><div id="_Ctrl_f" class="eventNotifier">Ctrl+f</div><div id="_Ctrl_g" class="eventNotifier">Ctrl+g</div><div id="_Ctrl_h" class=
"eventNotifier">Ctrl+h</div><div id="_Ctrl_i" class="eventNotifier">Ctrl+i</div><div id="_Ctrl_j" class="eventNotifier">Ctrl+j</div><div id="_Ctrl_k" class="eventNotifier">Ctrl+k</div><div id="_Ctrl_l" class="eventNotifier">

Ctrl+l</div><div id="_Ctrl_m" class="eventNotifier">Ctrl+m</div><div id="_Ctrl_n" class="eventNotifier">Ctrl+n</div><div id="_Ctrl_o" class="eventNotifier">Ctrl+o</div><div id="_Ctrl_p" class="eventNotifier">Ctrl+p</div><div id
="_Ctrl_q" class="eventNotifier">Ctrl+q</div><div id="_Ctrl_r" class="eventNotifier">Ctrl+r</div><div id="_Ctrl_s" class="eventNotifier">Ctrl+s</div><div id="_Ctrl_t" class="eventNotifier">Ctrl+t</div><div id="_Ctrl_u" class=
"eventNotifier">Ctrl+u</div><div id="_Ctrl_v" class="eventNotifier">Ctrl+v</div><div id="_Ctrl_w" class="eventNotifier">Ctrl+w</div><div id="_Ctrl_x" class="eventNotifier">Ctrl+x</div><div id="_Ctrl_y" class="eventNotifier">
Ctrl+y</div><div id="_Ctrl_z" class="eventNotifier">Ctrl+z</div><div style="clear: both;"/><strong>Shift</strong><div id="_Shift_a" class="eventNotifier">Shift+a</div><div id="_Shift_b" class="eventNotifier">Shift+b</div><div
id="_Shift_c" class="eventNotifier">Shift+c</div><div id="_Shift_d" class="eventNotifier">Shift+d</div><div id="_Shift_e" class="eventNotifier">Shift+e</div><div id="_Shift_f" class="eventNotifier">Shift+f</div><div id=
"_Shift_g" class="eventNotifier">Shift+g</div><div id="_Shift_h" class="eventNotifier">Shift+h</div><div id="_Shift_i" class="eventNotifier">Shift+i</div><div id="_Shift_j" class="eventNotifier">Shift+j</div><div id="_Shift_k"
class="eventNotifier">Shift+k</div><div id="_Shift_l" class="eventNotifier">Shift+l</div><div id="_Shift_m" class="eventNotifier">Shift+m</div><div id="_Shift_n" class="eventNotifier">Shift+n</div><div id="_Shift_o" class=
"eventNotifier">Shift+o</div><div id="_Shift_p" class="eventNotifier">Shift+p</div><div id="_Shift_q" class="eventNotifier">Shift+q</div><div id="_Shift_r" class="eventNotifier">Shift+r</div><div id="_Shift_s" class=
"eventNotifier">Shift+s</div><div id="_Shift_t" class="eventNotifier">Shift+t</div><div id="_Shift_u" class="eventNotifier">Shift+u</div><div id="_Shift_v" class="eventNotifier">Shift+v</div><div id="_Shift_w" class=
"eventNotifier">Shift+w</div><div id="_Shift_x" class="eventNotifier">Shift+x</div><div id="_Shift_y" class="eventNotifier">Shift+y</div><div id="_Shift_z" class="eventNotifier">Shift+z</div><div style="clear: both;"/><strong>

Alt</strong><div id="_Alt_a" class="eventNotifier">Alt+a</div><div id="_Alt_b" class="eventNotifier">Alt+b</div><div id="_Alt_c" class="eventNotifier">Alt+c</div><div id="_Alt_d" class="eventNotifier">Alt+d</div><div id=
"_Alt_e" class="eventNotifier">Alt+e</div><div id="_Alt_f" class="eventNotifier">Alt+f</div><div id="_Alt_g" class="eventNotifier">Alt+g</div><div id="_Alt_h" class="eventNotifier">Alt+h</div><div id="_Alt_i" class=
"eventNotifier">Alt+i</div><div id="_Alt_j" class="eventNotifier">Alt+j</div><div id="_Alt_k" class="eventNotifier">Alt+k</div><div id="_Alt_l" class="eventNotifier">Alt+l</div><div id="_Alt_m" class="eventNotifier">Alt+m</div
><div id="_Alt_n" class="eventNotifier">Alt+n</div><div id="_Alt_o" class="eventNotifier">Alt+o</div><div id="_Alt_p" class="eventNotifier">Alt+p</div><div id="_Alt_q" class="eventNotifier">Alt+q</div><div id="_Alt_r" class=
"eventNotifier">Alt+r</div><div id="_Alt_s" class="eventNotifier">Alt+s</div><div id="_Alt_t" class="eventNotifier">Alt+t</div><div id="_Alt_u" class="eventNotifier">Alt+u</div><div id="_Alt_v" class="eventNotifier">Alt+v</div
><div id="_Alt_w" class="eventNotifier">Alt+w</div><div id="_Alt_x" class="eventNotifier">Alt+x</div><div id="_Alt_y" class="eventNotifier">Alt+y</div><div id="_Alt_z" class="eventNotifier">Alt+z</div><div style="clear: both;"
/><h2>Special Modifiers + Special Keys</h2><div style="clear: both;"/><strong>Ctrl</strong><div id="_Ctrl_esc" class="eventNotifier">Ctrl+esc</div><div id="_Ctrl_tab" class="eventNotifier">Ctrl+tab</div><div id="_Ctrl_space"
class="eventNotifier">Ctrl+space</div><div id="_Ctrl_return" class="eventNotifier">Ctrl+return</div><div id="_Ctrl_backspace" class="eventNotifier">Ctrl+backspace</div><div id="_Ctrl_scroll" class="eventNotifier">Ctrl+scroll

</div><div id="_Ctrl_capslock" class="eventNotifier">Ctrl+capslock</div><div id="_Ctrl_numlock" class="eventNotifier">Ctrl+numlock</div><div id="_Ctrl_pause" class="eventNotifier">Ctrl+pause</div><div id="_Ctrl_insert" class=
"eventNotifier">Ctrl+insert</div><div id="_Ctrl_home" class="eventNotifier">Ctrl+home</div><div id="_Ctrl_del" class="eventNotifier">Ctrl+del</div><div id="_Ctrl_end" class="eventNotifier">Ctrl+end</div><div id="_Ctrl_pageup"
class="eventNotifier">Ctrl+pageup</div><div id="_Ctrl_pagedown" class="eventNotifier">Ctrl+pagedown</div><div id="_Ctrl_left" class="eventNotifier">Ctrl+left</div><div id="_Ctrl_up" class="eventNotifier">Ctrl+up</div><div id=
"_Ctrl_right" class="eventNotifier">Ctrl+right</div><div id="_Ctrl_down" class="eventNotifier">Ctrl+down</div><div id="_Ctrl_f1" class="eventNotifier">Ctrl+f1</div><div id="_Ctrl_f2" class="eventNotifier">Ctrl+f2</div><div id=
"_Ctrl_f3" class="eventNotifier">Ctrl+f3</div><div id="_Ctrl_f4" class="eventNotifier">Ctrl+f4</div><div id="_Ctrl_f5" class="eventNotifier">Ctrl+f5</div><div id="_Ctrl_f6" class="eventNotifier">Ctrl+f6</div><div id="_Ctrl_f7"
class="eventNotifier">Ctrl+f7</div><div id="_Ctrl_f8" class="eventNotifier">Ctrl+f8</div><div id="_Ctrl_f9" class="eventNotifier">Ctrl+f9</div><div id="_Ctrl_f10" class="eventNotifier">Ctrl+f10</div><div id="_Ctrl_f11" class=
"eventNotifier">Ctrl+f11</div><div id="_Ctrl_f12" class="eventNotifier">Ctrl+f12</div><div style="clear: both;"/><strong>Shift</strong><div id="_Shift_esc" class="eventNotifier">Shift+esc</div><div id="_Shift_tab" class=
"eventNotifier">Shift+tab</div><div id="_Shift_space" class="eventNotifier">Shift+space</div><div id="_Shift_return" class="eventNotifier">Shift+return</div><div id="_Shift_backspace" class="eventNotifier">Shift+backspace</div
><div id="_Shift_scroll" class="eventNotifier">Shift+scroll</div><div id="_Shift_capslock" class="eventNotifier">Shift+capslock</div><div id="_Shift_numlock" class="eventNotifier">Shift+numlock</div><div id="_Shift_pause" class
="eventNotifier">Shift+pause</div><div id="_Shift_insert" class="eventNotifier">Shift+insert</div><div id="_Shift_home" class="eventNotifier">Shift+home</div><div id="_Shift_del" class="eventNotifier">Shift+del</div><div id=
"_Shift_end" class="eventNotifier">Shift+end</div><div id="_Shift_pageup" class="eventNotifier">Shift+pageup</div><div id="_Shift_pagedown" class="eventNotifier">Shift+pagedown</div><div id="_Shift_left" class="eventNotifier">

Shift+left</div><div id="_Shift_up" class="eventNotifier">Shift+up</div><div id="_Shift_right" class="eventNotifier">Shift+right</div><div id="_Shift_down" class="eventNotifier">Shift+down</div><div id="_Shift_f1" class=
"eventNotifier">Shift+f1</div><div id="_Shift_f2" class="eventNotifier">Shift+f2</div><div id="_Shift_f3" class="eventNotifier">Shift+f3</div><div id="_Shift_f4" class="eventNotifier">Shift+f4</div><div id="_Shift_f5" class=
"eventNotifier">Shift+f5</div><div id="_Shift_f6" class="eventNotifier">Shift+f6</div><div id="_Shift_f7" class="eventNotifier">Shift+f7</div><div id="_Shift_f8" class="eventNotifier">Shift+f8</div><div id="_Shift_f9" class=
"eventNotifier">Shift+f9</div><div id="_Shift_f10" class="eventNotifier">Shift+f10</div><div id="_Shift_f11" class="eventNotifier">Shift+f11</div><div id="_Shift_f12" class="eventNotifier">Shift+f12</div><div style="clear:
both;"/><strong>Alt</strong><div id="_Alt_esc" class="eventNotifier">Alt+esc</div><div id="_Alt_tab" class="eventNotifier">Alt+tab</div><div id="_Alt_space" class="eventNotifier">Alt+space</div><div id="_Alt_return" class=
"eventNotifier">Alt+return</div><div id="_Alt_backspace" class="eventNotifier">Alt+backspace</div><div id="_Alt_scroll" class="eventNotifier">Alt+scroll</div><div id="_Alt_capslock" class="eventNotifier">Alt+capslock</div><div
id="_Alt_numlock" class="eventNotifier">Alt+numlock</div><div id="_Alt_pause" class="eventNotifier">Alt+pause</div><div id="_Alt_insert" class="eventNotifier">Alt+insert</div><div id="_Alt_home" class="eventNotifier">Alt+home

</div><div id="_Alt_del" class="eventNotifier">Alt+del</div><div id="_Alt_end" class="eventNotifier">Alt+end</div><div id="_Alt_pageup" class="eventNotifier">Alt+pageup</div><div id="_Alt_pagedown" class="eventNotifier">Alt+
pagedown</div><div id="_Alt_left" class="eventNotifier">Alt+left</div><div id="_Alt_up" class="eventNotifier">Alt+up</div><div id="_Alt_right" class="eventNotifier">Alt+right</div><div id="_Alt_down" class="eventNotifier">Alt+
down</div><div id="_Alt_f1" class="eventNotifier">Alt+f1</div><div id="_Alt_f2" class="eventNotifier">Alt+f2</div><div id="_Alt_f3" class="eventNotifier">Alt+f3</div><div id="_Alt_f4" class="eventNotifier">Alt+f4</div><div id=
"_Alt_f5" class="eventNotifier">Alt+f5</div><div id="_Alt_f6" class="eventNotifier">Alt+f6</div><div id="_Alt_f7" class="eventNotifier">Alt+f7</div><div id="_Alt_f8" class="eventNotifier">Alt+f8</div><div id="_Alt_f9" class=
"eventNotifier">Alt+f9</div><div id="_Alt_f10" class="eventNotifier">Alt+f10</div><div id="_Alt_f11" class="eventNotifier">Alt+f11</div><div id="_Alt_f12" class="eventNotifier">Alt+f12</div></div>

````

````javascript
seajs.use('index',function(Keeyer){
    console.log(Keeyer);
                    Keeyer('#input').bind('keydown.ctrl_return',function(e){
                        alert('ctrl+enter');
                    });
                    Keeyer(document).bind('keydown.esc',function (evt){Keeyer('#_esc').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.tab',function (evt){Keeyer('#_tab').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.space',function (evt){Keeyer('#_space').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.return',function (evt){Keeyer('#_return').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.backspace',function (evt){Keeyer('#_backspace').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.scroll',function (evt){Keeyer('#_scroll').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.capslock',function (evt){Keeyer('#_capslock').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.numlock',function (evt){Keeyer('#_numlock').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.pause',function (evt){Keeyer('#_pause').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.insert',function (evt){Keeyer('#_insert').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.home',function (evt){Keeyer('#_home').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.del',function (evt){Keeyer('#_del').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.end',function (evt){Keeyer('#_end').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.pageup',function (evt){Keeyer('#_pageup').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.pagedown',function (evt){Keeyer('#_pagedown').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.left',function (evt){Keeyer('#_left').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.up',function (evt){Keeyer('#_up').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.right',function (evt){Keeyer('#_right').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.down',function (evt){Keeyer('#_down').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.f1',function (evt){Keeyer('#_f1').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.f2',function (evt){Keeyer('#_f2').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.f3',function (evt){Keeyer('#_f3').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.f4',function (evt){Keeyer('#_f4').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.f5',function (evt){Keeyer('#_f5').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.f6',function (evt){Keeyer('#_f6').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.f7',function (evt){Keeyer('#_f7').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.f8',function (evt){Keeyer('#_f8').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.f9',function (evt){Keeyer('#_f9').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.f10',function (evt){Keeyer('#_f10').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.f11',function (evt){Keeyer('#_f11').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.f12',function (evt){Keeyer('#_f12').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.1',function (evt){Keeyer('#_1').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.2',function (evt){Keeyer('#_2').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.3',function (evt){Keeyer('#_3').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.4',function (evt){Keeyer('#_4').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.5',function (evt){Keeyer('#_5').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.6',function (evt){Keeyer('#_6').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.7',function (evt){Keeyer('#_7').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.8',function (evt){Keeyer('#_8').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.9',function (evt){Keeyer('#_9').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.0',function (evt){Keeyer('#_0').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.a',function (evt){Keeyer('#_a').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.b',function (evt){Keeyer('#_b').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.c',function (evt){Keeyer('#_c').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.d',function (evt){Keeyer('#_d').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.e',function (evt){Keeyer('#_e').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.f',function (evt){Keeyer('#_f').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.g',function (evt){Keeyer('#_g').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.h',function (evt){Keeyer('#_h').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.i',function (evt){Keeyer('#_i').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.j',function (evt){Keeyer('#_j').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.k',function (evt){Keeyer('#_k').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.l',function (evt){Keeyer('#_l').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.m',function (evt){Keeyer('#_m').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.n',function (evt){Keeyer('#_n').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.o',function (evt){Keeyer('#_o').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.p',function (evt){Keeyer('#_p').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.q',function (evt){Keeyer('#_q').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.r',function (evt){Keeyer('#_r').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.s',function (evt){Keeyer('#_s').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.t',function (evt){Keeyer('#_t').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.u',function (evt){Keeyer('#_u').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.v',function (evt){Keeyer('#_v').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.w',function (evt){Keeyer('#_w').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.x',function (evt){Keeyer('#_x').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.y',function (evt){Keeyer('#_y').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.z',function (evt){Keeyer('#_z').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_a',function (evt){Keeyer('#_Ctrl_a').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_b',function (evt){Keeyer('#_Ctrl_b').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_c',function (evt){Keeyer('#_Ctrl_c').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_d',function (evt){Keeyer('#_Ctrl_d').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_e',function (evt){Keeyer('#_Ctrl_e').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_f',function (evt){Keeyer('#_Ctrl_f').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_g',function (evt){Keeyer('#_Ctrl_g').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_h',function (evt){Keeyer('#_Ctrl_h').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_i',function (evt){Keeyer('#_Ctrl_i').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_j',function (evt){Keeyer('#_Ctrl_j').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_k',function (evt){Keeyer('#_Ctrl_k').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_l',function (evt){Keeyer('#_Ctrl_l').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_m',function (evt){Keeyer('#_Ctrl_m').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_n',function (evt){Keeyer('#_Ctrl_n').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_o',function (evt){Keeyer('#_Ctrl_o').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_p',function (evt){Keeyer('#_Ctrl_p').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_q',function (evt){Keeyer('#_Ctrl_q').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_r',function (evt){Keeyer('#_Ctrl_r').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_s',function (evt){Keeyer('#_Ctrl_s').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_t',function (evt){Keeyer('#_Ctrl_t').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_u',function (evt){Keeyer('#_Ctrl_u').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_v',function (evt){Keeyer('#_Ctrl_v').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_w',function (evt){Keeyer('#_Ctrl_w').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_x',function (evt){Keeyer('#_Ctrl_x').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_y',function (evt){Keeyer('#_Ctrl_y').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_z',function (evt){Keeyer('#_Ctrl_z').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_a',function (evt){Keeyer('#_Shift_a').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_b',function (evt){Keeyer('#_Shift_b').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_c',function (evt){Keeyer('#_Shift_c').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_d',function (evt){Keeyer('#_Shift_d').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_e',function (evt){Keeyer('#_Shift_e').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_f',function (evt){Keeyer('#_Shift_f').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_g',function (evt){Keeyer('#_Shift_g').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_h',function (evt){Keeyer('#_Shift_h').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_i',function (evt){Keeyer('#_Shift_i').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_j',function (evt){Keeyer('#_Shift_j').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_k',function (evt){Keeyer('#_Shift_k').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_l',function (evt){Keeyer('#_Shift_l').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_m',function (evt){Keeyer('#_Shift_m').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_n',function (evt){Keeyer('#_Shift_n').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_o',function (evt){Keeyer('#_Shift_o').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_p',function (evt){Keeyer('#_Shift_p').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_q',function (evt){Keeyer('#_Shift_q').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_r',function (evt){Keeyer('#_Shift_r').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_s',function (evt){Keeyer('#_Shift_s').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_t',function (evt){Keeyer('#_Shift_t').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_u',function (evt){Keeyer('#_Shift_u').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_v',function (evt){Keeyer('#_Shift_v').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_w',function (evt){Keeyer('#_Shift_w').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_x',function (evt){Keeyer('#_Shift_x').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_y',function (evt){Keeyer('#_Shift_y').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_z',function (evt){Keeyer('#_Shift_z').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_a',function (evt){Keeyer('#_Alt_a').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_b',function (evt){Keeyer('#_Alt_b').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_c',function (evt){Keeyer('#_Alt_c').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_d',function (evt){Keeyer('#_Alt_d').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_e',function (evt){Keeyer('#_Alt_e').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_f',function (evt){Keeyer('#_Alt_f').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_g',function (evt){Keeyer('#_Alt_g').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_h',function (evt){Keeyer('#_Alt_h').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_i',function (evt){Keeyer('#_Alt_i').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_j',function (evt){Keeyer('#_Alt_j').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_k',function (evt){Keeyer('#_Alt_k').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_l',function (evt){Keeyer('#_Alt_l').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_m',function (evt){Keeyer('#_Alt_m').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_n',function (evt){Keeyer('#_Alt_n').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_o',function (evt){Keeyer('#_Alt_o').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_p',function (evt){Keeyer('#_Alt_p').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_q',function (evt){Keeyer('#_Alt_q').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_r',function (evt){Keeyer('#_Alt_r').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_s',function (evt){Keeyer('#_Alt_s').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_t',function (evt){Keeyer('#_Alt_t').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_u',function (evt){Keeyer('#_Alt_u').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_v',function (evt){Keeyer('#_Alt_v').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_w',function (evt){Keeyer('#_Alt_w').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_x',function (evt){Keeyer('#_Alt_x').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_y',function (evt){Keeyer('#_Alt_y').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_z',function (evt){Keeyer('#_Alt_z').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_esc', function (evt){Keeyer('#_Ctrl_esc').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_tab', function (evt){Keeyer('#_Ctrl_tab').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_space', function (evt){Keeyer('#_Ctrl_space').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_return', function (evt){Keeyer('#_Ctrl_return').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_backspace', function (evt){Keeyer('#_Ctrl_backspace').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_scroll', function (evt){Keeyer('#_Ctrl_scroll').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_capslock', function (evt){Keeyer('#_Ctrl_capslock').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_numlock', function (evt){Keeyer('#_Ctrl_numlock').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_pause', function (evt){Keeyer('#_Ctrl_pause').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_insert', function (evt){Keeyer('#_Ctrl_insert').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_home', function (evt){Keeyer('#_Ctrl_home').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_del', function (evt){Keeyer('#_Ctrl_del').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_end', function (evt){Keeyer('#_Ctrl_end').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_pageup', function (evt){Keeyer('#_Ctrl_pageup').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_pagedown', function (evt){Keeyer('#_Ctrl_pagedown').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_left', function (evt){Keeyer('#_Ctrl_left').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_up', function (evt){Keeyer('#_Ctrl_up').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_right', function (evt){Keeyer('#_Ctrl_right').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_down', function (evt){Keeyer('#_Ctrl_down').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_f1', function (evt){Keeyer('#_Ctrl_f1').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_f2', function (evt){Keeyer('#_Ctrl_f2').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_f3', function (evt){Keeyer('#_Ctrl_f3').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_f4', function (evt){Keeyer('#_Ctrl_f4').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_f5', function (evt){Keeyer('#_Ctrl_f5').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_f6', function (evt){Keeyer('#_Ctrl_f6').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_f7', function (evt){Keeyer('#_Ctrl_f7').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_f8', function (evt){Keeyer('#_Ctrl_f8').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_f9', function (evt){Keeyer('#_Ctrl_f9').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_f10', function (evt){Keeyer('#_Ctrl_f10').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_f11', function (evt){Keeyer('#_Ctrl_f11').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Ctrl_f12', function (evt){Keeyer('#_Ctrl_f12').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_esc', function (evt){Keeyer('#_Shift_esc').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_tab', function (evt){Keeyer('#_Shift_tab').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_space', function (evt){Keeyer('#_Shift_space').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_return', function (evt){Keeyer('#_Shift_return').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_backspace', function (evt){Keeyer('#_Shift_backspace').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_scroll', function (evt){Keeyer('#_Shift_scroll').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_capslock', function (evt){Keeyer('#_Shift_capslock').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_numlock', function (evt){Keeyer('#_Shift_numlock').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_pause', function (evt){Keeyer('#_Shift_pause').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_insert', function (evt){Keeyer('#_Shift_insert').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_home', function (evt){Keeyer('#_Shift_home').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_del', function (evt){Keeyer('#_Shift_del').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_end', function (evt){Keeyer('#_Shift_end').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_pageup', function (evt){Keeyer('#_Shift_pageup').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_pagedown', function (evt){Keeyer('#_Shift_pagedown').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_left', function (evt){Keeyer('#_Shift_left').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_up', function (evt){Keeyer('#_Shift_up').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_right', function (evt){Keeyer('#_Shift_right').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_down', function (evt){Keeyer('#_Shift_down').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_f1', function (evt){Keeyer('#_Shift_f1').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_f2', function (evt){Keeyer('#_Shift_f2').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_f3', function (evt){Keeyer('#_Shift_f3').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_f4', function (evt){Keeyer('#_Shift_f4').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_f5', function (evt){Keeyer('#_Shift_f5').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_f6', function (evt){Keeyer('#_Shift_f6').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_f7', function (evt){Keeyer('#_Shift_f7').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_f8', function (evt){Keeyer('#_Shift_f8').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_f9', function (evt){Keeyer('#_Shift_f9').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_f10', function (evt){Keeyer('#_Shift_f10').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_f11', function (evt){Keeyer('#_Shift_f11').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Shift_f12', function (evt){Keeyer('#_Shift_f12').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_esc', function (evt){Keeyer('#_Alt_esc').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_tab', function (evt){Keeyer('#_Alt_tab').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_space', function (evt){Keeyer('#_Alt_space').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_return', function (evt){Keeyer('#_Alt_return').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_backspace', function (evt){Keeyer('#_Alt_backspace').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_scroll', function (evt){Keeyer('#_Alt_scroll').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_capslock', function (evt){Keeyer('#_Alt_capslock').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_numlock', function (evt){Keeyer('#_Alt_numlock').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_pause', function (evt){Keeyer('#_Alt_pause').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_insert', function (evt){Keeyer('#_Alt_insert').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_home', function (evt){Keeyer('#_Alt_home').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_del', function (evt){Keeyer('#_Alt_del').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_end', function (evt){Keeyer('#_Alt_end').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_pageup', function (evt){Keeyer('#_Alt_pageup').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_pagedown', function (evt){Keeyer('#_Alt_pagedown').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_left', function (evt){Keeyer('#_Alt_left').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_up', function (evt){Keeyer('#_Alt_up').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_right', function (evt){Keeyer('#_Alt_right').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_down', function (evt){Keeyer('#_Alt_down').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_f1', function (evt){Keeyer('#_Alt_f1').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_f2', function (evt){Keeyer('#_Alt_f2').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_f3', function (evt){Keeyer('#_Alt_f3').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_f4', function (evt){Keeyer('#_Alt_f4').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_f5', function (evt){Keeyer('#_Alt_f5').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_f6', function (evt){Keeyer('#_Alt_f6').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_f7', function (evt){Keeyer('#_Alt_f7').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_f8', function (evt){Keeyer('#_Alt_f8').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_f9', function (evt){Keeyer('#_Alt_f9').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_f10', function (evt){Keeyer('#_Alt_f10').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_f11', function (evt){Keeyer('#_Alt_f11').addClass('dirty'); return false; });
                    Keeyer(document).bind('keydown.Alt_f12', function (evt){Keeyer('#_Alt_f12').addClass('dirty'); return false; });
             
             
             
});
````