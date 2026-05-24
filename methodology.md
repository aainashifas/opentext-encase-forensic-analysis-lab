# Methodology

## 1. Case Creation
A new case was created in OpenText/EnCase Forensic using the basic case template. Evidence files were added to the case for analysis.

## 2. Evidence Loading
Two evidence sources were reviewed:
- A raw disk image
- An EnCase evidence file

## 3. File System Review
The raw image was reviewed to identify file system information and disk-level structures. Deleted file indicators and root directory entries were examined at the hex level.

## 4. Evidence Processing
The Evidence Processor was used to run forensic processing tasks, including:
- File signature analysis
- Hash analysis
- Thumbnail creation
- Email artifact parsing
- Internet artifact parsing
- Windows artifact parsing
- Keyword indexing

## 5. Artifact Review
Artifacts reviewed included:
- Registry hives
- NTUSER.DAT
- Email archives
- Internet history/cache records
- Thumbnails
- File metadata

## 6. Searching and Tagging
Indexed searches and raw keyword searches were used to locate relevant content. Bookmarks and tags were created to organize evidence for reporting.

## 7. Reporting
Findings were summarized using a structured forensic reporting approach focused on repeatability, evidence organization, and artifact interpretation.
