# 🗺️ Excel Linestring Parser

This Excel file extracts the **start and end coordinates** from WKT `LINESTRING` geometries.

### ✨ Example Input

LINESTRING(-81.836326 28.123202,-81.832427 28.110597,-81.831532 28.107264)

### 🚀 Output
| From Longitude | From Latitude | To Longitude | To Latitude |
|----------------|----------------|--------------|--------------|
| -81.836326 | 28.123202 | -81.831532 | 28.107264 |

### ⚙️ How It Works
Built with complex Excel formulas that:
- Parse text using string manipulation functions  
- Split coordinates by commas  
- Extract the first and last points in each `LINESTRING`  
- Output clean “From” and “To” latitude/longitude columns  

### 💡 Why I Built This
I wanted a quick, no-code way to extract coordinate pairs from GIS-style data — purely inside Excel.  
It’s a small project that blends **logic, creativity, and data handling**.

---

⭐️ *Built with good vibes and formulas.*
