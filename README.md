# NSHWEDatabaseMining

_Last update: 2023.11.12_

This repository contains the scripts and machine learning programming performed on approximately 8000 files originating in the Nationalsozialismus, Holocaust, Widerstand und Exil 1933-1945 (NSHWE) De Gruyter Database. The primary topics are: the speeches and writings of Adolf Hitler, the Joseph Goebbels diaries, and the Meldungen aus dem Reich and the SD-Berichte zu Inlandsfragen reports generated by the Sicherheitsdienst from 1939-1945.

## File Cleaning

All files from the NSHWE database were downloaded in .html format without proper naming due to the time constraints imposed on the use of the database (i.e. files were downloaded with whatever default name the database gave them; these were often standard names and duplicates of each other. Therefore, MacOS appended numbers to the end to signify the order of download. The actual file names contain no usable data for analysis and therefore need to be renamed to some kind of identifying characteristic, which is most often the date of the document.

The following file cleaning and conversions has been performed:

- Extract the date from the top line of all Meldungen aus dem Reich HTML files and rename the files based on that date
- Convert Meldungen aus dem Reich files from .html to .pdf (primarily for proper storage in my own bibliographic database)
- Extract the date from the top line of SD-Berichte zu Inlandsfragen HTML files and rename the files based on that date
- Convert SD-Berichte zu Inlandsfragen files from .html to .pdf (primarily for proper storage in my own bibliographic database))
- Convert all files from Bericht an das Reichsministerium für Volksaufklärung und Propaganda from HTML to PDF (primarily for proper storage in my own bibliographic database)
- Convert all files from Bericht an die Parteikanzlei from HTML to PDF
- Convert all files from Bericht aus Akten der Geschäftsführenden Reichsregierung Dönitz from HTML to PDF
- Convert all files from Meldungen aus den SD-Abschnittsbereichen from HTML to PDF
- Convert all files from Bericht an den Reichsschatzmeister der NSDAP from HTML to PDF
- Convert all files from Vierteljahreslagebericht des Sicherheitshauptamtes from HTML to PDF
- Convert all files from Meldungen über die Entwicklung in der öffentlichen Meinungsbildung from HTML to PDF

The following file cleaning and conversions has yet to be performed:

- Renaming all other files into a useable format
- Converting files into PDF form
- Converting files into TXT form to run machine learning analyses


## Data Cleaning

This section will be expanded once file cleaning has been performed

## Data Mining and Textual Analysis

This section will be expanded once data cleaning has been performed.
