<h2 class="c-project-heading--task">Make the pattern worse</h2>

You will stack more repeated shapes on top of the stripes to make the background noisier.

Stay in `style.css` and add a dot layer plus another set of repeating lines.

<div class="c-project-code">

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 1
line_highlights: 13-24
---
body {
  margin: 0;
  min-height: 100vh;
  display: grid;
  place-items: center;
  padding: 24px;
  font-family: "Trebuchet MS", Verdana, sans-serif;
  color: #170f2c;
  background-color: #ffe45e;
  background-image:
    radial-gradient(circle, #ff47b5 0 18px, transparent 19px),
    repeating-linear-gradient(45deg, #171717 0 14px, #ffe45e 14px 28px),
    repeating-linear-gradient(-45deg, rgba(0, 225, 255, 0.55) 0 16px, transparent 16px 32px);
  background-size: 120px 120px, auto, auto;
}
--- /code ---

</div>

<h2 class="c-project-heading--task">Test</h2>

The background should now feel much louder, with repeated dots and clashing lines.

<div class="c-project-output">
  <img src="images/step_2_output.png" alt="Observed project output after this step.">
</div>
