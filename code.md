# Code

### Inline code <a id="inline-code"></a>

Wrap inline snippets of code with `<code>`. Be sure to escape HTML angle brackets.

 For example, `<section>` should be wrapped as inline.

```markup
For example, <code>&lt;section&gt;</code> should be wrapped as inline.
```

### Code blocks

Use `<pre>`s for multiple lines of code. Once again, be sure to escape any angle brackets in the code for proper rendering. You may optionally add the `.pre-scrollable` class, which will set a max-height of 340px and provide a y-axis scrollbar.

> &lt;p&gt;Sample text here...&lt;/p&gt;  
> &lt;p&gt;And another line of sample text here....&lt;/p&gt;

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

### User input

 Use the `<kbd>` to indicate input that is typically entered via keyboard.

> To switch directories, type `cd` followed by the name of the directory. To edit settings, press `ctrl + ,`

```markup
To switch directories, type <kbd>cd</kbd> followed by the name of the directory.<br>
To edit settings, press <kbd><kbd>ctrl</kbd> + <kbd>,</kbd></kbd>
```

### Sample output <a id="sample-output"></a>

 For indicating sample output from a program use the `<samp>` tag.

> _This text is meant to be treated as sample output from a computer program._

```text
<samp>This text is meant to be treated as sample output from a computer program.</samp>
```

