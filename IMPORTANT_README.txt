##### GitHub Collaboration Rules #####

File Size
--------------------------------------------------------
Artists must keep each uploaded file under 100 MB.
Files larger than 100 MB may be rejected by GitHub.

Declare Editing Range
-------------------------------------------------------
Before editing any file, asset, document, or project content, declare your working range in Discord.

File Path Changes
-------------------------------------------------------
Any file/folder move, rename, or deletion must be announced with @everyone in advance.
Do not change file paths until all active editors have pushed their current work.

#PS：Git Behavior
# Git only tracks changes made to files. An unchanged older local file will not normally overwrite someone else's newer version. File path changes are different. When a file is moved, renamed, or deleted, Git may record the operation as the removal of the old path and the addition of the file at a new path. 
# If another editor is still working on the file under the old path, their later push may conflict with the path change or recreate files in locations that have already been changed.

Respect Editing Boundaries
------------------------------------------------------
Stay within your declared working range.
Do not edit files or areas currently declared by someone else until they confirm their work is finished and pushed.

Ignored Files
-----------------------------------------------------
Unreal-generated files such as Autosaves, Logs, Intermediate, and DerivedDataCache should be ignored through .gitignore.
.gitignore setup is currently in progress.