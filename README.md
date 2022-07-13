<!-- Left Menu -->
<div id="leftmenu">
  
  <div id="date_time">
    <div id="date" class="semi_arc e4">
      <div class="semi_arc_2 e4_1">
        <div class="counterspin4"></div>
      </div>
        <div style="font-size: 40px; margin-top: 25px;">04</div>
        <div style="font-size: 25px;">January</div>
    </div>
    
    <div id="time" class="arc e1">
        <div style="font-size: 23px; margin-left: -10px; margin-top: 23px;">23:41</div>
        <div style="font-size: 15px; margin-left: 40px; margin-top: -30px; display; inline;">31</div>
        <div style="font-size: 17px; margin-top: 10px;">Tuesday</div>
    </div>
  </div>
  
  <p class="title">Performance</p>
  <div class="hline title_underline"></div>
  
  <span class="menuitem entypo-gauge" style="font-size: 30px; margin-left: 10px;">
    <p id="cpu" class="caption" style="font-size: 20px;">CPU Usage: 19%</p>
  </span> <br/>
  
  <span class="menuitem entypo-chart-area" style="font-size: 30px; margin-left: 10px;">
    <p id="ram" class="caption" style="font-size: 20px;">Physical Memory: 28%</p>
  </span> <br/>
  
  <span class="menuitem entypo-chart-pie" style="font-size: 30px; margin-left: 10px;">
    <p id="proc" class="caption" style="font-size: 20px;">Processes: 73</p>
  </span>
  
  <p class="title">Shortcuts</p>
  <div class="hline title_underline"></div> 
  
  <div class="menu">
    <button class="menuitem"> <span class="entypo-right-open"/> <p class="caption">User</p> </button>
    <button class="menuitem"> <span class="entypo-right-open"/> <p class="caption">Documents</p> </button>
    <button class="menuitem"> <span class="entypo-right-open"/> <p class="caption">Computer</p> </button>
    <button class="menuitem"> <span class="entypo-right-open"/> <p class="caption">Control Panel</p> </button>
    
    <hr style="border-color: transparent; margin: 0;"/>
    <div class="hline" style="margin-top: 5px; margin-bottom: 5px;"></div>
    
    <button class="menuitem"> <span class="entypo-right-open"/> <p class="caption">Custom Path 1</p> </button>
    <button class="menuitem"> <span class="entypo-right-open"/> <p class="caption">Custom Path 2</p> </button>
    <button class="menuitem"> <span class="entypo-right-open"/> <p class="caption">Custom Path 3</p> </button>
  </div>
  
  <p class="title">Social</p>
  <div class="hline title_underline"></div>
  
  <div class="app_icon entypo-facebook-squared"></div>
  <div class="app_icon entypo-twitter"></div>
  <div class="app_icon entypo-gplus"></div>
  <div class="app_icon entypo-skype"></div>
  
  <div class="app_icon entypo-tumblr"></div>
  <div class="app_icon entypo-pinterest"></div>
  <div class="app_icon entypo-soundcloud"></div>
  <div class="app_icon entypo-stumbleupon"></div>
  
</div>


<!-- Right Menu -->
<div id="rightmenu">
  <p class="title" style="text-align: left; margin-left: 10px;">Notes</p>
  <div id="particle10" class="hline"></div>
  <div id="particle11" class="hline"></div>
  <div id="particle12" class="vline"></div>
  <textarea id="note_input" rows="12" cols="44">For the maximum viewing experience, please view this pen in full screen where the code is displayed to the side of the display.
    
    To Complete:
    - Right Menu (this side of the screen)
      - Make this note restricted to 11 rows
      - Fill in empty space below
    - Weather widget next to date/time
    - Place quick access taskbar down bottom
    - Fill in space at the top</textarea>
</div>



<!-- Arc Reactor -->
<div id="arc_container">
  <div class="arc_reactor">
    <div class="case_container">
      <div class="e7">
        <div class="semi_arc_3 e5_1">
          <div class="semi_arc_3 e5_2">
            <div class="semi_arc_3 e5_3">
              <div class="semi_arc_3 e5_4"></div>
            </div>
          </div>
        </div>
        <div class="core2"></div>
      </div>
      <ul class="marks">
        <li></li><li></li><li></li><li></li><li></li><li></li>
        <li></li><li></li><li></li><li></li><li></li><li></li>
        <li></li><li></li><li></li><li></li><li></li><li></li>
        <li></li><li></li><li></li><li></li><li></li><li></li>
        <li></li><li></li><li></li><li></li><li></li><li></li>
        <li></li><li></li><li></li><li></li><li></li><li></li>
        <li></li><li></li><li></li><li></li><li></li><li></li>
        <li></li><li></li><li></li><li></li><li></li><li></li>
        <li></li><li></li><li></li><li></li><li></li><li></li>
        <li></li><li></li><li></li><li></li><li></li><li></li>
      </ul>
    </div>
  </div>
</div>



<!-- Particles -->
<!-- Left Menu Particles -->
<canvas id="particle1" width="20" height="500"></canvas> <script>
var canvas = document.getElementById('particle1');
var context = canvas.getContext('2d');

context.beginPath();
context.moveTo(0, 0);
context.lineTo(0, 70);
context.lineTo(10, 85);
context.lineTo(10, 135);
context.lineTo(0, 150);
context.lineTo(0, 480);
context.lineTo(5, 490);
context.lineTo(10, 490);
context.lineTo(20, 490);
context.lineTo(20, 250);
context.lineTo(10, 235);
context.lineTo(10, 185);
context.lineTo(20, 170);
context.lineTo(20, 40);
context.lineTo(10, 30);
context.lineTo(10, 20);

context.closePath();
context.lineWidth = 1;
context.fillStyle = 'rgba(2,254,255,0.3)';
context.fill();
context.strokeStyle = 'transparent';
context.stroke();
</script>

<canvas id="particle1_1" width="40" height="510"></canvas> <script>
var canvas = document.getElementById('particle1_1');
var context = canvas.getContext('2d');

context.beginPath();
context.lineTo(0, 0);
context.lineTo(10, 15);
context.lineTo(10, 65);
context.lineTo(0, 80);
context.lineTo(0, 0);

context.closePath();
context.lineWidth = 1;
context.fillStyle = 'rgba(2,254,255,0.3)';
context.fill();
context.strokeStyle = 'transparent';
context.stroke();
</script>

<canvas id="particle1_2" width="40" height="510"></canvas> <script>
var canvas = document.getElementById('particle1_2');
var context = canvas.getContext('2d');

context.beginPath();
context.lineTo(10, 80);
context.lineTo(0, 65);
context.lineTo(0, 15);
context.lineTo(10, 0);
context.lineTo(10, 80);

context.closePath();
context.lineWidth = 1;
context.fillStyle = 'rgba(2,254,255,0.3)';
context.fill();
context.strokeStyle = 'transparent';
context.stroke();
</script>

<div id="particle1_3">
  > > > >
</div>

<div id="particle2">▶<br/>▶<br/>▶</div>
<div id="particle3" class="vline"/>
<div id="particle4" class="vline"/>
<div id="particle5" class="vline"/>
<div id="particle6" class="vline"/>
<div id="particle7" class="vline"/>
<div id="particle8" class="vline"/>
<div id="particle9" class="vline"/>

# JS-Jarvis-test
Idea By Prajwal
