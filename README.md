This repo holds the core artifacts and files for the website, Haodoo.net. Using these files, one can construct a website that serves out the e-books via a browser interface.

Haodoo_Catalog_Table.csv contains a catalog table that describes the classification and location of the e-books on the website. Only entries with a category name assigned are books that are visible on the website. If an entry has [NA] as the category name, this entry is likely a duplicate or an orphan file on the server.

Using the book《楚留香傳奇．午夜蘭花》with a book_code of 173 as an example:

The "title_link" field points to the web page that displays the book information at https://haodoo.net/?M=book&P=173.

The “PDB” directory holds the e-books in separate bins and in different formats. The bin location assignment for each book is noted in the catalog table. For example:

https://haodoo.net/PDB/D/173.updb for the UPDB format OR
https://haodoo.net/PDB/D/173.epub for the horizontal EPUB format OR
https://haodoo.net/PDB/D/V173.epub for the vertical EPUB format

The “MP3” directory holds the audiobook files. For example, https://haodoo.net/MP3/0836-01.mp3.

The “book” and “Share” directories hold the book description in HTML format. The assignment of each book description file can be found in the catalog table. For example, https://haodoo.net/book/173.html.

The “covers” directory holds the cover graphic files for a book. Not all books have an associated cover. The assignment of each book cover file can be found in the catalog table. For example, https://haodoo.net/covers/173.jpg.

If a book has multiple volumes with a common title, the volume_track and volume_title fields will have more information. The audiobooks are a prime example of using separate tracks and titles.

If multiple book titles are parts of a series, the series_name field will have that information. For example, the 衛斯理系列 series from the beloved author Mr. 倪匡.

NOTE: If you are a fan of Haodoo, please consider giving a star to this repo. This will make the repo more easily be found by other Haodoo fans. Thank you.
