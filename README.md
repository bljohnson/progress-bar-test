TESTING PROGRESS BAR BUILD

Installation Requirements:

sudo gem update --system

sudo gem install -n /usr/local/bin compass

If project already exists, cd into project, then: compass install compass

If new project, then: compass create project-name-here

Source the links provided by the terminal ouput into your html file.

Add a new .scss file in the sass folder. Put your sass there.

sass --watch sass/file-name-here.scss (This autocompiles your scss into a css file.)

Source the css file (from sass folder) into your html file.
