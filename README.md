# SymbolJS

<!-- markdownlint-disable MD033 -->

Scripting with only symbols.

## Rules

* Runnable on latest Firefox
* Starting with only [Standard built-in objects][Web/JavaScript/Reference/Global_Objects] and [Global object][Glossary/Global_object]
* Never creating String object where use quotation symbols (0x22, 0x27, and 0x60)
* Coding with only these characters

<dl>
  <dt>0x20 - 0x21</dt>
  <dd>
    <code>&nbsp;</code><!-- ATTENSION: THIS IS NOT 0x20 BUT YOU CANNOT USE NBSP -->
    <code>!</code>
  </dd>
</dl>
<dl>
  <dt>0x22 - 0x26</dt>
  <dd>
    <code>"</code>
    <code>#</code>
    <code>$</code>
    <code>%</code>
    <code>&amp;</code>
  </dd>
</dl>
<dl>
  <dt>0x27 - 0x2f</dt>
  <dd>
    <code>'</code>
    <code>(</code>
    <code>)</code>
    <code>*</code>
    <code>+</code>
    <code>,</code>
    <code>-</code>
    <code>.</code>
    <code>/</code>
  </dd>
</dl>
<dl>
  <dt>0x3a - 0x40</dt>
  <dd>
    <code>:</code>
    <code>;</code>
    <code>&lt;</code>
    <code>=</code>
    <code>&gt;</code>
    <code>?</code>
    <code>@</code>
  </dd>
</dl>
<dl>
  <dt>0x5b - 0x60</dt>
  <dd>
    <code>[</code>
    <code>\</code>
    <code>]</code>
    <code>^</code>
    <code>_</code>
    <code>`</code>
  </dd>
</dl>
<dl>
  <dt>0x7b - 0x7e</dt>
  <dd>
    <code>{</code>
    <code>|</code>
    <code>}</code>
    <code>~</code>
  </dd>
</dl>

## Trying

Just 3 steps to begin SymbolJS!

1. Open `about:blank`
2. Press <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>K</kbd> (macOS: <kbd>⌘Command</kbd>+<kbd>⌥Option</kbd>+<kbd>K</kbd>)
3. Write your code and press <kbd>Enter</kbd> to run

## Contributing

* Pull Request Welcome!
* If you have a question or a trouble, make an issue to resolve it!
* Don't hesitate!

[Web/JavaScript/Reference/Global_Objects]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects
[Glossary/Global_object]: https://developer.mozilla.org/en-US/docs/Glossary/Global_object
