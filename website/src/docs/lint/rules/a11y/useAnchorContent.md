---
title: Lint Rule a11y/useAnchorContent
layout: layouts/rule.liquid
showHero: false
description: MISSING DOCUMENTATION
eleventyNavigation:
	key: lint-rules/a11y/useAnchorContent
	parent: lint-rules
	title: a11y/useAnchorContent
---

# a11y/useAnchorContent

MISSING DOCUMENTATION

<!-- GENERATED:START(hash:da39a3ee5e6b4b0d3255bfef95601890afd80709,id:description) Everything below is automatically generated. DO NOT MODIFY. Run `./rome run scripts/generated-files/lint-rules` to update. -->

<!-- GENERATED:END(id:description) -->

<!-- GENERATED:START(hash:b6f6c227c3ba598f097bbbf2ad1d60d695edea96,id:examples) Everything below is automatically generated. DO NOT MODIFY. Run `./rome run scripts/generated-files/lint-rules-docs` to update. -->
## Examples

### Invalid

{% raw %}<pre class="language-js"><code class="language-js">&lt;<span class="token variable">a</span> <span class="token operator">/</span>&gt;</code></pre>{% endraw %}
{% raw %}<pre class="language-text"><code class="language-text">
 <span style="text-decoration-style: dashed; text-decoration-line: underline;">file.jsx:1</span> <strong>lint/a11y/useAnchorContent</strong> ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  <strong><span style="color: Tomato;">✖ </span></strong><span style="color: Tomato;">Provide screen reader accessible content when using </span><span style="color: Tomato;"><strong>anchor</strong></span><span style="color: Tomato;"> elements.</span>

    &lt;<span class="token variable">a</span> <span class="token operator">/</span>&gt;
    <span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span>

  <strong><span style="color: rgb(38, 148, 255);">ℹ </span></strong><span style="color: rgb(38, 148, 255);">All links on a page should have content that is accessible to screen</span>
    <span style="color: rgb(38, 148, 255);">readers.</span>

</code></pre>{% endraw %}

---

{% raw %}<pre class="language-js"><code class="language-js">&lt;<span class="token variable">a</span>&gt;&lt;<span class="token variable">TextWrapper</span> <span class="token attr-name">aria-hidden</span> <span class="token operator">/</span>&gt;&lt;<span class="token operator">/</span><span class="token variable">a</span>&gt;</code></pre>{% endraw %}
{% raw %}<pre class="language-text"><code class="language-text">
 <span style="text-decoration-style: dashed; text-decoration-line: underline;">file.jsx:1</span> <strong>lint/a11y/useAnchorContent</strong> ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  <strong><span style="color: Tomato;">✖ </span></strong><span style="color: Tomato;">Provide screen reader accessible content when using </span><span style="color: Tomato;"><strong>anchor</strong></span><span style="color: Tomato;"> elements.</span>

    &lt;<span class="token variable">a</span>&gt;&lt;<span class="token variable">TextWrapper</span> <span class="token attr-name">aria-hidden</span> <span class="token operator">/</span>&gt;&lt;<span class="token operator">/</span><span class="token variable">a</span>&gt;
    <span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span>

  <strong><span style="color: rgb(38, 148, 255);">ℹ </span></strong><span style="color: rgb(38, 148, 255);">All links on a page should have content that is accessible to screen</span>
    <span style="color: rgb(38, 148, 255);">readers.</span>

</code></pre>{% endraw %}
{% raw %}<pre class="language-html"><code class="language-html"><span class="token punctuation">&lt;</span><span class="token tag">a</span><span class="token punctuation">&gt;</span><span class="token punctuation">&lt;/</span><span class="token attr-name">a</span><span class="token punctuation">&gt;</span></code></pre>{% endraw %}
{% raw %}<pre class="language-text"><code class="language-text">
 <span style="text-decoration-style: dashed; text-decoration-line: underline;">file.html:1</span> <strong>lint/a11y/useAnchorContent</strong> ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  <strong><span style="color: Tomato;">✖ </span></strong><span style="color: Tomato;">Provide screen reader accessible content when using </span><span style="color: Tomato;"><strong>anchor</strong></span><span style="color: Tomato;"> elements.</span>

    <span class="token punctuation">&lt;</span><span class="token tag">a</span><span class="token punctuation">&gt;</span><span class="token punctuation">&lt;/</span><span class="token attr-name">a</span><span class="token punctuation">&gt;</span>
    <span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span>

  <strong><span style="color: rgb(38, 148, 255);">ℹ </span></strong><span style="color: rgb(38, 148, 255);">All links on a page should have content that is accessible to screen</span>
    <span style="color: rgb(38, 148, 255);">readers.</span>

</code></pre>{% endraw %}

### Valid

{% raw %}<pre class="language-js"><code class="language-js">&lt;<span class="token variable">a</span>&gt;Anchor Content!&lt;<span class="token operator">/</span><span class="token variable">a</span>&gt;</code></pre>{% endraw %}
{% raw %}<pre class="language-js"><code class="language-js">&lt;<span class="token variable">a</span>&gt;&lt;<span class="token variable">TextWrapper</span> <span class="token operator">/</span>&gt;&lt;<span class="token operator">/</span><span class="token variable">a</span>&gt;</code></pre>{% endraw %}
{% raw %}<pre class="language-js"><code class="language-js">&lt;<span class="token variable">a</span> <span class="token attr-name">dangerouslySetInnerHTML</span><span class="token operator">=</span><span class="token punctuation">{</span><span class="token punctuation">{</span> <span class="token variable">__html</span><span class="token punctuation">:</span> <span class="token string">&apos;foo&apos;</span> <span class="token punctuation">}</span><span class="token punctuation">}</span> <span class="token operator">/</span>&gt;</code></pre>{% endraw %}
{% raw %}<pre class="language-js"><code class="language-js">&lt;<span class="token variable">a</span>&gt;&lt;<span class="token variable">TextWrapper</span> <span class="token attr-name">aria-hidden</span><span class="token operator">=</span><span class="token punctuation">{</span><span class="token boolean">true</span><span class="token punctuation">}</span> <span class="token operator">/</span>&gt; visible content&lt;<span class="token operator">/</span><span class="token variable">a</span>&gt;</code></pre>{% endraw %}
{% raw %}<pre class="language-html"><code class="language-html"><span class="token punctuation">&lt;</span><span class="token tag">a</span><span class="token punctuation">&gt;</span>Anchor Content!<span class="token punctuation">&lt;/</span><span class="token attr-name">a</span><span class="token punctuation">&gt;</span></code></pre>{% endraw %}
{% raw %}<pre class="language-html"><code class="language-html"><span class="token punctuation">&lt;</span><span class="token tag">a</span><span class="token punctuation">&gt;</span><span class="token punctuation">&lt;</span><span class="token tag">div</span> <span class="token attr-name">aria-hidden</span><span class="token attr-equals">=</span><span class="token attr-value">&quot;true&quot;</span><span class="token punctuation">&gt;</span><span class="token punctuation">&lt;/</span><span class="token attr-name">div</span><span class="token punctuation">&gt;</span>visible content<span class="token punctuation">&lt;/</span><span class="token attr-name">a</span><span class="token punctuation">&gt;</span></code></pre>{% endraw %}
<!-- GENERATED:END(id:examples) -->
