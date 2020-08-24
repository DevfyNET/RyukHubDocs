# Reboot

## Headings and paragraphs

 All heading elements—e.g., `<h1>`—and `<p>` are reset to have their `margin-top` removed. Headings have `margin-bottom: .5rem` added and paragraphs `margin-bottom: 1rem` for easy spacing.

| Heading | Example |
| :--- | :--- |
| `<h1></h1>` | h1. Bootstrap heading |
| `<h2></h2>` | h2. Bootstrap heading |
| `<h3></h3>` | h3. Bootstrap heading |
| `<h4></h4>` | h4. Bootstrap heading |
| `<h5></h5>` | h5. Bootstrap heading |
| `<h6></h6>` | h6. Bootstrap heading |

## Lists

All lists—`<ul>`, `<ol>`, and `<dl>`—have their `margin-top` removed and a `margin-bottom: 1rem`. Nested lists have no `margin-bottom`.

1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa
4. Facilisis in pretium nisl aliquet
5. Nulla volutpat aliquam velit
6. Faucibus porta lacus fringilla vel
7. Aenean sit amet erat nunc
8. Eget porttitor lorem

* Lorem ipsum dolor sit amet
* Consectetur adipiscing elit
* Integer molestie lorem at massa
* Facilisis in pretium nisl aliquet
* Nulla volutpat aliquam velit
  * Phasellus iaculis neque
  * Purus sodales ultricies
  * Vestibulum laoreet porttitor sem
  * Ac tristique libero volutpat at
* Faucibus porta lacus fringilla vel
* Aenean sit amet erat nunc
* Eget porttitor lorem

For simpler styling, clear hierarchy, and better spacing, description lists have updated `margin`s. `<dd>`s reset `margin-left` to `0` and add `margin-bottom: .5rem`. `<dt>`s are **bolded**.

**Description lists**  
A description list is perfect for defining terms.

**Euismod**  
Vestibulum id ligula porta felis euismod semper eget lacinia odio sem.Donec id elit non mi porta gravida at eget metus.

**Malesuada porta**  
Etiam porta sem malesuada magna mollis euismod.

## Preformatted text

 The `<pre>` element is reset to remove its `margin-top` and use `rem` units for its `margin-bottom`.

```css
.example-element {
  margin-bottom: 1rem;
}
```

## Misc elements

### Address

 The `<address>` element is updated to reset the browser default `font-style` from `italic` to `normal`. `line-height` is also now inherited, and `margin-bottom: 1rem` has been added. `<address>`s are for presenting contact information for the nearest ancestor \(or an entire body of work\). Preserve formatting by ending lines with `<br>`.

**Twitter, Inc.**  
1355 Market St, Suite 900  
San Francisco, CA 94103  
P: \(123\) 456-7890 **Full Name**  
[first.last@example.com](mailto:first.last@example.com)

### Blockquote

 The default `margin` on blockquotes is `1em 40px`, so we reset that to `0 0 1rem` for something more consistent with other elements.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.  
Someone famous in _Source Title._

\_\_

