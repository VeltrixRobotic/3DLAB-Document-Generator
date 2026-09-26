3D Lab Document Generator

Baseline: current working reverted version.

Features preserved:
- Quotation, Invoice, Receipt, Delivery Order
- Shared customer and item synchronization
- Add/remove item synchronization
- Normal typing in item fields
- Editable notes/terms and receipt text
- Multi-page table handling
- UNIT PRICE (RM) one-line header

Added in this version:
- "Add File" button directly under Notes / Terms
- Select one or multiple PDF files
- Remove attached files before printing
- Attached PDFs are included after the final generated document page in the combined print view
- Attachments are stored in Save Data File JSON and restored with Load Data

Usage:
1. Click + Add File under Notes / Terms.
2. Select PDF file(s).
3. Click Print / Save PDF.
4. The generated document pages are followed by the attached PDF pages in the print view.
5. Choose Save as PDF in the browser print dialog.

Note: Browser print engines handle embedded PDF pages differently. The combined print view uses embedded PDF frames for the attachment pages; Chrome/Edge are recommended.
