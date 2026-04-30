<h2 class="c-project-heading--task">Add the warning note header</h2>

Add the visible note panel on top of the wallpaper so the page looks like a dramatic profile warning instead of loose pattern tiles.

<h2 class="c-project-heading--explainer">Make this change</h2>

Stay in `index.html` and put this `<main class="pattern-note">` section underneath the `wallpaper` `<div>`.

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 29
line_highlights: 31-35
---
    </div>

    <main class="pattern-note">
      <p class="eyebrow">Recovered profile skin // tiled at 2:04am</p>
      <h1>WALLPAPER_DO-NOT-STARE.gif</h1>
      <p class="status">mood: browser overheating</p>
    </main>
  </body>
--- /code ---

</div>

## Now run your code

You should now see the warning note header centered on top of the tiled pattern background.

<div class="c-project-output">
  <img src="images/step_4_output.png" alt="Expected project output after step 4 showing the warning note header centered over the tiled pattern wallpaper.">
</div>
