# mdbibexport
mdbibexport.pl extracts the cited references of a Pandoc markdown document and writes a bibtex database for this document. The citations are expected in a format [@key1], [@key2; @key3, p.34] etc. The keys between square brackets and starting with an @ symbol are extracted from the markdown file and writen into an auxiliary file, which is used by BibTool to find the references in the bibtex (.bib) data base and write them into a new file.
## Requirements
Perl <https://www.perl.org/> and BibTool <http://gerd-neugebauer.de/software/TeX/BibTool/en/> have to be installed on the system. Version 5.25 of Perl and version 2.65 of BibTool have been tested with this script.
## License
General Public License (GPL), version 3.0 <https://www.gnu.org/licenses/gpl-3.0.html>.
## Release version
0.10.
## Release date
2016/10/31.
## Author
Dr. Robert Winkler.
## Contact
robert.winkler@bioprocess.org, robert.winkler@cinvestav.mx.
