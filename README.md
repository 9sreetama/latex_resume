
This latex version of the resume is a modification with inclusion of Publication section and other sections more appropriate for a researcher.
The modifications have been implemented on the base version of Christophe Roger and that version is available on GitHub at https://github.com/darwiin/yaac-another-awesome-cv.

NOTE: The modification is inspired by the template of LianTze Lim (https://www.overleaf.com/latex/templates/a-customised-curve-cv/mvmbhkwsnmwv)

## How to use
- Include "\addbibresource{my_pub.bib}" in the main tex file
- Create a file called my_pub.bib and copy all your references in .bib format
- In the file "section_publications", ensure "\nocite{*}" is UNCOMMENTED. This is needed to ensure papers not being citing will still be displayed.
- If you just want everything in one list uncomment the line "\printbibliography[heading={none}]" and comment all the others
- For articles only uncomment "\printbibliography[heading=subbibliography,title={Journal Proceedings}, type=article]" and comment out the others.
- Similarly you have options for books only and journals only.
