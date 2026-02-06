# Plugins

## Custom Attachment Location

[See Plugin Repo Here.](https://github.com/mnaoumov/obsidian-custom-attachment-location) This puts any file attachments (mostly images) within the 'Meta' folder and automatically renames them for standardization.

**Location for New Attachments:** The attachments folder follows a duplicated path tree.
```
Meta/Attachments/${noteFolderPath}
```

**Generated Attachment File Name:** Gives attachments mention of name it is in, a date stamp, and a random four digits. Attachment rename mode is set to 'All'.
```
file-${noteFileName:{case:'lower',slugify:true}}-${date:{momentJsFormat:'YYYYMMDD'}}-${random:{letters:false,length:4}}
```

As an example: following this format, a file could be named `file-meta-20260206-0992.png`.

## Iconic

[See Plugin Repo Here.](https://github.com/gfxholo/iconic) Allows for extensive rule creating for notes and folders.

<img width="1744" height="1744" alt="20260206 10 33 00@2x" src="https://github.com/user-attachments/assets/963920a2-da95-45f3-b8d4-41526b2a1ccf" />

The static icon's I've used for the main folders and subfolders are:
- **Catalogue** - `layout list`
  - Development - `code 2`
  - Music - `disc album`
  - Reading - `book open`
  - TV & Movies - `tv`
  - Tags - `tags`
  - Video Essays - `minimal play`
- **Fleeting** - `feather`
- **Meta** - `square dashed mouse pointer`
  - Attachments - `paperclip`
  - Templates - `construction`
- **Organized** - `library square`
  - Software - `git graph`
  - University - `graduation cap`
  - Writing - `pen tool`
- **Permanent** - `archive`

The file rules I've created are:
- **All Bases** - `database`, when extention is 'base'.
- **Catalogued Files** - `shapes`, when folder tree starts with `Catalogue/`.
- **Fleeting Files** - `notepad text dashed`, when folder tree starts with `Fleeting/`.
- **Organized Files** - `notebook tabs`, when folder tree starts with `Organized/`.
- **Permanent Files** - `file text`, when folder tree starts with `Permanent/`.

And finally, the folder rules:
- **Fleeting Subfolder** - `calendar range`, when folder tree is `Fleeting/`.
- **Catalogued Folder as Item** - `shapes`, when folder tree matches RegEx `Catalogue\/\w+\/.*`.
- **Organized Folder as Book** - `book text`, when folder tree matches RegEx `Organized\/\w+\/.*`.

## Linter

[See Plugin Repo Here.](https://github.com/platers/obsidian-linter) Useful for quickly standardizing and cleaning up notes without any hassle.

You can find my full configuration file [here](https://github.com/uthoffcyra/kitsuneji-obsidian/blob/main/configuration/obsidian-linter/data.json).

## Other 

- [Furigana](https://github.com/uonr/obsidian-furigana).
- [Obsifetch](https://github.com/tabibyte/obsifetch)
- [Smart Typography](https://github.com/mgmeyers/obsidian-smart-typography)
- [Style Settings](https://github.com/mgmeyers/obsidian-style-settings)
- [Tag Wrangler](https://github.com/pjeby/tag-wrangler)
