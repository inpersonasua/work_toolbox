# rename.wt.js
Renames documents in windchill

It simple script replaces Polish characters to Latin equivalents (like Ł -> L etc.) in Windchill rename page.
Paste content of the script in developer tools -> console in browser (tested on firefox).

# materials.py
Exports ProEngineer/Creo material files (.mtl) to Excell spreadsheet.
Find all materials in script directory and subdirectories.

# catalog_names.py
Finds numbers and corresponding parts/assy names in Machine Catalogs.

# windchill_batch_rename.py
Batch renames WTpart names based on prepared excel file:
first column: part number
second column: old name
third column: new name
fourth column: status (empty when part wasn't renamed, "OK" if part was renamed)

# split-speech.py
Looks for pauses in sound file and streches the pauses to give time for repeating previous pice of speech. The purpose of this script was to prepare sound file for pronunciation exercises (repeting speech) for foreign language practice. The pause duration is equal to previous piece of sound duration.
