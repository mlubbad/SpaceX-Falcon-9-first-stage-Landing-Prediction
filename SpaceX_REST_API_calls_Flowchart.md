+-----------------------------+
|          Start              |
+-----------------------------+
              |
              v
+-----------------------------+
| Perform HTTP GET request to |
| `api.spacexdata.com/v4/     |
| launches/past`              |
+-----------------------------+
              |
              v
+-----------------------------+
|   Receive JSON response     |
+-----------------------------+
              |
              v
+-----------------------------+
| Normalize JSON data using   |
| `json_normalize`            |
+-----------------------------+
              |
              v
+-----------------------------+
| Make additional API calls   |
| to `/capsules`, `/cores`,   |
| `/launchpads`, `/payloads`  |
+-----------------------------+
              |
              v
+-----------------------------+
| Merge additional data with  |
| main dataframe              |
+-----------------------------+
              |
              v
+-----------------------------+
| Handle missing values and   |
| filter out irrelevant data  |
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
