---
title: Building Collections
nav: Building Collections
gallery: true
---

{% include feature/nav-menu.html sections="Information Architecture;Importing Files;Duplicating and Removing Items;Data Limits" %}

<br>


## Information Architecture

**Now that all of your software is connected**, the first step to building your collections is considering how you want to organize your research material. 

**For example:**

---

#### **1. Chronological Organization**  
Best for: **Sequential learning or time-based projects**  
**Example:**  
📘 **Science Coursework**  
- **Course 1**  
  - **Week 1:**  
    - 🗣️ Lecture Notes  
    - 📚 Assigned Readings  
  - **Week 2:**  
    - 🧪 Lab Report: Photosynthesis  
    - 🌻 Articles: Plant Cell Function  
- **Course 2**  
  - **Week 1:**  
    - 📄 Lecture Notes: Genetics  
    - 📚 Assigned Readings  
  - **Week 2:**  
    - 🧪 Lab Report: DNA Extraction  
    - 📜 Articles: CRISPR Technology  

---

#### **2. Project-Based Organization**  
Best for: **Focused, outcome-driven work**  
**Example:**  
🎓 **History PhD Research**  
- **Dissertation**  
  - 📖 Chapter 1: Introduction  
    - 🔑 Key Sources  
    - 🧠 Theoretical Framework  
  - 📖 Chapter 2: The Revolution  
    - 🥇 Primary Sources  
    - 🥈 Secondary Sources  
- **Conference Presentations**  
  - 🗓 **2024 History Symposium**  
    - 📚 Sources on Colonial America  
    - 📝 Presentation Outline   
- **Publications**  
  - 📄 Journal Article: "Revolutionary Networks"  
    - ✍ Drafts  
    - 🔍 Peer-Reviewed Sources  

---

#### **3. Methodological Framework Organization**  
Best for: **Research using diverse approaches**  
**Example:**  
🏙️ **Sociology Scholarship**  
- **Qualitative Research**  
  - 🛤 Ethnography  
    - 📖 Field Notes: Rural Communities  
    - 🗂 Case Studies  
  - 🎤 Interviews  
    - 📝 Transcripts  
    - 🧩 Subject Tagging  
- **Quantitative Research**  
  - 📊 Surveys  
    - 📝 Questionnaire Design  
    - 📈 Response Data  
  - 📉 Statistical Analysis  
    - 🧮 Regression Models  
    - 🗂 Demographic Reports  
- **Mixed Methods**  
  - ⚖ Comparative Studies  
    - 🔄 Case vs. Control Groups  
    - 🌐 Interdisciplinary Approaches   

---

### **Other Research Organization Approaches**  

<table style="width:100%; border-collapse:collapse; text-align:center; border:1px solid black;">
  <tr>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;">Sections</th>
  </tr>
  <tr>
    <td style="border:1px solid black;"><strong>Resource Type</strong></td>
    <td style="border:1px solid black;">📘 Books | 📄 Journal Articles | 🌐 Web Resources</td>
  </tr>
  <tr>
    <td style="border:1px solid black;"><strong>Citation Priority</strong></td>
    <td style="border:1px solid black;">❗ Must Cite | 📚 Further Reading | 🕵️‍♂️ Background Information</td>
  </tr>
  <tr>
    <td style="border:1px solid black;"><strong>Stage of Research</strong></td>
    <td style="border:1px solid black;">🔍 Literature Review | 📊 Data Analysis | ✍ Publication</td>
  </tr>
</table>

<br>

**No one way is better than another**; they simply need to best suit what scholarly output you would like to produce and the format that is most intuitive to you as a researcher. 

**On a technical level**, to create a new collection or subcollection, either select `File` from the menu and `New Collection`, or simply right click `My Library` on the left pane of the application and start building out your collection structure. 

<div class="symbol-container">
    <p class="symbol">&#10042;</p>
</div>

<br>

## Importing Files

