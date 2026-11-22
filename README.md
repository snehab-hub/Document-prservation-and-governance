# Document preservation and governance

# Repository structure
# Sampling strategy
### Sampling Strategy Using ChatGPT

ChatGPT was used to assist in selecting a representative sample from the PDF archive. The archive (ZIP file) was uploaded to ChatGPT, and a prompt was provided to generate a sample ZIP file containing screenshots of selected PDFs, along with a rationale for selecting each document. The sampling approach was focused on variations in document length, metadata quality, text extractability, scanned documents, and duplicate files. Through this process, documents suitable for further analysis of preservation risks and document quality were identified. The selected samples were also reviewed to verify the accuracy of the AI-generated information.

A purposive sampling approach was adopted to capture meaningful differences within the archive rather than selecting documents randomly. Nine documents were selected to represent different technical characteristics and preservation challenges.


# Methodology
The analysis involved examining the selected PDFs and recording their technical and descriptive characteristics in an Excel inventory.

Step 1 — Document Inspection: Each PDF was examined to identify its filename, document type, page count, creation date, modification date, and technical characteristics.

Step 2 — Metadata Assessment: Embedded metadata was reviewed to determine whether titles, authors, subjects, keywords, and dates were available and consistent with the document content. Metadata quality was classified as High, Medium, or Low.

Step 3 — Text-Layer Assessment: The PDFs were examined to determine whether they contained extractable text or were image-based. Documents without extractable text were identified as potential OCR candidates.

Step 4 — Duplicate Identification: Files were manually verified to identify exact duplicates. This confirmed that 1156.pdf and 1157.pdf contain identical file content.

Step 5 — Sensitive Data Review: Documents were examined for personal contact details, property-owner information, and other potentially sensitive content. Files containing identifiable information were flagged for further review.

Step 6 — Verification: The recorded metadata and technical characteristics were compared with the original PDFs. AI-generated findings were reviewed because some initial results, including page counts and text-layer classifications, required correction.

# Tools Used 

| Tool | Purpose |
|---|---|
| **ChatGPT** | Assisted with representative PDF sampling, generating screenshots, identifying technical characteristics, and documenting findings. |
| **Microsoft Excel** | Used to record PDF metadata, document types, page counts, text-layer status, OCR requirements, sensitive data, and preservation concerns. |
| **Adobe Acrobat** | Used to visually inspect original PDFs and verify document content, page counts, and metadata information. |
| **GitHub** | Used as a shared repository to organize sample PDFs, supporting materials, documentation, and project findings. |

# Major findings

- **Missing and Inconsistent Metadata:** Several sampled PDFs contained incomplete or inaccurate metadata, which could affect document identification, classification, searchability, and retrieval.

- **OCR and Searchability Issues:** The image-based document `970.pdf` lacked a searchable text layer, indicating the need for Optical Character Recognition (OCR) to improve accessibility and text retrieval.

- **Duplicate Documents:** Exact duplicates, such as `1156.pdf` and `1157.pdf`, were identified. Duplicate files may lead to unnecessary storage consumption and confusion during document retrieval and management.

- **Sensitive Information:** Documents `1079.pdf` and `812.pdf` contained identifiable property-owner or contact information. Although some information may be publicly available, further privacy and access reviews are recommended to ensure appropriate handling.
