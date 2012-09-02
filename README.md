LoUBBCode
=========

Adds extra functionality to Lord of Ultima chat 

<h3>Overview</h3>
<p>Proof of Concept Script - extend the LoU-Chat, IGM and Forum posts with custom BBCode and emoticons</p>
<p></p>
<h3>Features</h3>
<p></p>
<ul>
<li>Hijack the Chat</li>
<li>Implements emoticons</li>
<li>Hijack and extend UBB-Code</li>
<li>Social Gadjets: Like, Slap, Poke ...</li>
<br>
<p>More features will be added in the future.</p>
</ul>
<h3>Changelog</h3>
<p></p>
<ul>
<li>1.0   - initial</li>
<li>1.1   - fix dependency</li>
<li>1.2   - fix sample onNewMessage injection</li>
<li>1.3   - add [pre] - Text in a pre element is displayed in a fixed-width</li>
<li>1.3.1 - fix [pre] to match any character including newlines</li>
<li>1.4   - add social gadjets</li>
<li>1.4.1 - add version to greeting</li>
<li>1.4.2 - fix hide Error message</li>
<li>1.4.3 - fix wrong chat notify for empty string with emoticon</li>
<li>1.4.4 - minor fix, add some shortcuts and fix the devil ;)</li>
<li>1.5   - clear up code with JSLint, @see http://www.jslint.com/</li>
<p></p>
</ul>
<h3>HowTo</h3>
<p></p>
<ul>
<li>
<pre>
Including an image within IGM or Forum
[img]http://www.bbcode.org/images/lubeck_small.jpg[/img]
Resizing the image
[img=100x50]http://www.bbcode.org/images/lubeck_small.jpg[/img]
Making the image clickable (in this case linking to the original image)
[url=http://www.bbcode.org/images/lubeck.jpg][img]http://www.bbcode.org/images/lubeck_small.jpg[/img][/url]
</pre></li>

<li>Use Emoticons</u>
<p>Just write ;)</p></li>

<li>Use social gadjets</u>
<p>Just whisper to anyone :)</p>
<pre>
/whisper BloodHeart !LoU.Love
/whisper BloodHeart !LoU.Like
/whisper BloodHeart !LoU.Vote
/whisper BloodHeart !LoU.Poke
/whisper BloodHeart !LoU.Slap
</pre>
<b>!LoU.Slap and !LoU.Love are anonym ;)</b>
</li>
</ul>
<h3>Credits</h3>
<p>
Special thanks to Ben Alman http://benalman.com/projects/javascript-emotify</p>