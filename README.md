# info-rename-buffer
Rename Info buffers to match manuals

`info-rename-buffer-mode` is a global minor-mode that automatically
renames Info buffers to match their visiting manual.

That’s a useful feature when consulting several Info manuals
simultaneously, because it frees the user from the burden of renaming
Info buffers to descriptive names manually before visiting another
manual, thus avoiding accidentally overriding the currently visited
node in case the user tries to open a new Info buffer.
