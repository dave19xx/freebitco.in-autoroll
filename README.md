<span><div class="PostFull__header"><h1 class="entry-title"><!-- react-text: 212 -->freebitcoin script!! For a lot of money automatically<!-- /react-text --></h1><span class="PostFull__time_author_category_large vcard"><div class="Userpic" style="background-image: url(&quot;https://steemitimages.com/u/oscarbur7/avatar&quot;);"></div><div class="right-side"><span class="Author"><span itemprop="author" itemscope="" itemtype="http://schema.org/Person"><strong><a href="/@oscarbur7"><!-- react-text: 220 -->oscarbur7<!-- /react-text --><!-- react-text: 221 --> <!-- /react-text --><span class="Reputation" title="Reputation"><!-- react-text: 223 -->(<!-- /react-text --><!-- react-text: 224 -->28<!-- /react-text --><!-- react-text: 225 -->)<!-- /react-text --></span><span class="Icon dropdown-arrow" style="display: inline-block; width: 1.12rem; height: 1.12rem;"><svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 512 512" enable-background="new 0 0 512 512" xml:space="preserve"><g><polygon points="128,90 256,218 384,90"></polygon></g></svg></span></a></strong><span><!-- react-text: 228 --><!-- /react-text --></span></span><!-- react-empty: 229 --></span><!-- react-text: 230 -->in<!-- /react-text --><!-- react-text: 231 --> <!-- /react-text --><a href="/trending/bitcoin">#bitcoin</a><!-- react-text: 233 --> • <!-- /react-text --><span title="8/18/2017 5:07 AM"><span>5 years ago</span></span><!-- react-text: 236 --> <!-- /react-text --><!-- react-empty: 237 --></div></span></div><div class="PostFull__body entry-content"><div class="MarkdownViewer Markdown"><div><p><img src="https://steemitimages.com/640x0/https://pbs.twimg.com/profile_images/771941643004051458/ScAR5Tf2.jpg" srcset="https://steemitimages.com/640x0/https://pbs.twimg.com/profile_images/771941643004051458/ScAR5Tf2.jpg 1x, https://steemitimages.com/1280x0/https://pbs.twimg.com/profile_images/771941643004051458/ScAR5Tf2.jpg 2x"></p>
<p>1)Go to  <a href="https://freebitco.in" rel="nofollow noopener" title="This link will take you away from steemit.com">https://freebitco.in</a>...</p>
<ol>
<li><p>Go to MULTIPLY BTC</p></li>
<li><p>Press F12</p></li>
<li><p>Go to Console</p></li>
<li><p>Copy and Paste the script in the console</p></li>
<li><p>Press Enter</p></li>
<li><p>Enjoy</p></li>
</ol>
<p>var startValue = '0.00000001', // Don't lower the decimal point more than 4x of current balance<br>
stopPercentage = 0.001,<br>
maxWait = 777,<br>
stopped = false, // debugging<br>
stopBefore = 1; // In minutes for timer before stopping redirect on webpage</p>
<p>var $loButton = $('#double_your_btc_bet_lo_button'),<br>
$hiButton = $('#double_your_btc_bet_hi_button');</p>
<p>function multiply(){<br>
var current = $('#double_your_btc_stake').val();<br>
var multiply = (current * 2).toFixed(8);<br>
$('#double_your_btc_stake').val(multiply);<br>
}</p>
<p>function getRandomWait(){<br>
var wait = Math.floor(Math.random() * maxWait ) + 100;</p>
<p>console.log('Waiting for ' + wait + 'ms before next bet.');</p>
<p>return wait ;<br>
}</p>
<p>function startGame(){<br>
console.log('Game started!');<br>
reset();<br>
$loButton.trigger('click');<br>
}</p>
<p>function stopGame(){<br>
console.log('Game will stop soon! Let me finish.');<br>
stopped = true;<br>
}</p>
<p>function reset(){<br>
$('#double_your_btc_stake').val(startValue);<br>
}</p>
<p>// quick and dirty hack if you have very little bitcoins like 0.00000001<br>
function deexponentize(number){<br>
return number * 10000000;</p>
</div></div></div></span>
