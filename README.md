### **Project: Web Scraping and Analysis of a Jin Yong Novel**

#### **Objective:**
- Implement object-oriented programming to accomplish the tasks below.

#### **Tasks:**

1. **Web Scraping:**
   - Scrape all chapters of a Jin Yong novel from the internet.
   - Save each chapter's webpage locally.
     - **Deliverable:** Webpage files.

2. **Text Extraction:**
   - Process the scraped webpages to extract the novel's text.
   - Save the extracted text locally.
     - **Deliverable:** Text files of the novel's content.

3. **Text Analysis:**
   - Perform word segmentation on the novel text to identify and count words.
   - Count the frequency of words and the occurrence of characters in each chapter.
   - Save the statistics in CSV files.
     - **Deliverables:** Two CSV files for word frequencies and character occurrences.

#### **Requirements:**

- Utilize an object-oriented approach with at least three custom classes, each designed for specific tasks (e.g., web scraping, text extraction, word segmentation and frequency counting).
- Consider class and interface design for clear program structure and logic, ensuring code reusability.
- Incorporate considerations for web scraping etiquette, such as not overwhelming a website with requests.
- Handle encoding for Chinese webpages appropriately.
- Include custom dictionaries for word segmentation, especially for main characters (refer to "金庸小说人物.txt" for a character list).

#### **Class Design Suggestions:**

1. **WebScraper:** A class for fetching web pages.
2. **TextExtractor:** A class for extracting main text from the HTML content.
3. **TextAnalyzer:** A class for performing word segmentation and calculating word/character frequencies.

#### **Additional Notes:**

- Avoid triggering website protection mechanisms by spacing out requests.
- If a website blocks your requests, consider alternative sources listed in the project description.
- Submit a document explaining your class designs and interfaces.

#### **Submission:**

- Source code with comments.
- Scraped webpage files.
- Extracted text files.
- CSV files for word frequencies and character occurrences.
- A document detailing your approach to class and interface design.

This structured overview should help you organize your project effectively, ensuring that each component and requirement is addressed systematically.
