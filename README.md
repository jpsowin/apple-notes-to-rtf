# Apple Notes → RTF

I was taking notes for a book in Apple Notes and writing it in Pages. All I wanted was to move the notes over, keep the bold and underlining, and use the font I’d already picked.

Apparently this was asking a lot.

So I made a little HTML file.

**[Use it here →](https://jpsowin.github.io/apple-notes-to-rtf/)**

It cleans up text copied from Apple Notes, keeps the emphasis and spacing, and exports an RTF using your chosen font and size.

## How to use it

1. Copy your text from Apple Notes and paste it into the left box.
2. Open **Font settings** and choose the font and size you use in Pages.
3. Check the preview and choose how you want the lists handled.
4. Click **Save for Pages (.rtf)**.
5. Open the downloaded file in TextEdit, select all, copy, and paste into Pages.

Yes, there’s a TextEdit step. Copying directly from the browser can make Pages choose a different font, which is part of the annoyance that led to this thing existing.

A few things to know:

- **Lowercase is on by default.** That’s how I wanted my notes. Turn it off if you want to keep your capitalization.
- **Tabs, no bullets** replaces bullet levels with tabs. You can also keep bullets or turn top-level items into paragraphs.
- **Indents, no bullets** is experimental. The exported list levels haven’t been fully verified with Pages’ Increase/Decrease Indent Level controls.
- The default font is **Adobe Jenson Pro, 14 pt**. Fonts need to be installed on your Mac, so choose one you have.
- This matches your chosen font and size. It doesn’t apply your document’s named Pages paragraph styles.

## Use it online or locally

[Use it on the internet](https://jpsowin.github.io/apple-notes-to-rtf/), or download `index.html` and open it on your computer. Same little tool either way.

Everything happens in your browser. Your note text is never stored or uploaded.

Made by [Josh Sowin](https://sowin.io).
