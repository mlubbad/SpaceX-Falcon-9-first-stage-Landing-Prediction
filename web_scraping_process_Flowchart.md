# Web Scraping Process for Falcon 9 Historical Launch Records

## Flowchart

```plaintext
+-----------------------------+
|          Start              |
+-----------------------------+
              |
              v
+-----------------------------+
| Send HTTP GET request to    |
| Wikipedia page URL          |
| `https://en.wikipedia.org/  |
| wiki/List_of_Falcon_9_and_  |
| Falcon_Heavy_launches`      |
+-----------------------------+
              |
              v
+-----------------------------+
| Receive HTML response       |
+-----------------------------+
              |
              v
+-----------------------------+
| Parse HTML content using    |
| BeautifulSoup               |
+-----------------------------+
              |
              v
+-----------------------------+
| Locate the HTML table       |
| containing launch records   |
+-----------------------------+
              |
              v
+-----------------------------+
| Extract table data and      |
| convert to Pandas dataframe |
+-----------------------------+
              |
              v
+-----------------------------+
| Clean and preprocess data   |
| (handle missing values,     |
| convert data types, etc.)   |
+-----------------------------+
              |
              v
+-----------------------------+
| Store cleaned data in       |
| Pandas dataframe            |
+-----------------------------+
              |
              v
+-----------------------------+
|            End              |
+-----------------------------+
