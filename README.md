# opentext-encase-forensic-analysis-lab
Digital forensic analysis lab using OpenText/EnCase Forensic for evidence processing, artifact review, file signature analysis, hashing, keyword search, and reporting.

# OpenText/EnCase Forensic Analysis Lab

## Overview
This project documents a digital forensic analysis lab completed using OpenText/EnCase Forensic. The lab focused on processing forensic image files, analyzing file system artifacts, identifying file signature mismatches, reviewing registry artifacts, examining email and internet artifacts, and documenting evidence through bookmarks and tags.

## Objective
The objective of this lab was to practice a structured forensic workflow using OpenText/EnCase Forensic and demonstrate how evidence can be processed, searched, analyzed, and documented in a repeatable manner.

## Tools Used
- OpenText/EnCase Forensic v25.3
- Windows forensic workstation
- Forensic image files: Raw image and EnCase evidence image
- Evidence Processor
- Artifact Explorer

## Skills Demonstrated
- Digital forensic case setup
- Evidence image loading and navigation
- File system analysis
- File signature analysis
- Hash analysis using MD5/SHA-1
- Registry artifact review
- Email artifact analysis
- Internet artifact analysis
- Keyword searching
- Bookmarking and tagging evidence
- Forensic reporting workflow

## Methodology
1. Created a new forensic case in OpenText/EnCase.
2. Added raw and EnCase-format evidence images.
3. Verified file system information and reviewed disk-level structures.
4. Ran evidence processing to perform file signature analysis, hash analysis, email recovery, internet artifact parsing, and Windows artifact parsing.
5. Reviewed registry artifacts such as NTUSER.DAT for user activity.
6. Examined email, thumbnail, and internet artifacts.
7. Performed indexed and raw keyword searches.
8. Used bookmarks and tags to organize relevant evidence.
9. Reviewed artifacts using Artifact Explorer.

## Key Findings
- File signature analysis helped identify files whose extensions did not match their actual file type.
- Hash analysis supported evidence integrity and known-file filtering.
- Registry artifacts provided insight into user activity such as recent files, typed URLs, and application usage.
- Internet and email artifacts helped reconstruct user activity.
- Bookmarking and tagging improved evidence organization for reporting.

## What I Learned
This lab strengthened my understanding of how forensic tools process evidence, recover artifacts, identify file mismatches, and support repeatable investigation workflows. It also helped me connect individual artifacts, such as registry entries, thumbnails, internet history, and email records, to broader investigative conclusions.

## Disclaimer
This project was completed in a controlled academic lab environment using provided forensic images. No real personal, confidential, or production data is included in this repository.
