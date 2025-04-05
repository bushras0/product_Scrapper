
### 🛍️ Product Scraper – Smart Data Extraction with AI Prompts

**Overview:**

The Product Scraper is a full-stack web application designed to intelligently scrape product data from any e-commerce webpage or product listing. It uses **React JS** for the frontend and **FastAPI (Python)** as the backend. What makes this tool powerful is its prompt-based scraping mechanism, allowing users to extract specific product information dynamically.

---

### 🚀 Tech Stack:

- **Frontend:** React JS  
- **Backend:** FastAPI (Python)  
- **Other Tools:** BeautifulSoup / Playwright / Requests (or similar scraping libraries), JSON for structured output

---

### ⚙️ How It Works:

1. **User Interface (React JS):**  
   Users interact with a clean and responsive UI where they can:
   - Input a product URL
   - Provide a natural language prompt like:  
     _“Extract product name, price, images, and availability”_

2. **API Communication (FastAPI):**  
   The prompt and URL are sent to the backend, where FastAPI processes the request.

3. **Web Scraping Logic (Python):**  
   The backend visits the provided URL and scrapes the page using intelligent parsing techniques. It uses the provided **prompt** to determine what information to extract—allowing highly customizable and context-aware scraping.

4. **Data Output:**  
   The structured product data (JSON) is sent back to the frontend and displayed in a user-friendly format.

---

### ✨ Features:

- ✅ **Prompt-based scraping** for flexible data extraction  
- ✅ **Works with any product URL** (supports most common e-commerce layouts)  
- ✅ **Scalable backend** with FastAPI for performance  
- ✅ **Modern React frontend** with responsive design  
- ✅ **Extracts text, images, prices, availability, and more**  
- ✅ **Lightweight and easy to deploy**

---

### 📦 Use Cases:

- Competitor price tracking  
- E-commerce data aggregation  
- Market research  
- Real-time product comparison tools  
- Auto-filling product databases

