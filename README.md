<h1 style="text-align: center;">GeSHi Pro</h1>
<p>This project was first started by <a href="http://richardtuin.com" target="_blank">Richard Tuin</a> and now I have taken on the task of intergating this excellant software into <a href="http://fckeditor.net" target="_blank">FCKeditor</a></p>
<p>GeSHi Pro is for the FCKeditor and is an implementation of the famous php Geshi library for FCKeditor. This FCKeditor plugin helps you to put scripting code colored in FCKeditor. It automatically syntax highlight's code, color's the code you enter, and adds the generated code to FCKeditor.</p>
<p>This FCKeditor plugin uses the <a href="http://qbnz.com/highlighter/" target="_blank">GeSHi</a> library. GeSHi stands for Generic Syntax Highlighter and <span style="font-style: italic;">supports a wide variety of programming languages</span>. Including: C#, PHP, ASP, VB, javascript, actionscript, C++, delphi and many more (GeSHi can highlight 80+ languages by default).</p>
<p>Since GeSHi is a PHP script, this FCKeditor plugin only works if your webserver is PHP-enabled.</p>
<p>GeSHi Pro for FCKeditor is easy to install and even more easy to use. <span style="font-weight: bold;"><br /> Give it a try!</span></p>

<h2>What's New</h2>
<p>version 1.2:</p>
<ul>
<li>Updated the geshi javascript to be compatable with FCKeditor 1.6</li>
</ul>
<h2>Features</h2>
<ul>
<li><span style="font-size: small;"><span style="font-family: Verdana;">choice of line numbers (none, normal or fancy)</span></span></li>
<li><span style="font-size: small;"><span style="font-family: Verdana;">add tab width</span></span></li>
<li><span style="font-size: small;"><span style="font-family: Verdana;">enable CSS classes</span></span></li>
<li><span style="font-size: small;"><span style="font-family: Verdana;">choice of code container (none, &lt;pre&gt; or &lt;div&gt;)</span></span></li>
</ul>
<h2>Requirements</h2>
<ul>
<li>FCKeditor</li>
<li>PHP enabled website</li>
</ul>
<h2>Demo</h2>
<p>A demo of GeSHi Pro can be found <a href="http://demo.shaunfreeman.co.uk/GeSHiPro/index.php">here</a></p>
<h2>How to Install</h2>
<p>You can install the plugin by extracting the 'geshipro' folder from the gzip file, and copy it to your FCKeditor plugin directory (which is '<span style="font-style: italic;">editor/plugins/</span>' usually). <br /> To enable the plugin you have to add the following lines at the lines mentioned in fckconfig.js (in the FCKeditor root directory):</p>
<ul>
<li><span style="color: #000000;"><span style="font-weight: bold;">ADD:</span> </span>FCKConfig.<span style="color: #006600;">Plugins</span>.<span style="color: #006600;">Add</span><span style="color: #66cc66;">(</span> <span style="color: #3366cc;">'geshipro'</span>, <span style="color: #3366cc;">'en'</span> <span style="color: #66cc66;">)</span> ;</li>
<li><span style="color: #000000;"><span style="font-weight: bold;">BEFORE:</span>&nbsp; </span>FCKConfig.<span style="color: #006600;">AutoGrowMax</span> = <span style="color: #cc0000;">400</span> ;</li>
</ul>
<p>To have the plugin's button on the toolbar in FCKeditor (which is mandatory to get it to work) you have to add it to the toolbar. To add the button to the <span style="font-style: italic;">Default Toolbar</span> in FCKeditor you must find the array<span style="color: #000000;"> '</span>FCKConfig.<span style="color: #006600;">ToolbarSets</span><span style="color: #66cc66;">[</span><span style="color: #3366cc;">"Default"</span><span style="color: #66cc66;">]</span><span style="color: #000000;">' </span>in the fckconfig.js file.<span style="color: #000000;"><br /> </span> Within this array find the line<span style="color: #000000;"> '</span><span style="color: #66cc66;">[</span><span style="color: #3366cc;">'Undo'</span>,<span style="color: #3366cc;">'Redo'</span>,<span style="color: #3366cc;">'-'</span>,<span style="color: #3366cc;">'Find'</span>,<span style="color: #3366cc;">'Replace'</span>,<span style="color: #3366cc;">'-'</span>,<span style="color: #3366cc;">'SelectAll'</span>,<span style="color: #3366cc;">'RemoveFormat'</span><span style="color: #66cc66;">]</span>,<span style="color: #000000;">'</span> and <span style="font-weight: bold; font-style: italic;">replace it</span> with<span style="color: #000000;"> '</span><span style="color: #66cc66;">[</span><span style="color: #3366cc;">'Undo'</span>,<span style="color: #3366cc;">'Redo'</span>,<span style="color: #3366cc;">'-'</span>,<span style="color: #3366cc;">'Find'</span>,<span style="color: #3366cc;">'Replace'</span>,<span style="color: #3366cc;">'-'</span>,<span style="color: #3366cc;">'SelectAll'</span>,<span style="color: #3366cc;">'RemoveFormat'</span>,<span style="color: #3366cc;">'-'</span>,<span style="color: #3366cc;">'GeSHiPro'</span><span style="color: #66cc66;">]</span>,<span style="color: #000000;">'.</span></p>
<p>Now the plugin should be working! Have fun with it!</p>
<p>Feel free to email me if you have problems with this plugin, also email me to let me know what to inprove or if you just like it! <img src="admin/editor/fckeditor/editor/images/smiley/msn/wink_smile.gif" alt="" /></p>
