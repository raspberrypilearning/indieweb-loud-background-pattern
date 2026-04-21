<h2 class="c-project-heading--task">Keep the text readable</h2>

You will add a tiny text panel so the cursed pattern stays the main event without swallowing the words.

Still in `style.css`, style the small note in the middle of the page.

<div class="c-project-code">

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 26
line_highlights: 26-46
---
.pattern-note {
  width: min(360px, 100%);
  padding: 22px;
  border: 5px solid #170f2c;
  border-radius: 20px;
  background: rgba(255, 255, 255, 0.9);
  box-shadow:
    0 0 0 6px #ffffff,
    0 16px 0 #170f2c;
  text-align: center;
}

h1 {
  margin: 0;
  font-size: clamp(2rem, 7vw, 3rem);
  line-height: 0.95;
  text-transform: uppercase;
}

p {
  margin: 14px 0 0;
  font-size: 1rem;
  line-height: 1.5;
}
--- /code ---

</div>

<h2 class="c-project-heading--task">Test</h2>

You should see a small readable note sitting on top of the gloriously too-much background.

<div class="c-project-output">
  <img src="images/step_3_output.png" alt="Observed project output after this step.">
</div>
