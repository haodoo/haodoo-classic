This repo holds the core artifacts and files for the website, https://haodoo.net. Using these files, one can construct a website that serves out the e-books via a browser interface.

Haodoo_Content_Mapping.sql contains a catalog table that describes the classification and location of the e-books on the website. Only entries with a category name assigned are books that are visible on the website. If an entry has [NA] as the category name, this entry is likely a duplicate or an orphan file on the server.

The “PDB” directory holds the e-books in separate bins and in different formats. The bin location assignment for each book is noted in the catalog table.

The “MP3” directory holds the audiobook files.

The “book” and “Share” directories hold the book description in HTML format. The assignment of each book description file can be found in the catalog table.

The “covers” directory holds the book cover graphic files. The assignment of each book cover file can be found in the catalog table.

NOTE: If you are a fan of Haodoo, please consider giving a star to this repo. This will make the repo more easily found by other Haodoo fans. Thank you.
