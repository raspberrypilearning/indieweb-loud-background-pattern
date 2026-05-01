<h2 class="c-project-heading--task">Start the terrible tile</h2>

Add one wallpaper image to the page background so the profile skin starts with a single loud patch.

## Step 1
Run the code to see the unstyled page.

## Step 2
Open `style.css`. Add these lines inside the `body` rule so the browser uses `leopard.gif` as a background image.

<div class="c-project-code">

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 6
line_highlights: 14-17
---
body {
  margin: 0;
  min-height: 100vh;
  display: grid;
  place-items: center;
  padding: 24px;
  overflow: hidden;
  background-color: #19001d;
  background-image: url("leopard.gif");
  background-repeat: no-repeat;
  background-position: top left;
  background-size: 220px 220px;
  color: #26001b;
  font-family: Verdana, Geneva, sans-serif;
}
--- /code ---

</div>

## Now run your code

You should see one giant patch of leopard wallpaper in the top-left corner instead of a fully tiled page.

<div class="c-project-output">
  <img src="images/step_1_output.png" alt="Expected project output after step 1 showing one large leopard wallpaper tile in the corner of the page.">
</div>
