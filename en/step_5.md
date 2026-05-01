<h2 class="c-project-heading--task">Challenge: corrupt the colours even more</h2>

Mess with the colours in the CSS classes so the warning note feels even more cursed and personal.

Open `style.css` and change the colour values inside `.pattern-note`, `.eyebrow`, and `.status`. Try swapping the panel background, the eyebrow background, the status background, the border colours, or the `text-shadow` colour on `h1`.

<div class="c-project-code">

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 18
line_highlights: 24-26,34,47,54
---
.pattern-note {
  position: relative;
  z-index: 1;
  width: min(34rem, calc(100vw - 48px));
  padding: 24px;
  border: 5px solid #26001b;
  border-radius: 24px;
  background:
    linear-gradient(rgba(255, 255, 255, 0.35), rgba(255, 255, 255, 0)),
    #ffd8f2;
  box-shadow:
    0 14px 0 #170011,
    0 28px 34px rgba(0, 0, 0, 0.42);
}

.eyebrow {
  margin: 0;
  display: inline-block;
  padding: 6px 10px;
  border: 2px solid #26001b;
  background: rgba(255, 255, 255, 0.52);
  box-shadow: 4px 4px 0 #170011;
  font-size: 0.8rem;
  font-weight: 900;
  text-transform: uppercase;
  letter-spacing: 0.09em;
}

h1 {
  margin: 12px 0 0;
  font-family: Impact, Haettenschweiler, "Arial Narrow Bold", sans-serif;
  font-size: clamp(2.5rem, 9vw, 4rem);
  line-height: 0.94;
  letter-spacing: 0.04em;
  overflow-wrap: anywhere;
  text-shadow: 3px 3px 0 #fff17a;
}

.status {
  display: inline-block;
  margin: 12px 0 0;
  padding: 4px 10px;
  border: 2px dashed #26001b;
  border-radius: 999px;
  background: #7eeeff;
  font-size: 0.95rem;
  font-weight: 700;
  transform: rotate(1deg);
}
--- /code ---

</div>

<div class="c-project-tip">

<h3>Tip</h3>

<p>Try making the note look more sugary, more radioactive, or more fake-dangerous.</p>

<p>Clashing colours usually look better here than neat matching ones.</p>

<p><a href="https://www.google.com/search?q=web+colour+picker" target="_blank" rel="noopener noreferrer">Open the Google web colour picker in a new tab</a> if you want help choosing colours.</p>

</div>

## Now run your code

If you change the colours in these classes, the warning note should feel much more like your own horrible profile skin.

<div class="c-project-output">
  <img src="images/step_5_output.png" alt="Expected project output after step 5 showing one possible version of the warning note with loud customised colours.">
</div>
