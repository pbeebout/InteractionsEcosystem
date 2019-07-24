# InteractionsEcosystem

Teaching about Natural Selection

Website at https://pbeebout.github.io/InteractionsEcosystem/

Work by Polly BeeBout, helped by Brian O'Meara.

To make changes:

Open Terminal.app (in Applications/Utilities)
In terminal, type the following (after each terminal command, hit return)

`cd ~/Desktop/InteractionsEcosystem`

Then, to get any changes

`git pull`

Then you can edit the files (names end in *.Rmd). This is a format called RMarkdown.

When you're done editing, in Terminal:

`Rscript -e "rmarkdown::render_site()"`

Which will create updated versions of pages.

After making changes, to add new files:

`git add .`

then

`git commit -m'updated site' -a`

To save the changes and

`git push`

to put the changes on github. The new [site](https://pbeebout.github.io/InteractionsEcosystem/) will update in a few minutes.
