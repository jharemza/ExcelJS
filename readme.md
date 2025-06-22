# 📊 Excel Text Differ

A single-page web app that compares text differences between two Excel columns using a character-level diff algorithm. Ideal for document revision audits, version tracking, or identifying subtle content changes between text pairs.

---

## 🚀 Features

- ✅ Upload an Excel file with two labeled columns: `Previous` and `Current`
- ✅ Visualizes differences using a character-level diff algorithm
- ✅ Cleanup options for semantic, efficiency, or raw diff output
- ✅ Drag-and-drop interface powered by Bootstrap & jQuery
- ✅ No backend required — runs entirely client-side

---

## 🖼️ Demo

Visit the live app here: [Excel Text Differ](https://jharemza.github.io/excel-text-differ/)

---

## 🧪 Usage

### Excel File Format Requirements

- The spreadsheet must contain **exactly 2 columns**:  
  `Previous` (left column) and `Current` (right column)
- The **first row** must contain these headers
- Drag and drop the file into the upload box to see results

### Cleanup Options

- **Semantic Cleanup**: Improves human readability by merging trivial differences
- **Efficiency Cleanup**: Optimizes for computational performance
- **Raw Output**: Displays unprocessed diffs

### Timeout Setting

Set a computation timeout to avoid long-running comparisons. Set to `0` for no timeout.

---

## ⚙️ Tech Stack

| Tool / Library      | Purpose               |
| ------------------- | --------------------- |
| SheetJS (xlsx)      | Excel file parsing    |
| diff_match_patch.js | Text diff generation  |
| Bootstrap           | Layout and UI styling |
| jQuery              | DOM manipulation      |

---

## 📁 Project Structure

```bash
excel-text-differ/
├── index.html # Main app page
├── LICENSE
└── readme.md # Project documentation
```

---

## 📄 License

This project is licensed under the terms of the [MIT License](LICENSE).
