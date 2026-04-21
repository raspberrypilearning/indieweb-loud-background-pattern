<h2 class="c-project-heading--task">Add the note box</h2>

You will add a small panel so the background can stay wild without swallowing the page text.

Still in `style.css`, add the `.pattern-note` rule in the middle of the page.

<div class="c-project-tip">

<h3>Tip</h3>

<p>Once this works, try changing the box style to get a different mood.</p>

<p>You could make the corners sharper by lowering `border-radius` to `8px`.</p>

<p>You could make the panel feel heavier by changing the border to `8px solid #170f2c`.</p>

<p>You could make it feel more ghostly by changing the background to `rgba(255, 255, 255, 0.75)`.</p>

</div>

<div class="c-project-code">

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 28
line_highlights: 30-40
---
}

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
--- /code ---

</div>

<h2 class="c-project-heading--task">Test</h2>

You should now see a small readable box sitting on top of the gloriously too-much background.

<div class="c-project-output">
  <img src="images/step_3_output.png" alt="Observed project output after this step.">
</div>
