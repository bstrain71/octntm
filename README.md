# Demo of Automated Data Scraping from Message Text

The three files in this repository are:

1) BNM_export.xml: an xml file containing 39 Notice to Mariners (NTM) messages released by USCG Sector 5 between October 1 and October 19. These NTM messages were chosen to demonstrate the ease with which Message-formatted text can be parsed and tabulated.
2) NTM.ipynb: A Jupyter notebook with the code used to parse the NTMs and create the powerpoint presentation.
3) text.pptx: A power point that was automatically created using the NTM.ipynb file. This powerpoint file was never edited by a human and all information in it was automatically extracted from the BNM_export.xml file.

The purpose of this repository and these files is to demonstrate how easy it is to automate processes that are currently done by human staff. The final power point presentation can be made to fit existing templates and workflows - and can be updated at any periodicity without extra effort.

It is not necessary for the raw data to be in XML format. A folder of .txt, .doc, or .pdf files will also suffice.
