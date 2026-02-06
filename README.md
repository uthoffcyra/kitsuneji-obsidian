# kitsuneji

This is my current organization system for notetaking in [Obsidian](https://obsidian.md/).

<img width="2934" height="1950" alt="20260206 09 40 56@2x" src="https://github.com/user-attachments/assets/7999d64e-dc03-4ca8-ac85-1504bfac1674" />

## Theme & Style

I've been using the ['Minimal'](https://github.com/kepano/obsidian-minimal) theme, as it is fairly mature, quite popular, and doesn't have as many issues in styling as I've encountered on other themes. Further, the actual simplistic nature of the theme lends itself well to notes of all kinds.

Using the **Style Settings** plugin, I've only deemed to change one setting for the theme:
```json
{
  "minimal-style@@image-muted": 1
}
```

As for my own tweaks and styling, I've created another CSS Snippet that adds some smaller tweaks and functionality to my vault. I also added compatability with the aforementioned **Style Settings** plugin, so changing or disabling anything I've done should be quite simple. [You can find the full CSS snippet here.](https://github.com/uthoffcyra/kitsuneji-obsidian/blob/main/kitsuneji.css)

A number of [custom CSS classes](https://github.com/uthoffcyra/kitsuneji-obsidian/blob/main/CSSCLASSES.md) are also implemented as a part of this snippet.

## Architecture

This vault is organized around the existence of five top-level folders, and two vital plugins that make ease of use possible.

- **Catalogue** - Used for notes that act like objects. For example, having a note to represent a book, an idea, a place, or tag. Notes are pushed into second-level subfolders for further categorization. Folders past the second level are considered to be objects themselves.
- **Fleeting** - Used for notes whose usefulness is not expected to be long-term. Think of plans, checklists, memos, etc. Within this directory, second-level folders for each month are also created, which aligns to the month the note was _first_ written.
- **Meta** - Used for storing notes and files necessary to the production of the vault. This includes storing templates and attachments.
- **Organized** - Used for projects, personal writing, and class notes. Notes are pushed into second-level subfolders for further categorization.
- **Permanent** - Used for notes that are expected to be used far into the future, and are to be updated more stringently.

For quick access, frequently opened notes are to be tagged with the **Bookmarks** plugin.

The **Bases** plugin further streamlines note access through tagging, especially for notes found in the ‘Catalogue’ and ‘Organized’ top-level folders.

## Used Plugins

Aside from Bases and Boomarks, the built-in plugins I use are: Backlinks, Command Palette, File Recovery, Files, Graph View, Outgoing Links, Outline, Page Preview, Quick Switcher, Search, Tags View, and Word Count.

I've also used a number of community plugins, which you can see my configurations for at [PLUGINS.md](https://github.com/uthoffcyra/kitsuneji-obsidian/blob/main/PLUGINS.md).
