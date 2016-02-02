#Wolf.Playout.Builds
"Wolf.PlayOut" is the codename of a TV broadcast Playout automation software which is currently using by <a href="http://en.alalam.ir/">AlAlam News Network TV</a> and optimized based MOS Protocol. This software have been developed based an in-house open source game engine called <a href="https://github.com/PooyaEimandar/Wolf.Engine">"Wolf Engine"</a>.
<hr>
<h2>Youtube video</h2>
<a href="https://www.youtube.com/watch?v=EZSdEjBvuGY" target="_blank"><img src="https://i.ytimg.com/vi/EZSdEjBvuGY/3.jpg?time=1450630345794" width="240" height="180" border="10" /></a>
<hr>
<h2>Builds</h2>
You can find the latest stable development builds here:
<table style="width:100%">
<tbody>
<tr>
	<th>Current Release</th>
	<th>Video samples</th>
	<th>Operating System</th>
	<th>Playback mode</th>
	<th>Supported video formats</th>
	<th>Supported extensions</th>
	<th>Video bitrate</th>
	<th>Audio channel</th>
	<th>Audio depth</th>
	<th>Audio sample rate</th>
</tr>
<tr>
	<td>
	    <a href="https://github.com/WolfSource/Wolf.Playout.Builds/raw/master/Wolf.PlayOut.Builds/HD_1080p_50/Wolf.PlayOut.Win_1.11.1.0_HD_1080p_50.7z">1.11.1.0</a>
	</td>
	<td><a href="https://netorgft1046267-my.sharepoint.com/personal/contact_wolfsource_io/_layouts/15/guestaccess.aspx?guestaccesstoken=27Y19GfEMpEAiUYBav49u6mPqfsazVU8zf%2fgawPK8qI%3d&docid=15b997a25e85044bbb41da1cb5f6ec425">HD_1080p_50.mp4</a></td>
	<td>Windows 8.1/10 x64 bit</td>
	<td>1080-50p</td>	
	<td>
	    <ul>
	        <li>x265</li>
	        <li>x264</li>
	        <li>mpeg4</li>
	        <li>mpeg2</li>
	        <li>DV</li>
	    </ul>
	</td>
	<td>
	    <ul>
	        <li>avi</li>
	        <li>mp4</li>
	        <li>mpg</li>
	    </ul>
	</td>
	<td>
	    15-30 Mbps
	</td>
	<td>2</td>
	<td>16</td>
	<td>192 khz</td>
</tr>
<tr>
	<td>
	   <a href="https://github.com/WolfSource/Wolf.Playout.Builds/raw/master/Wolf.PlayOut.Builds/SD_PAL_25/Wolf.PlayOut.Win_1.11.1.0_SD_PAL_25.7z">1.11.1.0</a>
	</td>
	<td><a href="https://netorgft1046267-my.sharepoint.com/personal/contact_wolfsource_io/_layouts/15/guestaccess.aspx?guestaccesstoken=ytEvbMzDLZiHGQwzRr1t%2fWBQEqG4R2WMUm4dIDJp%2flI%3d&docid=1010d64fc284541e7bfa52eb193f4ebc2">SD_PAL_25.mp4</a></td>
	<td>Windows 8.1/10 x64 bit</td>
	<td>PAL-25p</td>	
	<td>
	    <ul>
	        <li>x265</li>
	        <li>x264</li>
	        <li>mpeg4</li>
	        <li>mpeg2</li>
	        <li>DV</li>
	    </ul>
	</td>
	<td>
	    <ul>
	        <li>avi</li>
	        <li>mp4</li>
	        <li>mpg</li>
	    </ul>
	</td>
	<td>
	    <ul>
	        4-8 Mbps
	    </ul>
	</td>
	<td>2</td>
	<td>16</td>
	<td>192 khz</td>
</tr>
</tbody></table>
<h2>Prerequisite</h2>
The following are some essential prerequisites that should be considered before runnin the application:
<ul>
<li>The first important requirement is a PC running on Windows 8.1/10, with full hd output resolutions(1920 * 1080). Currently Wolf has not DYNAMIC layout</li>
<li>Make sure setup <a href="https://www.microsoft.com/en-us/download/details.aspx?id=48145">Visual C++ Redistributable for Visual Studio 2015 - 	
vc_redist.x64.exe</a></li>
<li>Make sure setup <a href="https://www.blackmagicdesign.com/support/download/e852cd3967694dd9810f57c16fa2c6a2/Windows">BlackMagic Desktop Video 10.5.2 Update</a></li>
<li>Install following <a href="https://github.com/WolfSource/Wolf.Playout.Builds/raw/master/Dependencies/Fonts.zip">fonts</a> on your target machine</li>
</ul>
<hr>
<h2>System Recommendations</h2>
<ul>
<li><strong>CPU</strong>: Wolf Playout takes advantage of multi-threading, so especially for Playing HD 1080p-50, a multi-core CPU is highly recommended.</li>
<li><strong>GPU</strong>: Wolf Playout requires at least DirectX 11.1, but we encourage you to plan you hardware specifications with DirectX12 consideration for next updates. Make sure update your Graphics Card Driver to the latest one and also update WDDM from windows update.</li>
<li><strong>RAM</strong>: At least 16 GB RAM needed for HD playback. (Wolf.PlayOut supports one minute buffering for media, this is efficient way for playing media from network)</li>
<li><strong>Storage</strong>: SSD Hard drives is highly recommended</li>
<li><strong>Blackmagic Decklink Cards</strong>: BlackMagic Design DeckLink 4K Extreme SDI video card is highly recommended, however Wolf tested on Blackmagic Design Decklink Intensity pro & Blackmagic Design Decklink HD Extreme 3D cards</li>
</ul>
<hr>
<h2>Bugs & Issues</h2>
Although I have taken every care to ensure the accuracy of this product, mistakes do happen and this playout is just at the begining of it's survey. If you find any bug, I would be grateful if you would report this to me at <a href="https://github.com/WolfSource/Wolf.Playout.Builds/issues">here</a>. 
<h2>Change Log</h2>
<a href="#">Change Log</a>
<h2>LICENSE</h2>
<a href="https://github.com/WolfSource/Wolf.Playout.Builds/blob/master/LICENSE">MIT LICENSE</a>
<hr>
<h2>Twitter</h2>
<a href="http://twitter.com/wolf_source">@Wolf_Source</a>
<a href="http://twitter.com/pooyaeimandar">@PooyaEimandar</a>
<hr>
<h2>Contact</h2>
If you're running a business that needs to use this playout or would like to change or add new features to it, you can send an email to contact{at}WolfSource{dot}io .Kindly do not email bugs & questions and just post it on issue page.   
