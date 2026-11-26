# Branding

The website's logo, icon and name. To brand the Lab Manager for your lab:

1. Put your files here (replace the Pestilli Lab ones):
   - `logo-light.svg` (or `.png`, `.jpg`, `.webp`): the logo on light backgrounds, shown top left (about 26 px tall,
     wide is fine). A single `logo.svg` also works.
   - `logo-dark.*` (optional): the version for dark mode. Without one, the light logo is used.
   - `favicon.svg` (or `.png`, `.ico`, optional): the browser tab icon.
2. Set the lab's name, PI, home page and joining-guide link in `lab.json` (`name`, `pi`, `home`, `guide`).
3. Run `python scripts/seed_department.py --website-only` (it writes `dashboard/src/lab.js`) and commit.

The next website deploy uses them. Everything in this folder is published with the website, so keep only public
files here.
