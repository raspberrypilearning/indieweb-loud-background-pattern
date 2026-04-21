<h2 class="c-project-heading--task">Style the heading and text</h2>

You will finish the page by styling the `h1` and `p` so the tiny note still looks deliberate.

Still in `style.css`, add the `h1` and `p` rules underneath `.pattern-note`.

<div class="c-project-code">

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 40
line_highlights: 42-53
---
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

You should now see a small readable note sitting on top of the gloriously too-much background.

<div class="c-project-tip">

<h3>Tip</h3>

<p>`font-size` changes how shouty or restrained the heading feels.</p>

<p>`letter-spacing` spreads the heading letters out and can make them feel more poster-like.</p>

<p>`margin` changes the gap between the heading and the paragraph.</p>

<p>`line-height` changes whether the paragraph feels tight and cramped or loose and open.</p>

</div>


<div class="c-project-output">
  <img src="images/step_4_output.png" alt="Observed project output after this step.">
</div>
