<h1>Libretro Core Manager (lrcm)</h1>

<p>Libretro Core Manager (lrcm) usage:</p>
<ul>
    <li><b>list</b> - List exact names of all official cores</li>
    <li><b>add [CORE]</b> - Add [CORE] to your retroarch folder</li>
    <li><b>remove [CORE]</b> - Remove [CORE] from your retroarch folder</li>
    <li><b>update</b> - Update all of your libretro cores</li>
    <li><b>show</b> - Show cores that are currently installed</li>
    <li><b>log</b> - Output the contents of the logfile</li>
</ul>

<p>This script is meant to make libretro core management easier for those who are comfortable with the commandline. This project is in no way affiliated with libretro or retroarch; this is just something I decided to do out of boredom.</p>

<p>If you have your cores located somewhere other than <b>~/.config/retroarch/cores/</b> then you will need to specify exactly where in the <b>cores_path</b> variable at the top of the script. If you use an architecture other than <b>x86_64</b>, then you will need to edit the <b>cores_url</b> variable to the correct buildbot architecture. Lastly, if you wish the logfile to be located somewhere else, you can edit the <b>logfile</b> variable.</p>

<p>This script is meant to be used with the bash shell, so it should work wherever bash is present. I have only tested this on Linux, so there is no guarantee it will work on macOS or the "Windows Subsystem for Linux (WSL)."</p>

<p>To install this script and use it:</p>
<ul>
    <li>git clone http://github.com/cpinkus/lrcm</li>
    <li>cd lrcm</li>
    <li>chmod +x lrcm</li>
    <li>./lrcm</li>
</ul>

<p>The <b>lrcm</b> file is 100% portable, so you can move it wherever you want. I recommend placing it somewhere in your $PATH, such as /usr/local/bin.

<center>![Screenshot](screenshot.png?raw=true "Screenshot")</center>
