# Research Framework (working title)

A single-page tool for researching businesses and real-life wonders through the lens of human ingenuity. It has three parts:

1. **The Gate.** Five scored tests decide whether a subject deserves 4 to 8 weeks of research. Ingenuity and Evidence are knockouts.
2. **The Canvas.** Four lenses (Engineering & Science, Economy, People, Environment), each answered through Constraint, Leap and Consequence.
3. **The Lesson.** Who gained, who paid, what was deferred, where the lenses collide, and one transferable principle. An episode plan is generated from the lenses you rate Strong.

The Library tab compares every subject you have researched, so patterns across subjects become visible.

## Host it on GitHub Pages (free)

1. Create a new repository on GitHub (public, so Pages can serve it on a free account).
2. Upload `index.html` and `README.md` to the repository root.
3. Go to **Settings → Pages**. Under "Build and deployment", choose **Deploy from a branch**, select the `main` branch and the `/ (root)` folder, then save.
4. After a minute or two the page is live at `https://<your-username>.github.io/<repository-name>/`.

There is nothing to install or build. The page is one self-contained file.

## Where your data lives

Work saves automatically in the browser you use, on that device only. It does not sync and is not visible to anyone else, even though the page is public. To keep, back up or share a subject, use **Download JSON** (and **Import JSON** to load it elsewhere) or **Download .md** for a readable copy.

## Tuning the gate

Near the top of the script in `index.html` is a `CONFIG` block:

- `goAt`: score out of 10 needed for "Go" (default 8)
- `revisitAt`: score needed for "Revisit" (default 6)
- `knockouts`: tests that stop a subject if scored too low (default Ingenuity and Evidence)
- `knockoutMin`: the minimum score on a knockout test (default 1)

## Evidence standard

Anchor every key claim in a primary source or two independent credible ones. Make every number traceable. Steel-man the strongest critic. Use explainers for orientation only, never as the sole source.

The built-in Panama Canal example is illustrative and unverified. Treat it as a demonstration of the canvas, not as research.
