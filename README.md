# My creative code site

Plain HTML and CSS. Nothing to install.

## Preview it
1. Open this folder in VS Code (File > Open Folder).
2. Install the "Live Server" extension (by Ritwick Dey).
3. Right-click `index.html` > "Open with Live Server".

## Add a log entry
1. Duplicate a file in `log/` and rename it with the date, like `2026-10-02.html`.
2. Edit the title, date, and text inside it.
3. In the main `index.html`, copy one `<li>` line, paste it at the top of the list,
   and point its link at your new file. The numbers update on their own.

## Add a project
1. Make a folder: `projects/your-project-name/` with an `index.html` inside.
2. Add an `<li>` for it at the top of the list in the main `index.html`, labeled Project.

## Folder map
    index.html        the index: every project and log entry, newest first
    style.css         the whole look of the site
    log/              one file per log entry
    projects/         one folder per piece
