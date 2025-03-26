# GP+ | AI-Powered Clean Energy Matchmaking (Prototype)

This is a public-facing prototype for the **Green Power Plus (GP+)** platform.

---

### Project Overview

**GP+** is a rule-based AI agent that interprets natural language queries, extracts structured parameters, and dynamically matches users with clean energy vendors within a scalable, AI-assisted framework. It leverages **predefined logic and an LLM-powered engine** to process user input and return tailored results based on key criteria such as **capacity, financing, certifications, battery storage, location**, and **installation timeline**.

While currently operating on deterministic rules, the system establishes the foundation for future **learning agents**, by structuring user interactions, vendor data, and decision logic for dynamic adaptation and reinforcement.

---

### Key Features (Prototype Phase)

- Natural language input (LLM-powered)
- Structured data extraction
- Vendor matching based on rule logic
- React-based user interface
- Flask backend with PostgreSQL

---

### Project Structure

- `frontend/` – Simplified React UI for user input and results  
- `backend/` – Flask API that handles query parsing and rule-based matching  
- `docs/` – Visual materials or diagrams for demo/pitch purposes

---

### Live Demo

[Try the live demo](https://greenpowerplus.replit.app)

---

### Disclaimer

This is a simplified version for demonstration purposes. Some logic and components have been abstracted for confidentiality.

---

### Sample Output

<details>
<summary>📦 Click to view a sample match</summary>

```json
{
  "ID": 1083,
  "Product": "PV",
  "Capacity": "150 kW",
  "Price": "€37,127",
  "Certifications": "IEC 61215", "TÜV Rheinland", "IEC 61730"
  "Financing Available": "Yes",
  "Battery Storage": "Yes",
  "Location": "Lombardy",
  "Installation Timeline": "6 months"
}
