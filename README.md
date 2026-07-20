<?xml version='1.0' encoding='UTF-8'?>
<svg xmlns="http://www.w3.org/2000/svg" font-family="ConsolasFallback,Consolas,monospace" width="1180" height="530" viewBox="0 0 1180 530" fontsize="15px">
<style>
@font-face {
  src: local('Consolas'), local('Consolas Bold');
  font-family: 'ConsolasFallback';
  font-display: swap;
  -webkit-size-adjust: 109%;
  size-adjust: 109%;
}
.key      { fill: #5EEAD4; }
.value    { fill: #E5E7EB; }
.cc       { fill: #5f6b7a; }
.addColor { fill: #39ff14; }
.delColor { fill: #ef4444; }
text, tspan { white-space: pre; }
</style>

<defs>
  <clipPath id="asciiReveal">
    <rect x="0" y="-40" width="1180" height="0">
      <animate attributeName="height" from="0" to="560" dur="2.2s" begin="0.15s" fill="freeze" calcMode="spline" keySplines="0.25 0.1 0.25 1"/>
    </rect>
  </clipPath>

  <linearGradient id="scanGlow" x1="0" y1="0" x2="0" y2="1">
    <stop offset="0%" stop-color="#00f0ff" stop-opacity="0"/>
    <stop offset="85%" stop-color="#00f0ff" stop-opacity="0.55"/>
    <stop offset="100%" stop-color="#aef9ff" stop-opacity="0.95"/>
  </linearGradient>

  <filter id="glowBlur" x="-50%" y="-200%" width="200%" height="500%">
    <feGaussianBlur stdDeviation="3" result="blur"/>
    <feMerge>
      <feMergeNode in="blur"/>
      <feMergeNode in="SourceGraphic"/>
    </feMerge>
  </filter>
</defs>

<rect width="1180px" height="530px" fill="#0a0b10" rx="15" stroke="rgba(0, 240, 255, 0.15)" stroke-width="2"/>

<g transform="translate(22,20) scale(0.42,0.88)" clip-path="url(#asciiReveal)">
<text x="0" y="0" fill="#00f0ff" class="ascii" opacity="0.85">
<tspan x="-10" y="-30">**#*##------.. ..:  .     *#*###----=-......      . ##*#*#=-=-=-...:..   .    *#***#---=--......  .     #**###==--=-......  </tspan>
<tspan x="-10" y="-21">****------ .. ..   .    **#**#-----=.... .     .  ##*#**---==-:::...        *#####-=-==-.:.       .   **####-==---.... .    </tspan>
<tspan x="-10" y="-12">##------ . ...        ######---=--.:..:. .      *###*#=-==-=..:. .        **##*#==---=. ....        *###*#-=---=. ..        </tspan>
<tspan x="-10" y="-3">------.. .:        .*####*---=-- .....     .. *#***#------ .  ..        #*##*#=-==--......        #####*==--=-.. ..  .      </tspan>
<tspan x="-10" y="6">----...  .        #*##*#==---= . .:         *##***-=-==-.......       *#**#*-===-=:.. ..        *##*#*-----=...:.         ##</tspan>
<tspan x="-10" y="15">--.. .:         ###**#=----=..:.    .     *#*##*---=--.....   .     ##**##--==--... ..  .     *##**#==---=   ... ..  .  ###*</tspan>
<tspan x="-10" y="24">  ..: .       ##*##*-==---.......       ###**#==----. ....        ***#*#==----......        #****#---=--..: ..      . ####*#</tspan>
<tspan x="-10" y="33">: ..        **#***=-----.  ... .     .#*#**#-=-=-- ... .        ##**##--=-=-. ....        ##*##*=-----......        #**#*#--</tspan>
<tspan x="-10" y="42">.       . ####*#-==-== .. ..        ***###-=----.... :    .   #*#*#*-=-=--  ....        *##*##-=----.... .    .   *##**#--=-</tspan>
<tspan x="-10" y="51">        *###*#=-=---. ....        #*#***===-=-.....:        *#*#**-=----.... .       .****##-=----. .. .    .   *###*#--=-=-</tspan>
<tspan x="-10" y="60">   .  ##*#*#-=--=- . ...        **####---===.. ...        **##**------:. : ..       #*####-----=......        *#*###------.:</tspan>
<tspan x="-10" y="69">    ##*#*#=----=.....:     .  *#*###---==-...  .     .  ###*#*=-=---.  ...      . *###*#---==-  ...         ##*###-=----. . </tspan>
<tspan x="-10" y="78">  ##*###==--=-.. ..: .      *#####----=-.....:        *###**--=-==......        ######------.: .         .###*#*---=-= .  ..</tspan>
<tspan x="-10" y="87">#**###=--=-=.:.  .        ####*#-=---=:... :    .   ######=-----.. ...        ##*##*-=---=.. ...        *#####--=---. ...  .</tspan>
<tspan x="-10" y="96">###*=-====.        .    *#*###=---==. ....     .  ###*##------. . .    .    *####*=-----.. ...        *#*##*-----=:. ..   . </tspan>
<tspan x="-10" y="105">#*--=---...  .        ####**=-=-=-... ..        *###*#==-=-= .:...  .     **#**#--=-==  ...         ######-==---.:....  ..  </tspan>
<tspan x="-10" y="114">------  :.:.        ###*##=--=--:....         ####*#------.... .     .  **##*#-=--== .....        #*#*##-=--==......        </tspan>
<tspan x="-10" y="123">----. .....       ######=----=.. ...  .   . ##**##--====.. ...     .  ##*#**=-=---...:..        ##**#*=----=.... . .    . *#</tspan>
<tspan x="-10" y="132">=-.:.:..        #*#*#*-----=.. ..         ###**#-=-=--. ....        *####*---=-= ....         ##***#=--==-...  .        **#*</tspan>
<tspan x="-10" y="141">......        ***#*#=-=-==. :.:.        #*#*##--=--- .. .       . *#*#*#-=-=--.. ..         #***##-==---. . .. .      #**###</tspan>
<tspan x="-10" y="150"> ...        **####==----. . .:        ##*###--===-....    .  .. #*##*#=-=--=  .. .        ##*#**------ .. .       . *##*##=-</tspan>
<tspan x="-10" y="159">.         ######-=-=== ..:.         *###**-=---=. .....       *####*=-=---...  .        ##**#*-----=: ....      . *####*----</tspan>
<tspan x="-10" y="168"> .      *####*----=-:...   .      #*****=----=. .:.         #**###=-----.....   .     **#*##---=--...... .   .  #####*=-----</tspan>
<tspan x="-10" y="177">  .   ##**#*=---=-.. . .      . ***#**=--=-- .....        ##*###=-==-- : . .        #**##*-----=.. . .        #**###------..</tspan>
<tspan x="-10" y="186">    ######---=--. : ..        #*#*##-=-==-.:....        *#*###----=-.... .        #*****=----=.....         *#**#*--=--= ...</tspan>
<tspan x="-10" y="195">  ###*##=---=-:....         ######---===. ....        *###*#--===-.. :..        ###***------. .. .        ######----=-. ....</tspan>
<tspan x="-10" y="204">##**#*=---==.....         #*#*#*==----.. ...     .. **###*-=----.....  . .    *#*#**---=-- . . .     .  ##**#*------.. .    </tspan>
<tspan x="-10" y="213">##*#-=-=-= . ...        *##*##=-=-=-:.. ..       .######=---== .. :.   .    #####*=-=-==... ..        ###*##--==--  ....    </tspan>
<tspan x="-10" y="222">#*--=-== . . ..       ###*#*---=-=.. ... .     .######=--=-=......    .   #*###*=---==...:..        #*#***--==--: .. .  .   </tspan>
<tspan x="-10" y="231">-=-=--......        ##*#**--==-= ..:..  .     *#####-----=......        ####*#=----=. . .:        ***###-=----.... .        </tspan>
<tspan x="-10" y="240">-=--....:.. .     ##**#*-=---= ...:..       ##***#=----=..   . .      ##***#===-=-..   .        **####--=---  ....        *#</tspan>
<tspan x="-10" y="249">=- .. .:        ##***#-==-=-  . :.        *#####-=----. . ..      . **###*--=--=.   ..        ###*##-=-=-=.... .. .  .  *#**</tspan>
<tspan x="-10" y="258">......        #*####-===--.. ..:        *#**##-=-=--  .  ..       ###*#*=-=-==..  .       . ##***#-=-=-=... ..        ###*##</tspan>
<tspan x="-10" y="267">. .         **####--=-==. :..         #**##*=---=- .....    .   #**##*-----=.:.. :   . .  #*##*#---=-- . ...     .  ###***--</tspan>
<tspan x="-10" y="276">..  . .   ****##--===- ......       *###*#--==--... :.  .  .  ####**------ .:...       .######-=--=-...  .        *##**#=---</tspan>
<tspan x="-10" y="285">        ##*##*--=---......        ##**#*-----= .....        #####*-=----. :..         *##*#*--==--.:. ..  .     *###*#-=--=-</tspan>
<tspan x="-10" y="294">      *##***=--===.:....   .    *##*#*-=---=.. ....       #**###==-===......        #*####-=---=.. ..         ####*#=-==-=. </tspan>
<tspan x="-10" y="303">    ###*##==-=--... ..       .####**-=---= ::..         ######---=--.....         ##*###==-==-:.  ..   .    *##***------.:.:</tspan>
<tspan x="-10" y="312">  #***##----=- .. ..        ##*###-=-=--  .. .      . #*###*---=--.. .          ####*#--==--...:          ######--===-  .. .</tspan>
<tspan x="-10" y="321">#*####=---==..  ..        ######----==..:...        ##*###--=-=-. ....        ######==-=-=. . . .       *#*##*--==-=  .  .  </tspan>
<tspan x="-10" y="330">###*=-=-==.... .      . *###**-----=. ..::  .     **####-=--==...:.:        #####*--=---....     .    ###*##-=---=:::..     </tspan>
<tspan x="-10" y="339">**---=--....          #*#*##--=--- . ... .      #***##------... ..        ##**#*-=----:. ..     .   #*####-==---...... .    </tspan>
<tspan x="-10" y="348">=--==-..  ...     . ##*##*------... ..        *#####-----=. ....      . ###***==----...... .      ###*##-=---- .. ..        </tspan>
<tspan x="-10" y="357">-==-... ..        *#*#*#--==-=.: ...        ##*#**------..: ..        **##*#---=--:.. ..        **####---==-. . ..        ##</tspan>
<tspan x="-10" y="366">--.......     ..#*#*##-=-==-. .. .        #####*===--=... ..   .    ##**##---===. ....        *#**##-----=.....         #**#</tspan>
<tspan x="-10" y="375">. ...         *#**##--=-=-.... .        ****#*---==-. . ...    .  *#####=---=-......    .   ##**##--==--... ..       .*##*##</tspan>
<tspan x="-10" y="384">. ...   .   ##***#=--=--..:...        #**#*#------  . ..      . ##**##=-----.... .        #*####-=--==.. . .        ##**##--</tspan>
<tspan x="-10" y="393">..     .. ###*##===-=-......        *#*#**-----=. :..       . ##*#*#==-=--.. ...        **####==--=- .....    ..  #*#**#---=</tspan>
<tspan x="-10" y="402">        ##*##*-----=.:...         *###*#===-==......        ###*##==----.: ..         ##*###=----= ..: . .      ****##-=--==</tspan>
<tspan x="-10" y="411"> .    #*####=-==-=......        #***##=---=- . . .        ####*#--=---.....:        *#####=---==......    .   ###*##-=-=-- .</tspan>
<tspan x="-10" y="420">  . ######------:... :       .#****#=-=---  ....        *##*#*--=-=-..... .       *####*-=-=-=..:.:         ###*#*---==-... </tspan>
<tspan x="-10" y="429">  #*****=--=-=  .....     ..****##-=--=-  .  .        ###**#--==-=......   .    **#*#*-=--=-:..:.:   .    #*#*##-=-=-=......</tspan>
<tspan x="-10" y="438">*#*###===-==. ....      . **###*-=---= :.. .        **####--=---. . ..        ##**##=---==......        ######=--=--... .:  </tspan>
<tspan x="-10" y="447">**##--==--.... ..       #####*---==-......   ..   ###***----=-.... .        ######-=-=-=.. ...        ##***#------.....     </tspan>
<tspan x="-10" y="456">##--==--:.. ..     .  ***#*#---=--... .         *#***#=--==-... ..        #**###=-=--- ....         #**###---==-......      </tspan>
</text>
</g>

<g transform="translate(22,20)">
  <rect x="0" y="0" width="500" height="26" fill="url(#scanGlow)" filter="url(#glowBlur)">
    <animate attributeName="y" from="-30" to="500" dur="2.2s" begin="0.15s" fill="freeze" calcMode="spline" keySplines="0.25 0.1 0.25 1"/>
    <animate attributeName="opacity" values="1;1;0" keyTimes="0;0.9;1" dur="2.2s" begin="0.15s" fill="freeze"/>
  </rect>
  <rect x="0" y="0" width="500" height="1.5" fill="#aef9ff">
    <animate attributeName="y" from="-30" to="500" dur="2.2s" begin="0.15s" fill="freeze" calcMode="spline" keySplines="0.25 0.1 0.25 1"/>
    <animate attributeName="opacity" values="1;1;0" keyTimes="0;0.9;1" dur="2.2s" begin="0.15s" fill="freeze"/>
  </rect>
</g>

<g opacity="0">
  <animate attributeName="opacity" from="0" to="1" dur="0.4s" begin="2.3000000000000003s" fill="freeze"/>
  <text x="520" y="30" fill="#00f0ff" fontsize="17px">YOUR_USERNAME@Neural-grid</text>
  <text x="720" y="30" fill="#E5E7EB">-———————————————————————————————————————————-—-</text>
</g>

<g opacity="0" transform="translate(0,6)">
  <animate attributeName="opacity" from="0" to="1" dur="0.45s" begin="2.45s" fill="freeze"/>
  <animateTransform attributeName="transform" type="translate" from="0,6" to="0,0" dur="0.45s" begin="2.45s" fill="freeze"/>
  <text x="520" y="50"><tspan class="cc">. </tspan><tspan class="key">Subject</tspan><tspan class="cc"> ............................ </tspan><tspan class="value">[Your Name]</tspan></text>
</g>
<g opacity="0" transform="translate(0,6)">
  <animate attributeName="opacity" from="0" to="1" dur="0.45s" begin="2.56s" fill="freeze"/>
  <animateTransform attributeName="transform" type="translate" from="0,6" to="0,0" dur="0.45s" begin="2.56s" fill="freeze"/>
  <text x="520" y="70"><tspan class="cc">. </tspan><tspan class="key">Role</tspan><tspan class="cc"> .......... </tspan><tspan class="value">[Your Role / Title]</tspan></text>
</g>
<g opacity="0" transform="translate(0,6)">
  <animate attributeName="opacity" from="0" to="1" dur="0.45s" begin="2.67s" fill="freeze"/>
  <animateTransform attributeName="transform" type="translate" from="0,6" to="0,0" dur="0.45s" begin="2.67s" fill="freeze"/>
  <text x="520" y="90"><tspan class="cc">. </tspan><tspan class="key">Status</tspan><tspan class="cc"> ........... </tspan><tspan class="value">[Your one-line status]</tspan></text>
</g>
<g opacity="0" transform="translate(0,6)">
  <animate attributeName="opacity" from="0" to="1" dur="0.45s" begin="2.78s" fill="freeze"/>
  <animateTransform attributeName="transform" type="translate" from="0,6" to="0,0" dur="0.45s" begin="2.78s" fill="freeze"/>
  <text x="520" y="110"><tspan class="cc">. </tspan><tspan class="key">ToolChain</tspan><tspan class="cc"> ............. </tspan><tspan class="value">[Your tools, e.g. VS Code, Git]</tspan></text>
</g>
<g opacity="0" transform="translate(0,6)">
  <animate attributeName="opacity" from="0" to="1" dur="0.45s" begin="2.89s" fill="freeze"/>
  <animateTransform attributeName="transform" type="translate" from="0,6" to="0,0" dur="0.45s" begin="2.89s" fill="freeze"/>
  <text x="520" y="150"><tspan class="cc">. </tspan><tspan class="key">Neural</tspan>.<tspan class="key">Core</tspan>:<tspan class="cc"> ... </tspan><tspan class="value">[Core languages]</tspan></text>
</g>
<g opacity="0" transform="translate(0,6)">
  <animate attributeName="opacity" from="0" to="1" dur="0.45s" begin="3.00s" fill="freeze"/>
  <animateTransform attributeName="transform" type="translate" from="0,6" to="0,0" dur="0.45s" begin="3.00s" fill="freeze"/>
  <text x="520" y="170"><tspan class="cc">. </tspan><tspan class="key">Neural</tspan>.<tspan class="key">Frontend</tspan>:<tspan class="cc"> ........ </tspan><tspan class="value">[Frontend stack]</tspan></text>
</g>
<g opacity="0" transform="translate(0,6)">
  <animate attributeName="opacity" from="0" to="1" dur="0.45s" begin="3.11s" fill="freeze"/>
  <animateTransform attributeName="transform" type="translate" from="0,6" to="0,0" dur="0.45s" begin="3.11s" fill="freeze"/>
  <text x="520" y="190"><tspan class="cc">. </tspan><tspan class="key">Neural</tspan>.<tspan class="key">Backend</tspan>:<tspan class="cc"> .. </tspan><tspan class="value">[Backend stack]</tspan></text>
</g>
<g opacity="0" transform="translate(0,6)">
  <animate attributeName="opacity" from="0" to="1" dur="0.45s" begin="3.22s" fill="freeze"/>
  <animateTransform attributeName="transform" type="translate" from="0,6" to="0,0" dur="0.45s" begin="3.22s" fill="freeze"/>
  <text x="520" y="210"><tspan class="cc">. </tspan><tspan class="key">Neural</tspan>.<tspan class="key">Stack</tspan>:<tspan class="cc"> ............. </tspan><tspan class="value">[Other stack / domain]</tspan></text>
</g>
<g opacity="0" transform="translate(0,6)">
  <animate attributeName="opacity" from="0" to="1" dur="0.45s" begin="3.33s" fill="freeze"/>
  <animateTransform attributeName="transform" type="translate" from="0,6" to="0,0" dur="0.45s" begin="3.33s" fill="freeze"/>
  <text x="520" y="250"><tspan fill="#ff007f">- Contact</tspan> -————————————————————————————————________________—————-—-</text>
</g>
<g opacity="0" transform="translate(0,6)">
  <animate attributeName="opacity" from="0" to="1" dur="0.45s" begin="3.44s" fill="freeze"/>
  <animateTransform attributeName="transform" type="translate" from="0,6" to="0,0" dur="0.45s" begin="3.44s" fill="freeze"/>
  <text x="520" y="270"><tspan class="cc">. </tspan><tspan class="key">Grid</tspan>.<tspan class="key">Mail</tspan>:<tspan class="cc"> ...................... </tspan><tspan class="value">[you@email.com]</tspan></text>
</g>
<g opacity="0" transform="translate(0,6)">
  <animate attributeName="opacity" from="0" to="1" dur="0.45s" begin="3.55s" fill="freeze"/>
  <animateTransform attributeName="transform" type="translate" from="0,6" to="0,0" dur="0.45s" begin="3.55s" fill="freeze"/>
  <text x="520" y="290"><tspan class="cc">. </tspan><tspan class="key">Grid</tspan>.<tspan class="key">Portfolio</tspan>:<tspan class="cc"> .......................... </tspan><tspan class="value">[yourportfolio.com]</tspan></text>
</g>
<g opacity="0" transform="translate(0,6)">
  <animate attributeName="opacity" from="0" to="1" dur="0.45s" begin="3.66s" fill="freeze"/>
  <animateTransform attributeName="transform" type="translate" from="0,6" to="0,0" dur="0.45s" begin="3.66s" fill="freeze"/>
  <text x="520" y="310"><tspan class="cc">. </tspan><tspan class="key">Grid</tspan>.<tspan class="key">LinkedIn</tspan>:<tspan class="cc"> ............................ </tspan><tspan class="value">[your-linkedin]</tspan></text>
</g>
<g opacity="0" transform="translate(0,6)">
  <animate attributeName="opacity" from="0" to="1" dur="0.45s" begin="3.77s" fill="freeze"/>
  <animateTransform attributeName="transform" type="translate" from="0,6" to="0,0" dur="0.45s" begin="3.77s" fill="freeze"/>
  <text x="520" y="330"><tspan class="cc">. </tspan><tspan class="key">Grid</tspan>.<tspan class="key">Github</tspan>:<tspan class="cc"> ..................... </tspan><tspan class="value">[YOUR_GITHUB]</tspan></text>
</g>
<g opacity="0" transform="translate(0,6)">
  <animate attributeName="opacity" from="0" to="1" dur="0.45s" begin="3.88s" fill="freeze"/>
  <animateTransform attributeName="transform" type="translate" from="0,6" to="0,0" dur="0.45s" begin="3.88s" fill="freeze"/>
  <text x="520" y="370"><tspan fill="#ff007f">- GitHub Stats</tspan> -————————————————————————————————________________-—-</text>
</g>
<g opacity="0" transform="translate(0,6)">
  <animate attributeName="opacity" from="0" to="1" dur="0.45s" begin="3.99s" fill="freeze"/>
  <animateTransform attributeName="transform" type="translate" from="0,6" to="0,0" dur="0.45s" begin="3.99s" fill="freeze"/>
  <text x="520" y="390"><tspan class="cc">. </tspan><tspan class="key">Repos</tspan>:<tspan class="cc"> .. </tspan><tspan class="value">[00]</tspan> {<tspan class="key">Contributed</tspan>: <tspan class="value">[00]</tspan>   }  | <tspan class="key">Stars</tspan>:<tspan class="cc"> .......... </tspan><tspan class="value">[00]</tspan></text>
</g>
<g opacity="0" transform="translate(0,6)">
  <animate attributeName="opacity" from="0" to="1" dur="0.45s" begin="4.10s" fill="freeze"/>
  <animateTransform attributeName="transform" type="translate" from="0,6" to="0,0" dur="0.45s" begin="4.10s" fill="freeze"/>
  <text x="520" y="410"><tspan class="cc">. </tspan><tspan class="key">Commits</tspan>:<tspan class="cc"> .................. </tspan><tspan class="value">[00]</tspan>       | <tspan class="key">Followers</tspan>:<tspan class="cc"> ...... </tspan><tspan class="value">[00]</tspan></text>
</g>
<g opacity="0" transform="translate(0,6)">
  <animate attributeName="opacity" from="0" to="1" dur="0.45s" begin="4.21s" fill="freeze"/>
  <animateTransform attributeName="transform" type="translate" from="0,6" to="0,0" dur="0.45s" begin="4.21s" fill="freeze"/>
  <text x="520" y="430"><tspan class="cc">. </tspan><tspan class="key">Lines of Code</tspan>:<tspan class="cc">. </tspan><tspan class="value">[000,000]</tspan> ( <tspan class="addColor">[000]</tspan><tspan class="addColor">++</tspan>, <tspan class="delColor">[000]</tspan><tspan class="delColor">--</tspan> )</text>
</g>
</svg>

<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&duration=3000&pause=1000&color=00D9FF&center=true&vCenter=true&width=600&lines=Hi+there!+I'm+a+Full+Stack+Developer+%F0%9F%91%8B;.NET+%7C+Angular+%7C+React+Specialist;Building+Scalable+Web+Applications;Always+Learning+New+Technologies+%F0%9F%9A%80" alt="Typing SVG" />

<h3>💻 Full Stack Software Engineer | Web Developer 🌐</h3>

<p>
Passionate about building modern, scalable and high-performance web & mobile applications with the Microsoft .NET ecosystem and modern JavaScript frameworks.
</p>

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="700">

</div>

---

## 🚀 About Me

- 🔭 I'm currently working on **Full Stack Web Applications**
- 🌱 I'm always learning and exploring **new technologies**
- 💬 Ask me about **.NET, ASP.NET Core, Angular, React, SQL**
- ⚡ Fun fact: I love turning ☕ into clean code!
- 📫 How to reach me: **pavelwahid1@gmail.com**

---

## 🛠️ Tech Stack

### 💎 Backend Development
<p>
<img src="https://img.shields.io/badge/ASP.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
<img src="https://img.shields.io/badge/ASP.NET%20Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
<img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
<img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white" />
<img src="https://img.shields.io/badge/Entity%20Framework-6C3483?style=for-the-badge&logo=nuget&logoColor=white" />
<img src="https://img.shields.io/badge/EF%20Core-6C3483?style=for-the-badge&logo=nuget&logoColor=white" />
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
</p>

### 🏛️ Architecture & Patterns
<p>
<img src="https://img.shields.io/badge/MVC-E34F26?style=for-the-badge&logo=dotnet&logoColor=white" />
<img src="https://img.shields.io/badge/MVC%20Core-FF6B6B?style=for-the-badge&logo=dotnet&logoColor=white" />
<img src="https://img.shields.io/badge/REST%20API-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
</p>

### 🎨 Frontend Development
<p>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white" />
<img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white" />
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
<img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" />
</p>

### 📱 Mobile / Cross-Platform
<p>
<img src="https://img.shields.io/badge/.NET%20MAUI-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
</p>

### 🗄️ Database
<p>
<img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" />
<img src="https://img.shields.io/badge/T--SQL-003B57?style=for-the-badge&logo=databricks&logoColor=white" />
</p>

### 🧰 Tools & Platforms
<p>
<img src="https://img.shields.io/badge/Visual%20Studio-5C2D91?style=for-the-badge&logo=visualstudio&logoColor=white" />
<img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" />
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
<img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" />
</p>

---

## 📊 GitHub Statistics

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=pavelwahid&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=pavelwahid&layout=compact&langs_count=8&theme=tokyonight"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=pavelwahid&theme=tokyonight" alt="GitHub Streak" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=pavelwahid&theme=tokyo-night&hide_border=true" width="95%" alt="Activity Graph" />

</div>

---

## 🏆 GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=pavelwahid&theme=tokyonight&no-frame=true&no-bg=false&margin-w=4&row=1" alt="Trophies" />

</div>

---

## 🌐 Connect With Me

<div align="center">

<a href="https://www.linkedin.com/in/pavel-softwaredeveloper/" target="_blank">
<img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="mailto:pavelwahid1@gmail.com">
<img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
<a href="https://www.facebook.com/mdpavelwahid" target="_blank">
<img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" />
</a>
<a href="https://YOUR_PORTFOLIO.com" target="_blank">
<img src="https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=todoist&logoColor=white" />
</a>

</div>

---

<div align="center">

### 💡 "Code is like humor. When you have to explain it, it's bad." – Cory House

<img src="https://komarev.com/ghpvc/?username=pavelwahid&label=Profile%20Views&color=00d9ff&style=for-the-badge" alt="Profile Views" />

⭐️ From your friendly neighborhood **Full Stack Developer** ⭐️

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" width="100%"/>

</div>
