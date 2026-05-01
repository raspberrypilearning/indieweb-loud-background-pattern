<h2 class="c-project-heading--task">Add the warning note header</h2>

Add the visible note panel on top of the wallpaper so the page looks like a dramatic profile warning instead of just endless leopard print.

<h2 class="c-project-heading--explainer">Make this change</h2>

Go back to `index.html` and put this `<main class="pattern-note">` section inside `<body>`.

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 9
line_highlights: 10-13
---
    <main class="pattern-note">
      <p class="eyebrow">Recovered profile skin // tiled at 2:04am</p>
      <h1>WALLPAPER_DO-NOT-STARE.gif</h1>
      <p class="status">mood: browser overheating</p>
    </main>
  </body>
--- /code ---

</div>

## Now run your code

You should now see the warning note header centered on top of the tightly tiled wallpaper.

<div class="c-project-output">
  <img src="images/step_4_output.png" alt="Expected project output after step 4 showing the warning note header centered over the tight tiled wallpaper.">
</div>
