<h2 class="c-project-heading--task">Add the first loud stripes</h2>

You will turn the plain page into a repeating striped background.

Open `style.css` and add the body styles that centre the page and paint big diagonal stripes behind it.

<div class="c-project-tip">

<p><strong>Tip:</strong> If you want to experiment after this works, try swapping the `background-image` line for a different repeating pattern.</p>

<p>You could try vertical stripes with `repeating-linear-gradient(90deg, #171717 0 14px, #ffe45e 14px 28px)`.</p>

<p>You could try horizontal stripes with `repeating-linear-gradient(0deg, #171717 0 14px, #ffe45e 14px 28px)`.</p>

<p>You could try loud spotty rings with `repeating-radial-gradient(circle, #171717 0 10px, #ffe45e 10px 22px)`.</p>

</div>

<div class="c-project-code">

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 1
line_highlights: 1-19
---
/* Start with one loud striped layer on the page background. */
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  min-height: 100vh;
  display: grid;
  place-items: center;
  padding: 24px;
  font-family: "Trebuchet MS", Verdana, sans-serif;
  color: #170f2c;
  background-color: #ffe45e;
  background-image: repeating-linear-gradient(
    45deg,
    #171717 0 14px,
    #ffe45e 14px 28px
  );
}
--- /code ---

</div>

<h2 class="c-project-heading--task">Test</h2>

You should see the page sitting on top of big repeating diagonal stripes.

<div class="c-project-output">
  <img src="images/step_1_output.png" alt="Observed project output after this step.">
</div>
