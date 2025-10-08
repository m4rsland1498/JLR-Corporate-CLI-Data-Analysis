# 📊 JLR Sales Data Viewer (CLI)

A terminal-based tool for downloading and visualizing **Jaguar Land Rover** quarterly and yearly sales volume data directly from the [official JLR Results Centre](https://www.jlr.com/results-centre).

This script allows you to:
- Browse and select fiscal years and quarters.
- Download official Excel files of sales volume data.
- Select specific car brands or models.
- View bar chart visualizations of their retail sales data in the terminal.

---

## 🧰 Features

- ✅ **Interactive terminal menus** using `simple_term_menu`.
- ✅ **Web scraping** with `BeautifulSoup` to dynamically locate and download Excel files.
- ✅ **Bar chart rendering** using `termgraph`.
- ✅ **Excel parsing** with `openpyxl`.
- 🚧 (Coming Soon) **Pie chart visualization** support using `termcharts`.

---

## 📦 Dependencies

Install the required Python packages:

```bash
pip install -r requirements.txt
```

Alternative manual installation:

```bash
pip install requests beautifulsoup4 openpyxl simple-term-menu termgraph termcharts
```
