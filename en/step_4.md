<h2 class="c-project-heading--task">Add the warning note</h2>

Add the visible note panel and its warning text on top of the wallpaper so the page looks like a dramatic profile warning instead of just endless leopard print.

<h2 class="c-project-heading--explainer">Make this change</h2>

Go back to `index.html` and put this full `<main class="pattern-note">` section inside `<body>`.

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 8
line_highlights: 9-14
---
  <body>
    <main class="pattern-note">
      <p class="eyebrow">Recovered profile skin // tiled at 2:04am</p>
      <h1>WALLPAPER_DO-NOT-STARE.gif</h1>
      <p class="status">mood: browser overheating</p>
      <p>This wallpaper was allegedly banned from three fan forums and one school library computer.</p>
    </main>
  </body>
--- /code ---

</div>

## Now run your code

You should now see the full warning note centered on top of the tightly tiled wallpaper.

<div class="c-project-output">
  <img src="images/step_4_output.png" alt="Expected project output after step 4 showing the full warning note centered over the tight tiled wallpaper.">
</div>
