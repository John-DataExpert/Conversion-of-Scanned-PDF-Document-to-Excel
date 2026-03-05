# Conversion of Scanned Paper Document to PDF and then to Excel

### Overview
This project showcases the end-to-end process of converting a poorly scanned, multi-page paper document to a PDF document containing a financial beneficiary list into a structured, clean, and validated Excel spreadsheet. This task is critical for data management, auditing, and payment processing.

***Confidentiality Note:*** *This dataset is entirely fictional and is designed to simulate the challenges of working with sensitive financial data. It contains no real names, account numbers, or personal information, demonstrating my process while upholding strict data confidentiality standards.*

---

### The Problem
A client had a 11-page scanned PDF of a payment list. The data was unsearchable, difficult to read, and contained inconsistencies. Standard OCR (Optical Character Recognition) tools failed due to the poor scan quality. They needed this data accurately digitized into an Excel file for payment processing and record-keeping, with any problematic entries clearly flagged for review.

### The Solution
I performed a detailed data conversion and cleaning process, transforming the unusable PDF into a valuable data asset.

1.  **Manual Data Extraction:** Due to poor OCR results, I conducted a meticulous manual transcription of the data to ensure the highest level of accuracy.
2.  **Data Structuring & Cleaning:** I organized the raw data into a logical structure (Name, Account, Bank, etc.) and performed extensive cleaning. 
3.  **Data Validation & Flagging:** I created a "VerificationNeeded" column to flag entries with issues like missing phone numbers, failed account verifications noted in the source, or ambiguous remarks. This made the review process for the client highly efficient.
4.  **Professional Formatting:** The final Excel sheet was professionally formatted with filters, frozen panes, and clear headings for easy navigation and use.

[Screenshot of Final Structured Excel Sheet](https://github.com/John-DataExpert/Conversion-of-Scanned-PDF-Document-to-Excel/blob/main/screenshot.PNG)

---

### Tools Used
*   **Microsoft Excel:** For data entry, cleaning, formatting, and validation.
*   **PDF Viewer/Reader:** For viewing the source document.
*   **Google Lens:** Note that I attempted automated methods first before resorting to a more robust manual process.

---

### My Process
1.  **Initial Assessment:** Evaluated the PDF and determined that manual extraction was necessary for accuracy.
2.  **Data Entry:** Transcribed the data field-by-field into an Excel spreadsheet, ensuring each row corresponded to a unique beneficiary.
3.  **Structural Cleaning:**
    *   Removed currency symbols and commas from the `Amount` column and converted it to a numeric format.
    *   Standardized bank names (e.g., "Grant BANK" and "GRANT Bank" became "GRANT BANK").
4.  **Content Validation:** Created rules to flag rows for review. 
5.  **Final Review:** Conducted a final pass to ensure all data was correctly aligned and the validation flags were accurate.

---

### Key Outcomes & Results
*   **Data Usability:** Transformed a completely unusable document into a fully functional, sortable, and auditable database in Excel.
*   **Risk Reduction:** The validation flagging system reduced the client's review time by an estimated **75%** and minimized the risk of payment errors.
*   **Demonstrated Expertise:** This project shows not just data entry, but a comprehensive data management approach, from handling messy data to implementing quality control checks.
