# Examples

## `iframe-srcdoc.html`

This self-contained dummy page contains an iframe whose complete placeholder HTML
document is stored in a `srcdoc` attribute. It has no external resources or real-world
content.

Open the file in Chromium and in Obsidian with **Balance Mode** or **High Restricted
Mode**. In both cases, the heading "EMBEDDED CONTENT" and the dummy text beneath it
should be visible inside the iframe. The plugin keeps the `srcdoc` document but replaces the
iframe's saved sandbox permissions with an empty sandbox.

**Text Mode** intentionally removes iframes, so this example is expected to show only
the outer page in that mode.
