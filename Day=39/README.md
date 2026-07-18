# Day 39

# PDF Splitter & Merger

Today I built an interactive **PDF Splitter & Merger** using Claude. The application runs entirely in the browser and allows users to split, merge, reorganize, and export PDF files without uploading them to any server. All processing is performed locally, ensuring privacy and fast performance.

The project provides a clean workspace for handling PDF documents while offering multiple splitting methods, drag-and-drop support, page management, and real-time document statistics.

---

## Features

### PDF Splitter

The splitter supports multiple methods for dividing PDF documents:

- Split using custom page ranges
- Split after specific pages
- Split every N pages
- Extract selected pages into a new PDF
- Preview output structure before exporting

---

### PDF Merger

Users can combine multiple PDF files into a single document with options to:

- Add multiple PDF files
- Rearrange document order
- Merge files locally
- Download the combined PDF

---

### Page Management

The application provides several tools for managing pages:

- Thumbnail preview of pages
- Select individual or multiple pages
- Rotate selected pages by 90°
- Mark pages for removal
- Clear selections instantly

---

### Document Information

A live document statistics panel displays:

- Total Pages
- Selected Pages
- Pages Marked for Deletion
- Output Files
- PDF File Size

These values update dynamically as modifications are made.

---

## Privacy & Performance

One of the biggest advantages of this application is that all PDF processing happens entirely on the client side.

- No files are uploaded to any server
- Works completely offline after loading
- Faster processing for most documents
- Better privacy and security

---

## What I Tested

### PDF Splitter

I successfully tested:

- Loading a PDF document
- Viewing page thumbnails
- Selecting pages
- Custom page range splitting
- Output preview generation

### PDF Merger

I also tested:

- Importing multiple PDF files
- Merging documents
- Rearranging files before merging
- Exporting the final merged PDF

---

## What I Learned

### 1. Browser-based PDF processing is possible

Modern JavaScript libraries allow complete PDF manipulation directly inside the browser without requiring backend servers.

### 2. Multiple splitting strategies improve flexibility

Different users have different requirements, so supporting custom ranges, fixed intervals, and page extraction makes the application much more useful.

### 3. Interactive previews improve usability

Displaying page thumbnails and live document statistics helps users verify their actions before exporting files.

### 4. Client-side processing improves privacy

Keeping documents entirely on the user's device eliminates privacy concerns associated with uploading sensitive PDFs.

### 5. AI can accelerate utility application development

Claude generated a polished PDF utility with a modern interface, responsive layout, and advanced document management capabilities in a very short time.

---

## Technical Concepts Used

- HTML5
- CSS3
- Vanilla JavaScript
- Drag & Drop API
- File API
- PDF Processing Libraries
- DOM Manipulation
- Client-side File Generation
- Responsive UI Design
- Dynamic State Management

---

## Files

- `pdf-splitter-merger.html` — Interactive PDF Splitter & Merger application
- PDF Splitter screenshots
- PDF Merger screenshots

---

## Conclusion

This project demonstrated how modern web technologies can handle complex PDF operations entirely within the browser. Features such as page selection, custom splitting methods, document merging, and live previews create a practical utility that is both fast and privacy-friendly.

The biggest takeaway from this challenge is that **client-side web applications can now perform advanced document processing without relying on external servers, making them faster, safer, and more accessible.**

---

## Challenge

**60 Days Claude Challenge — Day 39**

Built with Claude and explored browser-based PDF processing through an interactive PDF Splitter & Merger application.
