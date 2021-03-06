---
layout: page
title: Стили
permalink: /style-guide
image: '/images/pages/about.jpeg'
---

<h1 class='c-post__title u-text-center'>Style Guide</h1>

         
 <img src='/images/pages/styleguide.jpg' class='c-post__image' alt='Style Guide'>

<p>At <a href="http://aspirethemes.com/">Aspire Themes</a> I use a <strong>lot</strong> of tools to help me create WordPress, Ghost and Jekyll themes. Tools will range from development, design, services, hosting and automation.</p>

<p>Graphic design is the paradise of individuality, eccentricity, heresy, abnormality, hobbies, and humors. — George Santayana.</p>

<hr />

<h1 id="simple-default-styles-for-headings">Simple default styles for headings</h1>

<h2 id="simple-default-styles-for-headings-1">Simple default styles for headings</h2>

<h3 id="simple-default-styles-for-headings-2">Simple default styles for headings</h3>

<h4 id="simple-default-styles-for-headings-3">Simple default styles for headings</h4>

<h5 id="simple-default-styles-for-headings-4">Simple default styles for headings</h5>

<h6 id="simple-default-styles-for-headings-5">Simple default styles for headings</h6>

<hr />

<ul>
  <li>Ut at interdum nunc. Maecenas commodo turpis quis elementum gravida.</li>
  <li>Nunc ac sapien tellus. Quisque risus enim, tempus eget porttitor.</li>
  <li>Donec nibh massa, rutrum a sollicitudin eu, lacinia in lorem.</li>
</ul>

<hr />

<ol>
  <li>Ut at interdum nunc. Maecenas commodo turpis quis elementum gravida.</li>
  <li>Nunc ac sapien tellus. Quisque risus enim, tempus eget porttitor in.</li>
  <li>Donec nibh massa, rutrum a sollicitudin eu.</li>
</ol>

<hr />

<blockquote>
  <p>Graphic design is the paradise of individuality, eccentricity, heresy, abnormality, hobbies, and humors. — George Santayana</p>
</blockquote>

<hr />

<figure class="highlight"><pre><code class="language-js" data-lang="js"><span class="s1">'use strict'</span><span class="p">;</span>
<span class="kd">var</span> <span class="nx">markdown</span> <span class="o">=</span> <span class="nx">require</span><span class="p">(</span><span class="s1">'markdown'</span><span class="p">).</span><span class="nx">markdown</span><span class="p">;</span>
<span class="kd">function</span> <span class="nx">Editor</span><span class="p">(</span><span class="nx">input</span><span class="p">,</span> <span class="nx">preview</span><span class="p">)</span> <span class="p">{</span>
  <span class="k">this</span><span class="p">.</span><span class="nx">update</span> <span class="o">=</span> <span class="kd">function</span><span class="p">()</span> <span class="p">{</span>
    <span class="nx">preview</span><span class="p">.</span><span class="nx">innerHTML</span> <span class="o">=</span> <span class="nx">markdown</span><span class="p">.</span><span class="nx">toHTML</span><span class="p">(</span><span class="nx">input</span><span class="p">.</span><span class="nx">value</span><span class="p">);</span>
  <span class="p">};</span>
  <span class="nx">input</span><span class="p">.</span><span class="nx">editor</span> <span class="o">=</span> <span class="k">this</span><span class="p">;</span>
  <span class="k">this</span><span class="p">.</span><span class="nx">update</span><span class="p">();</span>
<span class="p">}</span></code></pre></figure>

<p>You can add inline code just like this, E.g. <code class="highlighter-rouge">.code { color: #fff; }</code></p>

<figure class="highlight"><pre><code class="language-css" data-lang="css"><span class="nt">pre</span> <span class="p">{</span>
  <span class="nl">background-color</span><span class="p">:</span> <span class="m">#f4f4f4</span><span class="p">;</span>
  <span class="nl">max-width</span><span class="p">:</span> <span class="m">100%</span><span class="p">;</span>
  <span class="nl">overflow</span><span class="p">:</span> <span class="nb">auto</span><span class="p">;</span>
<span class="p">}</span></code></pre></figure>

<hr />

<p>Cras sed sodales enim. Duis nec erat magna. Sed scelerisque pretium mi et <a href="https://unsplash.com/">unsplash</a> ullamcorper mauris aliquam ornare fringilla. In luctus commodo quam eget posuere.</p>

<hr />

<iframe src="https://player.vimeo.com/video/212114694?title=0&amp;byline=0&amp;portrait=0" width="640" height="360" frameborder="0" webkitallowfullscreen="" mozallowfullscreen="" allowfullscreen=""></iframe>

<hr />

<iframe src="https://embed.ted.com/talks/ted_halstead_a_climate_solution_where_all_sides_can_win" width="640" height="360" frameborder="0" scrolling="no" allowfullscreen=""></iframe>

<hr />

<iframe width="100%" height="166" scrolling="no" frameborder="no" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/29738591&amp;color=ff5500&amp;auto_play=false&amp;hide_related=false&amp;show_comments=true&amp;show_user=true&amp;show_reposts=false"></iframe>

<hr />

<p data-height="265" data-theme-id="light" data-slug-hash="YWvpRo" data-default-tab="css,result" data-user="kharrop" data-embed-version="2" data-pen-title="Referral Form" class="codepen">See the Pen <a href="http://codepen.io/kharrop/pen/YWvpRo/">Referral Form</a> by Kelly Harrop (<a href="http://codepen.io/kharrop">@kharrop</a>) on <a href="http://codepen.io">CodePen</a>.</p>
<script async="" src="https://production-assets.codepen.io/assets/embed/ei.js"></script>

<hr />

<p><img src="/images/posts/image17.jpg" alt="about" /></p>

<hr />

<p><input type="text" placeholder="I'm an input field!" /></p>

<hr />

<p><button class="c-btn c-btn--small">Button</button></p>

<p><button class="c-btn">Button</button></p>

<p><button class="c-btn c-btn--full">Button</button></p>

<figure class="highlight"><pre><code class="language-html" data-lang="html"><span class="nt">&lt;button</span> <span class="na">class=</span><span class="s">'c-btn c-btn--small'</span><span class="nt">&gt;</span>Button<span class="nt">&lt;/button&gt;</span>
<span class="nt">&lt;button</span> <span class="na">class=</span><span class="s">'c-btn'</span><span class="nt">&gt;</span>Button<span class="nt">&lt;/button&gt;</span>
<span class="nt">&lt;button</span> <span class="na">class=</span><span class="s">'c-btn c-btn--full'</span><span class="nt">&gt;</span>Button<span class="nt">&lt;/button&gt;</span></code></pre></figure>
