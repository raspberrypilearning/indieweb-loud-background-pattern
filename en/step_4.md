<h2 class="c-project-heading--task">Style the heading and text</h2>

You will finish the page by styling the `h1` and `p` so the tiny note still looks deliberate.

Still in `style.css`, add the `h1` and `p` rules underneath `.pattern-note`.

<div class="c-project-tip">

<h3>Tip</h3>

<p>After the text looks right, try a few small changes to see how much attitude you can add without making it unreadable.</p>

<p>You could make the heading louder by changing `font-size` to `clamp(2.4rem, 8vw, 3.6rem)`.</p>

<p>You could make it feel more poster-like by adding `letter-spacing: 0.08em` to the `h1` rule.</p>

<p>You could make the paragraph calmer by changing `line-height` to `1.7` or the `margin` to `18px 0 0`.</p>

</div>

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

<div class="c-project-output">
  <img src="images/step_4_output.png" alt="Observed project output after this step.">
</div>
