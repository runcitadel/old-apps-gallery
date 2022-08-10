# Citadel Apps Gallery

## Making Edits

- Open the `.fig` file in Figma
- Make sure you have the required fonts installed on your machineand they are usable by Figma
- Make your changes and export as 2x JPG
- Compress the exported result: `mogrify -strip -interlace Plane -sampling-factor 4:2:0 -define jpeg:dct-method=float -quality 85% *.jpg`
- Remember to commit the new `.fig` file which includes your edits
