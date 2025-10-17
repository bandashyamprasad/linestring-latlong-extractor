# 🗺️ Excel Linestring Parser

This Excel file extracts the **start and end coordinates** (latitude & longitude) from WKT `LINESTRING` geometries — all using Excel formulas.  

It automatically converts the coordinate order from `lon lat` to the standard `lat, lon` format used by most mapping tools.

---

### 🧠 Example Input
LINESTRING(-81.836326 28.123202,-81.832427 28.110597,-81.831532 28.107264,...)
### 🚀 Output
| From (Lat, Lon) | To (Lat, Lon) |
|-----------------|----------------|
| 28.123202, -81.836326 | 28.078552, -81.83208 |

---

### ⚙️ How It Works
Built entirely with Excel formulas that:
- Parse text strings to extract coordinate pairs  
- Identify the first and last coordinate points  
- Reorder them to **Latitude, Longitude** format  
- Output clean “From” and “To” location columns  

---

### 💡 Why I Built This
I wanted a quick, no-code way to extract coordinate pairs from GIS-style WKT data — purely inside Excel.  
This file makes it easy to grab start/end locations from multiple linestrings instantly.

---

⭐️ *Built with good vibes, logic, and Excel magic.*
