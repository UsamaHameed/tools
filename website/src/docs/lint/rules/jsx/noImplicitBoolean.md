---
title: Lint Rule jsx/noImplicitBoolean
layout: layouts/rule.liquid
description: MISSING DOCUMENTATION
eleventyNavigation:
	key: lint-rules/jsx/noImplicitBoolean
	parent: lint-rules
	title: jsx/noImplicitBoolean
---

# jsx/noImplicitBoolean

<!-- GENERATED:START(hash:0c842939a2a049e8cdb4f0be47baab529ffcaf37,id:description) Everything below is automatically generated. DO NOT MODIFY. Run `./rome run scripts/generated-files/lint-rules` to update. -->
MISSING DOCUMENTATION
<!-- GENERATED:END(id:description) -->

<!-- GENERATED:START(hash:6c75ed38c409ce3fcef7e217306886b896f5e7a2,id:examples) Everything below is automatically generated. DO NOT MODIFY. Run `./rome run scripts/generated-files/lint-rules-docs` to update. -->
## Examples

### Invalid

{% raw %}<pre class="language-js"><code class="language-js">&lt;<span class="token variable">input</span> <span class="token attr-name">disabled</span> <span class="token operator">/</span>&gt;</code></pre>{% endraw %}
{% raw %}<pre class="language-text"><code class="language-text">
 <span style="text-decoration-style: dashed; text-decoration-line: underline;">file.tsx:1:7</span> <strong>lint/jsx/noImplicitBoolean</strong> <span style="color: #000; background-color: #ddd;"> FIXABLE </span> ━━━━━━━━━━━━━━━━━━━━━━━━

  <strong><span style="color: Tomato;">✖ </span></strong><span style="color: Tomato;">Use explicit boolean values for boolean JSX props.</span>

    &lt;<span class="token variable">input</span> <span class="token attr-name">disabled</span> <span class="token operator">/</span>&gt;
           <span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span>

  <strong><span style="color: rgb(38, 148, 255);">ℹ </span></strong><span style="color: rgb(38, 148, 255);">Safe fix</span>

  <span style="color: Tomato;">-</span> <span style="color: Tomato;">disabled</span>
  <span style="color: MediumSeaGreen;">+</span> <span style="color: MediumSeaGreen;">disabled</span><span style="color: MediumSeaGreen;"><strong>={true}</strong></span>

</code></pre>{% endraw %}

### Valid

{% raw %}<pre class="language-js"><code class="language-js">&lt;<span class="token variable">input</span> <span class="token attr-name">disabled</span><span class="token operator">=</span><span class="token punctuation">{</span><span class="token boolean">false</span><span class="token punctuation">}</span> <span class="token operator">/</span>&gt;</code></pre>{% endraw %}
{% raw %}<pre class="language-js"><code class="language-js">&lt;<span class="token variable">input</span> <span class="token attr-name">disabled</span><span class="token operator">=</span><span class="token punctuation">{</span><span class="token string">&apos;&apos;</span><span class="token punctuation">}</span> <span class="token operator">/</span>&gt;</code></pre>{% endraw %}
{% raw %}<pre class="language-js"><code class="language-js">&lt;<span class="token variable">input</span> <span class="token attr-name">disabled</span><span class="token operator">=</span><span class="token punctuation">{</span><span class="token number">0</span><span class="token punctuation">}</span> <span class="token operator">/</span>&gt;</code></pre>{% endraw %}
{% raw %}<pre class="language-js"><code class="language-js">&lt;<span class="token variable">input</span> <span class="token attr-name">disabled</span><span class="token operator">=</span><span class="token punctuation">{</span><span class="token variable">undefined</span><span class="token punctuation">}</span> <span class="token operator">/</span>&gt;</code></pre>{% endraw %}
{% raw %}<pre class="language-js"><code class="language-js">&lt;<span class="token variable">input</span> <span class="token attr-name">disabled</span><span class="token operator">=</span><span class="token string">&apos;false&apos;</span> <span class="token operator">/</span>&gt;</code></pre>{% endraw %}
<!-- GENERATED:END(id:examples) -->
