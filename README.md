## ** Part 1: Scraping Mars News**
**Goal**: Scrape the **latest Mars news headlines** and **preview text** from NASA’s Mars News website.  
 **Approach**:
1. Use **Splinter** to automate browsing.
2. Extract the **title** and **preview text** using **BeautifulSoup**.
3. Store the results in a **list of dictionaries**.
4. Save the data as a **JSON file** (`mars_news.json`).

---

## ** Part 2: Scraping & Analyzing Mars Weather**
**Goal**: Scrape and analyze **Martian weather data** from the Mars Temperature Data Site.  
 **Approach**:
1. **Extract an HTML table** containing Mars weather data.
2. **Convert the table into a Pandas DataFrame**.
3. **Clean & convert data types** (dates, integers, floats).
4. **Analyze**:
   - How many months exist on Mars?
   - How many Martian days (`sols`) of data exist?
   - Coldest and warmest months on Mars?
   - Highest and lowest atmospheric pressure months? 
   - How long is a **Martian year** in Earth days?

Output
- A cleaned **CSV file** (`mars_weather.csv`) with structured data.
- **Bar charts & line plots** visualizing **temperature trends and pressure variations**.
