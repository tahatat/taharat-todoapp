# AI Document Scanning

The AI Document Scanning feature allows users to seamlessly scan and extract data from various document types. This functionality is designed to streamline the process of digitizing and managing physical documents.

## Supported Document Types

- PDF files
- Image files (JPEG, PNG, TIFF)
- Microsoft Word documents (DOCX)
- Rich Text Format (RTF)
  
## Extraction Methods

The AI utilizes multiple extraction methods to ensure accurate data retrieval, including:

- Optical Character Recognition (OCR) for text recognition and extraction from images.
- Intelligent Document Processing (IDP) to analyze the structure and content of documents.
- Pre-trained machine learning models that distinguish between different types of documents and fields.

## Usage Examples

### Example 1: Scanning a PDF Document

```python
from taharat import document_scanner

# Scan a PDF document
results = document_scanner.scan_document('path/to/document.pdf')
print(results)
```

### Example 2: Scanning an Image File

```python
# Scan an image file
results = document_scanner.scan_document('path/to/image.png')
print(results)
```