<h2 class="c-project-heading--task">Start the background tiles</h2>

Add the wallpaper container and the first row of provided pattern images inside `<body>`.

<h2 class="c-project-heading--explainer">Make this change</h2>

Open `index.html`. The starter file has an empty `<body>`, so add the `wallpaper` `<div>` and one `wallpaper-row` inside it.

<div class="c-project-tip">

<h3>Tip</h3>

<p>These images are only decorative, so each `<img>` uses `alt=""`.</p>

<p>The provided files live next to `index.html`, so you can use filenames like `maze.gif` and `leopard.gif` directly.</p>

</div>

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 1
line_highlights: 9-16
---
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>WALLPAPER_DO-NOT-STARE.gif</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <div class="wallpaper" aria-hidden="true">
      <div class="wallpaper-row">
        <img src="maze.gif" alt="">
        <img src="leopard.gif" alt="">
        <img src="maze.gif" alt="">
        <img src="leopard.gif" alt="">
      </div>
    </div>
  </body>
</html>
--- /code ---

</div>

## Now run your code

You should see one row of loud pattern tiles on the page background.

<div class="c-project-output">
  <img src="images/step_1_output.png" alt="Expected project output after step 1 showing the first row of decorative pattern images on the background.">
</div>
