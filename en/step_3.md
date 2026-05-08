<h2 class="c-project-heading--task">Shrink it into chaos</h2>

Make the repeated tile smaller so the wallpaper turns into a tight old-school mess.

Stay in `style.css` and change the `background-size` value inside the `body` rule.

<div class="c-project-code">

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 12
line_highlights: 13
---
  background-color: #19001d;
  background-image: url("leopard.gif");
  background-repeat: repeat;
  background-position: top left;
  background-size: 100px 100px;
--- /code ---

</div>

## Now run your code

You should now see a much tighter, nastier wallpaper pattern taking over the whole page.

<div class="c-project-output">
  <img src="images/step_3_output.png" alt="Expected project output after step 3 showing a tight repeating leopard wallpaper across the page.">
</div>
