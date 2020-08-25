# Code

### Inline code <a id="inline-code"></a>

Wrap inline snippets of code with `<code>`. Be sure to escape HTML angle brackets.

 For example, `<section>` should be wrapped as inline.

```markup
For example, <code>&lt;section&gt;</code> should be wrapped as inline.
```

### Code blocks

Use `<pre>`s for multiple lines of code. Once again, be sure to escape any angle brackets in the code for proper rendering. You may optionally add the `.pre-scrollable` class, which will set a max-height of 340px and provide a y-axis scrollbar.

{% hint style="info" %}
&lt;p&gt;Sample text here...&lt;/p&gt;  
&lt;p&gt;And another line of sample text here....&lt;/p&gt;
{% endhint %}

```markup
<pre><code>&lt;p&gt;Sample text here...&lt;/p&gt;
&lt;p&gt;And another line of sample text here...&lt;/p&gt;
</code></pre>
```

### Variables

 For indicating variables use the `<var>` tag.

> y = mx + b

```markup
<var>y</var> = <var>m</var><var>x</var> + <var>b</var>
```

