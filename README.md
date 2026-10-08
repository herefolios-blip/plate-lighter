# Plate Lighter

A browser tool that suggests a lighting setup for an actor on a green screen, so they sit more naturally in a background plate and need less correction in post.

Load a plate, describe your studio and kit, and the app proposes where each light goes, plus its colour temperature, tint or colour, intensity, height, distance, angle and modifier. It checks the plan against your room, stands, power and cameras.

**Status:** working prototype. The plate analysis is a simple brightness and colour heuristic, not AI, so treat the result as a starting point and adjust on set. Light output figures are estimates: confirm them against manufacturer spec sheets.

## Using it
- Open the page, then use the **Plate** tab to load an image. Optionally press *Mark light sources* and click the window, lamp or neon in the image.
- Set up your room, green screen shape, actor pose and cameras in the **Studio** tab, and your lights in the **Kit** tab.
- Click a light on the plan or in the right column to adjust it. Use **3D view** to check what each camera sees.
- **File** menu: save in this browser, export or import a project file to share, or export a plan image (PNG).

Saved projects live in each person's own browser. To share one, use *Export file* and send it to a colleague, who can use *Import file*.

## Hosting (GitHub Pages)
1. Create a repository and upload `index.html` (and this README).
2. Go to **Settings, Pages**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then save.
3. After a minute or two the site is live at `https://YOUR-USERNAME.github.io/REPO-NAME/`.

To update the app later, upload a new `index.html` over the old one.

The app is a single file with no build step and no server. It loads fonts from Google Fonts and needs nothing else.
