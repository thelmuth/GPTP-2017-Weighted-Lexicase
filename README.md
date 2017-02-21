# GPTP-2016 Proceedings Volume chapter prep

This repository includes all the files you will need for preparing your GPTP 2016 Proceedings Volume chapter—including a template you should edit to include your chapter's text—except for image and BibTeX files you will need to provide.

### Note

Updated thoroughly (and simplified, thanks to the folks at Springer Verlag) since the workshop occurred! Please take a moment to give it a try.

## Timeline

1. revised manuscripts due June 15, 2016
2. copy editing will be done while you're all busy at the Big Meeting
3. manuscripts will be returned to the author(s) as copy-editing is completed. Note this will involve _actual [copy editing](https://en.wikipedia.org/wiki/Copy_editing)_ and thus there may be important clarifications and improvements asked before the manuscript is complete.
4. all manuscript work should be complete (including changes made in response to copy editing) by August 15, 2016
5. yes, that said "August 15, 2016"
6. That means August 15, 2016 is the final deadline. We will be mean. More than a decade of experience informs our promise of meanness on this.
7. Chapters that have been completed satisfactorily by August 15, 2016 will be submitted to the publisher on September 1, 2016.

## Simple start

Just to make sure everything is set up correctly on your machine:

1. clone or download this repository; unzip it if necessary
2. navigate to the folder created, and then into `gptp2016-chapter`
3. open the file `author.tex` in your LaTeX editor of choice
4. render the document (all dependencies used by the example chapter, including images and references, are already here in this directory)
5. Take a moment to look over the document produced. It's loaded with helpful information for your own manuscript preparation!
6. Look over the documentation provided by Springer, which is stored in `documentation/authinst.pdf`. It's great!

OK, so now we both know your LaTeX installation is working! Now:

#### start fresh

Make a copy of the file `author.tex`, leaving it where it is for now

#### pick a useful filename

Rename the file to something more useful, like `yourname.tex` for example, or some other name that will help us know whose chapter it is.

#### pick a useful chapter name

at line 39, add the chapter title

#### pick a useful author name

at line 43, add the author names

#### pick a nice place to work

Edit the institutional affiliations appropriately. If you don't have an affiliation, that's OK, but _please_ include the email address of the corresponding author.

#### tell us what you're going to say

Edit the abstract to include a _succinct_ abstract of your work. "Succinct" means five or six sentences, 10–15 lines (rendered), max. If your abstract continues past the first page of the rendered manuscript, guess what? _It's not an abstract, it's a paper._

#### say it

Edit the section headings and the contents of the sections.

Probably you should also take out the example content from the example file. If you want. It's not too bad, but I don't recall anybody talking about it in the workshop, so maybe you'll want to.

#### pictures are fun!

Please be _very careful_ to read the comments and example code regarding figures. Don't add new packages to make fancy figures unless you contact the editors (Bill Tozier, probably) first. Don't stretch the figures to be in weird places or weird sizes. Don't try to jam too many figures into one chapter. Don't use color. Don't use pixelated images. Don't don't don't.

Make them nice please. _Then_ pictures are fun.

#### citations

In your text, use `\cite{<label>}` for every citation, and make sure every `<label>` is unique in your document.

#### but wait there's more!

Actually, hang on... no there isn't. Please don't use the `appendix` shown in the example template.

#### giving credit where you want to

Traditionally we've relied on Bill Langdon's [GP Bibliography](http://www.cs.bham.ac.uk/~wbl/biblio/). Please feel free to include items you want from that. But but _but_ you must also include any other references not present in that eminent file in your own references file. Edit (or generate using you favorite bibliographic management software) the file `referenc.tex` so that it has _your chapter's references in it_.

Editing bibliographic entries is complicated, but the documentation included in this repository is actually quite good. If you glance at the PDF file generated when you rendered `author.tex` (the original template you copied) you'll see all kinds of amazing useful helpful stuff near the end about references.

You can choose whichever bibliographic standards you like, but I think probably we will use the ones given in the first or second example blocks of the template's bibliography (references 1-5 and 6-10).

If you have trouble rendering the bibliography, please don't spend too much time fixing it to be pretty. We'll do that. Instead

1. get all the references you use in your chapter into `referenc.tex`
2. don't include any references there that aren't in your chapter
3. make sure all the bibliographic info is present (full title, full author list, etc) and we will fiddle with the styles later

#### make it right

Please spell check. We will correct obvious misspellings without informing you, but would rather not have to do that.

Please write clearly. We will flag obscure or incorrect grammar if it appears in your manuscript and return it to you, and we'd _really_ rather not do that.

Please refer to the pertinent literature in your contribution. Err on the side of extra references. Imagine somebody who is (1) interested but (2) a complete novice is reading your chapter.

Include all figures as encapsulated postscript `.eps` or PDF files `.pdf` _in the directory with your chapter, at the same level as your text_. Don't put them in a sub-directory, please. Just make sure the files are named reasonably and can be identified if they all get mixed up.

#### make it pretty

We'll do that. But these will certainly help:

Don't use color.

Don't use new or extra fonts.

Don't play bounding box games or check for hbox overflow errors.

Don't hyphenate things unless you really know they need to be hyphenated.

Don't have too many figures.

If you absolutely must must must have a full-page figure, please...

#### make it fit

Sixteen pages, rendered using this template. Including figures and bibliography.

#### ask questions

Please discuss your manuscript early and often on the Slack channel assigned to it.

#### get it done

Submit revised manuscripts by **15 June, 2016**. To submit your manuscript:

1. rename the folder `gptp2016-chapter` to `gptp2016-chapter-YOURNAMEHERE`
2. zip the entire folder, and all contents
3. upload this zip file to the Slack channel assigned to it (just drag it onto the channel input box!); if for some reason you're unable to upload via slack, then email it to Bill Tozier as an attachment with an explanation (and then he will help you figure out how to upload it correctly to the Slack channel, because that's probably what you wanted to do anyway)
