# pdf-merger-tool
This project provides a simple Python script to merge multiple PDF files into a single PDF document using the PyPDF2 library.

Project Description
The script pdf_merge.py uses the PyPDF2 library's PdfMerger class to combine multiple PDFs listed in the script or found in a directory into one consolidated output file (merged_output.pdf). This is useful for combining reports, research papers, or any PDF documents that need to be merged for easier sharing or archiving.

How It Works
The script imports PyPDF2 and initializes a PdfMerger object.

It iterates over a list of PDF filenames (pdfs), and appends them into the merger object.

Finally, it writes out the combined PDF to disk and closes the merger to release resources.

This approach allows simple and effective merging without requiring manual reordering or handling PDF internals like page extraction.
