# no-mans-sky
Repository for my No Man's Sky travels. I play under the usernames "sio" (Nintendo Switch) or "tatsutron" (PlayStation).

Feel free to fork this repository and use it as a way to record your own travel! This data is designed to be compatible with No Man's Sky Glyphs (https://glyphs.had.sh/). Some changes have been made to accommodate my personal preferences:
- no civilization field
- added a field for guild envoy
- added links to images stored in folders
- added space to document detailed info about planets and moons.

Have questions or want to give me feedback? Send me a message here or on Discord. You can find me at sio3f3a.

## Structure

This database is designed to be used with Obsidian.md, but all of the files are YAML / Markdown, so they will work with any text editor.

Each system has its own file, with all of the metadata fields that could be associated with that system. System files will also generally include links to images captured for that system, each stored in its appropriate folder:
- Galaxy Maps: Captured from the Galaxy Map screen, showing system information and nearby systems.
- Planet Maps: Captured from the Discoveries screen, showing names of the planets in that system. These may be updated as I go back and do more detailed explorations. 
- Images: General images, labeled with the system name, planet name (if applicable), and subject of the photo. (I generally take images without portal codes included.)

Systems.md is an Obsidian Base that shows all of the items in my database in a table view. 
- Systems View shows all items
- Research View shows items that have not been uploaded to No Man's Sky Glyphs (https://glyphs.had.sh/)

Folders: 
- Items in the root folder are systems that I have a record of visiting, but that I haven't documented yet. Generally, these files will not include metadata fields for links to the image files, since those are added later.
- Galaxy Maps, Images, Planet Maps: see description above.
- Systems: items that are complete and have been posted to to NMS Glyphs.
- templates: the template for the system files
- Upload to Glyphs: items that are complete but have not been posted to NMS Glyphs

### Plugins
I've tried to limit this to native Obsidian functions, but there are a few plugins that I needed for quality-of-life:
- Auto Template Trigger (automatically opens the system template when I open a new tab)
- Git (keeps an automatic backup of the system to Github)