<link rel="stylesheet" href="https://github.com/unix121/Themes/blob/master/style.css">
  <h1>Themes</h1>
  <ul>
   My Rice with DGD for the  Fedora Spin i3. 
  </ul>
  
  <h1>What you might need</h1>
  <ul>
    <li> i3-wm in any Linux distro you prefer</li>
    <li> <a href="https://github.com/jaagr/polybar">Polybar</a> (for most of the themes)</li>
    <li> <a href="https://davedavenport.github.io/rofi/">Rofi</a> (for most of the themes)</li>
    <li> You might need to copy the files located in "scripts" folder into "~/.config/polybar/"
      to make the Polybar configuration work properly on most themes.</li>
    <li> To recreate some of the GTK themes (for now) you can download <a href="https://github.com/actionless/oomox">oomox</a> and use the 
      colors located in "/{Theme_name}/.resources/.extend.Xresources" and recreate them.</li>
    <li> A few fonts might be required. <a href="https://github.com/chrissimpkins/Hack">Hack Font</a>, <a href="http://fontawesome.io/">Font Awesome</a> and <a href="http://www.dafont.com/monofur.font">monofur</a>.</li>
    <li> Firefox Themes can be installed using the "Stylish" extension</li>
  </ul>
  
<h1>Installation</h1> 
<ul>
 <h3>Manual Way</h3> To copy the basic configuration of a theme follow those steps:
  <ul>
  <li> git clone https://github.com/unix121/Themes </li>
  <li> cd {THEME_YOU_WANT_TO_APPLY}</li>
  <li> cp .i3/config ~/.i3/config (or ~/.config/i3/config depending on your configuration file location)</li>
  <li> cp .config/compton.conf ~/.config/compton.conf</li>
  <li> cp .config/polybar/config ~/.config/polybar/config</li>
  <li> cp ../scripts/polybar/launch.sh ~/.config/polybar/launch.sh</li>
  <li> cp ../scripts/polybar/music.sh ~/.config/polybar/music.sh</li>
  </ul>
  <h3>Automated way</h3> (In testing please use with caution)
  <ul>
  <li> git clone https://github.com/unix121/Themes</li>
  <li> cd scripts/</li>
  <li> ./apply_theme.sh {THEME} ({THEME} should be the name of the theme you want to apply)

    (example on how to apply the "Minimal" theme)

    ./apply_theme.sh Minimal
 </li>
  <li> NOTE: This script might not be working perfectly (yet), I will fix it when I have the time to do so.</li>
  </ul>
</ul>
  
<h1>Themes</h1>

<ul>
   <li><h2>DGD</h2>
    <img src="https://i.redd.it/zjf1avlghpv61.png">
    <a href="https://i.redd.it/zjf1avlghpv61.png">(More can be found here)</a></li>
  </ul>
