<h2 class="c-project-heading--task">Make it repeat forever</h2>

Change the background so the same image repeats across the whole page instead of appearing only once.

Stay in `style.css` and change the `background-repeat` value inside the `body` rule.

<div class="c-project-code">

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 12
line_highlights: 15
---
  background-color: #19001d;
  background-image: url("leopard.gif");
  background-repeat: repeat;
  background-position: top left;
  background-size: 220px 220px;
--- /code ---

</div>

## Now run your code

You should now see the same giant leopard tile repeated across the whole page.

<div class="c-project-output">
  <img src="images/step_2_output.png" alt="Expected project output after step 2 showing the large leopard wallpaper tile repeated across the page.">
</div>