Once you have an idea of how to best organize your material, let’s begin filling it in with documents. Another powerful feature of Zotero that can help you save a massive amount of time in citation management is its `Retrieve Metadata` feature. If you drop one or many PDF files in your collection, Zotero will automatically scan these documents for a [Digital Object Identifier](https://www.lib.uidaho.edu/services/data/dois.html){:target="_blank" rel="noopener"} (DOI), PubMed ID (PMID), or other metadata embedded in the file. The software will then query external databases such as CrossRef, Pubmed and Google Scholar that contain bibliographic details of the work’s title, author, publication year, etc. and fill in these items, creating a parent item for the PDF file and differentiating item type depending on if the item is a book, journal article, newspaper article or any of the other 35 qualifiers Zotero distinguishes.

{% include alert.html text="Note: The `Retrieve Metadata` feature (and Zotero in general) is meant to work with PDF files rather than DOC or TXT files. While these file types will import into a collection, metadata retrieval, citation formatting and exporting are prone to corruption." color="light" align="center" %}

**Safe and freely available ways to convert DOC and TXT files to PDF include:**

- Upload the DOC or TXT file to your **Google Drive**.
- Open the file with Google Docs.
- From the "File" menu, choose Download > PDF Document (.pdf).

 **Or**

- Open the DOC file in **Microsoft Word** (available to students as part of the Office 365 suite).
- Select File > Save As.
- Choose PDF as the format and save.

<br>

**While the `Retrieve Metadata` feature is helpful**, it is really only as good as the document you feed into it. If the paper is missing a DOI (as any non-peer reviewed items will be) this metadata will not generate. The foolproof process I like to do when importing is to visit a page that is guaranteed to have all of the metadata I need for my resource, such as the [University of Idaho Library Catalog](https://alliance-uidaho.primo.exlibrisgroup.com/discovery/search?vid=01ALLIANCE_UID:UID&mode=simple){:target="_blank" rel="noopener"} or [WorldCat](https://search.worldcat.org/){:target="_blank" rel="noopener"}, and using Zotero Connector from the Extensions tab in my browser to create a parent file for the document, and then dropping the PDF file into it. 

{% include gallery-figure.html img="zot_04.gif" alt="Demonstration of foolproof way to retrieve all available metadata when importing PDF documents by using Zotero Connector on a library catalog site and then dropping the file into this parent object." caption="Foolproof method for retrieving all available metadata when importing PDF documents by using Zotero Connector on a library catalog site and then dropping the file into this parent object" width="100%" %}

For items that may not have a web presence such as presentations, conference papers and hearings, you can also add files manually by going to the menu and selecting `File` > `New Item` or selecting the green plus sign along the top of the application and picking the appropriate item type.  

<div class="symbol-container">
    <p class="symbol">&#10042;</p>
</div>

<br>

## Duplicating and Removing Items

If you would like to have the same document in two separate collections, simply drag the item into your preferred folder. This won’t remove the file from the current folder but you will now be able to see it in the Duplicate Items folder, which will be at the bottom of your organizational tree. The other important default folder to note is the Trash. Within collections you have the option to both `Remove Item from Collection` to erase a single instance of a document and `Move Item to Trash` to send all available copies to the trash. **This doesn’t automatically delete the document though!** 

Zotero is (maybe rightfully) skittish about accidentally deleting research. To remove completely, visit the Trash folder, select items, right click and select `Delete Permanently` to remove from both your cloud storage and the local storage on your device. Alternatively, you can also select items, right click and select `Return to Library` to recover these documents.  

{% include gallery-figure.html img="zot_05.gif" alt="Demonstration of how to first move items to trash and then permanently delete items in the Trash folder to free up storage space" caption="How to first move items to trash and then permanently delete items in the Trash folder to free up storage space" width="100%" %}

<br>

## Data Limits

This is an appropriate time to mention that **Zotero is free up to 300 MB**, after which tiered storage is available at a subscription fee. There is also a functionality to link your Zotero storage with a Web Distributed Authoring and Versioning (WebDAV) service, which the more technically adept may be interested in reading [more about here](https://www.zotero.org/support/sync){:target="_blank" rel="noopener"}. 

**For the majority of you:**

- Remembering to remove duplicate items
- Emptying your trash folder and 
- Regularly exporting collections once a semester or when a project ends, before deleting those items from your collection 

**should be sufficient to maintain a completely free Zotero account!**

<div class="symbol-container">
    <p class="symbol">&#10042;</p>
</div>

<br>
