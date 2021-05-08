# webgen
- A tree based static website builder without any JS.
- Can be used as a main website or a sub module of any existing website because of the tree structure.
- Perfect for any blog based website which recursively has categories.
- Uses the structure of directories to generate a static website.
- Every directory must have an `index.md` markdown file. The end of the file should contain description of the subtrees if there are subdirectories.
- The directory names are allowed to have single quotes and spaces in them.

## Requirements
- `pandoc` must be installed. The python script invokes a shell command to convert markdown to html.
