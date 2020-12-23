<h4 class="text-center" style="margin-top:30px">Button/Iframe API</h4>        
						<br />
						<h4 class="panel-title panel-heading">Set the "src" attribute of an HTML iframe to:</h4>
						<pre class="prettyprint lang-html">https://s1.mp3hot.cc/@api/button/<b><span class="nocode" style="color:#65b042">{format}</span></b>/<b><span class="nocode" style="color:#65b042">{YouTube-Video-ID}</span></b></pre>						
						<h4 class="panel-title panel-heading">...where <code><b>{format}</b></code> is one of the following:</h4>
						<div class="panel-title panel-heading">
							<ul style="margin-bottom:0">
								<li>"<b>mp3</b>" : for MP3 results</li> 
																	<li>"<b>videos</b>" : for Video w/Audio results</li>
																									<li>"<b>mergedstreams</b>" : for Merged Video + Audio results</li>
																<li>"<b>videostreams</b>" : for Video-Only results</li>
								<li>"<b>audiostreams</b>" : for Audio-Only results</li>
							</ul>
						</div>
						<h4 class="panel-title panel-heading">...and <code><b>{YouTube-Video-ID}</b></code> is any valid YouTube video ID.</h4>
						<h4 class="panel-title panel-heading">The resulting iframe code and corresponding output should look like one of the following, e.g.:</h4>
						<div>
							<!-- Nav tabs -->
							<div class="panel-heading">
								<ul class="nav nav-tabs" role="tablist" id="button-api-tabs">
									<li role="presentation" class="active"><a href="#mp3-button-api" aria-controls="home" role="tab" data-toggle="tab">MP3</a></li>
																			<li role="presentation"><a href="#videos-button-api" aria-controls="profile" role="tab" data-toggle="tab">Video w/Audio</a></li>
																												<li role="presentation"><a href="#mergedstreams-button-api" aria-controls="profile" role="tab" data-toggle="tab">Merged Video + Audio</a></li>
																		<li role="presentation"><a href="#videostreams-button-api" aria-controls="messages" role="tab" data-toggle="tab">Video-Only</a></li>
									<li role="presentation"><a href="#audiostreams-button-api" aria-controls="settings" role="tab" data-toggle="tab">Audio-Only</a></li>
								</ul>
							</div>

<pre class="prettyprint lang-html">&#x3C;iframe class="button-api-frame" src="https://s1.mp3hot.cc/@api/button/mp3/CevxZvSJLk8" width="100%" height="100%" allowtransparency="true" scrolling="no" style="border:none"&#x3E;&#x3C;/iframe&#x3E;

&#x3C;!-- Optional script that automatically makes iframe content responsive. --&#x3E;
&#x3C;script src="https://cdnjs.cloudflare.com/ajax/libs/iframe-resizer/3.5.14/iframeResizer.min.js"&#x3E;&#x3C;/script&#x3E;
&#x3C;script&#x3E;iFrameResize({checkOrigin: false}, '.button-api-frame');&#x3C;/script&#x3E;</pre>

<pre class="prettyprint lang-html">&#x3C;iframe class="button-api-frame" src="https://s1.mp3hot.cc/@api/button/videos/CevxZvSJLk8" width="100%" height="100%" allowtransparency="true" scrolling="no" style="border:none"&#x3E;&#x3C;/iframe&#x3E;

&#x3C;!-- Optional script that automatically makes iframe content responsive. --&#x3E;
&#x3C;script src="https://cdnjs.cloudflare.com/ajax/libs/iframe-resizer/3.5.14/iframeResizer.min.js"&#x3E;&#x3C;/script&#x3E;
&#x3C;script&#x3E;iFrameResize({checkOrigin: false}, '.button-api-frame');&#x3C;/script&#x3E;</pre>

<a href="https://s1.mp3hot.cc" target="_blank"><span>More info</span></a>
