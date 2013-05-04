---
layout: index
---

<h1>docsync</h1>

<p>Testing methods to sync README.md and other documentation selectively from master branch to gh-pages and have a GitHub Pages site that when created using a layout from the Automatic Page Generator will keep updated with the markdown in the master branch.</p>

<p>The rest of this document a modified version of the [**example source**][4] for [**GitHub Flavored Markdown**][5] to use for testing:</p>

<h1>GitHub Flavored Markdown</h1>

<p><em>View the <a href="docs/source.txt">source of this content</a></em></p>

<p>Let's get the whole "linebreak" thing out of the way. The next paragraph contains two phrases separated by a single newline character:</p>

<p>Roses are red
Violets are blue</p>

<p>The next paragraph has the same phrases, but now they are separated by two spaces and a newline character:</p>

<p>Roses are red<br>
Violets are blue</p>

<h2>Math is hard, let's go shopping</h2>

<p>In first grade I learned that 5 &gt; 3 and 2 &lt; 7. Maybe some arrows. 1 -&gt; 2 -&gt; 3. 9 &lt;- 8 &lt;- 7.</p>

<p>Triangles man! a^2 + b^2 = c^2</p>

<h2>We all like making lists</h2>

<p>The above header should be an H2 tag. Now, for a list of fruits:</p>

<ul>
<li>Red Apples</li>
<li>Purple Grapes</li>
<li>Green Kiwifruits</li>
</ul><p>Let's get crazy:</p>

<ol>
<li>
<p>This is a list item with two paragraphs. Lorem ipsum dolor
sit amet, consectetuer adipiscing elit. Aliquam hendrerit
mi posuere lectus.</p>

<p>Vestibulum enim wisi, viverra nec, fringilla in, laoreet
vitae, risus. Donec sit amet nisl. Aliquam semper ipsum
sit amet velit.</p>
</li>
<li><p>Suspendisse id sem consectetuer libero luctus adipiscing.</p></li>
</ol><p>What about some code <strong>in</strong> a list? That's insane, right?</p>

<ol>
<li>
<p>In Ruby you can map like this:</p>

<pre><code>['a', 'b'].map { |x| x.uppercase }
</code></pre>
</li>
<li>
<p>In Rails, you can do a shortcut:</p>

<pre><code>['a', 'b'].map(&amp;:uppercase)
</code></pre>
</li>
</ol><p>Some people seem to like definition lists</p>

<dl>
<dt>Lower cost</dt>
  <dd>The new version of this product costs significantly less than the previous one!</dd>
  <dt>Easier to use</dt>
  <dd>We've changed the product so that it's much easier to use!</dd>
</dl><h2>I am a robot</h2>

<p>Maybe you want to print <code>robot</code> to the console 1000 times. Why not?</p>

<pre><code>def robot_invasion
  puts("robot " * 1000)
end
</code></pre>

<p>You see, that was formatted as code because it's been indented by four spaces.</p>

<p>How about we throw some angle braces and ampersands in there?</p>

<pre><code>&lt;div class="footer"&gt;
    &amp;copy; 2004 Foo Corporation
&lt;/div&gt;
</code></pre>

<h2>Set in stone</h2>

<p>Preformatted blocks are useful for ASCII art:</p>

<pre><code>         ,-. 
  ,     ,-.   ,-. 
 / \   (   )-(   ) 
 \ |  ,.&gt;-(   )-&lt; 
  \|,' (   )-(   ) 
   Y ___`-'   `-' 
   |/__/   `-' 
   | 
   | 
   |    -hrr- 
___|_____________ 
</code></pre>

<h2>Playing the blame game</h2>

<p>If you need to blame someone, the best way to do so is by quoting them:</p>

<blockquote>
<p>I, at any rate, am convinced that He does not throw dice.</p>
</blockquote>

<p>Or perhaps someone a little less eloquent:</p>

<blockquote>
<p>I wish you'd have given me this written question ahead of time so I
could plan for it... I'm sure something will pop into my head here in
the midst of this press conference, with all the pressure of trying to
come up with answer, but it hadn't yet...</p>

<p>I don't want to sound like
I have made no mistakes. I'm confident I have. I just haven't - you
just put me under the spot here, and maybe I'm not as quick on my feet
as I should be in coming up with one.</p>
</blockquote>

<h2>Table for two</h2>

<table>
<tr>
<th>ID</th>
<th>Name</th>
<th>Rank</th>
  </tr>
<tr>
<td>1</td>
<td>Tom Preston-Werner</td>
<td>Awesome</td>
  </tr>
<tr>
<td>2</td>
<td>Albert Einstein</td>
<td>Nearly as awesome</td>
  </tr>
</table><h3>Crazy linking action</h3>

<p>I get 10 times more traffic from <a href="http://google.com/" title="Google">Google</a> than from
<a href="http://search.yahoo.com/" title="Yahoo Search">Yahoo</a> or <a href="http://search.msn.com/" title="MSN Search">MSN</a>.</p>