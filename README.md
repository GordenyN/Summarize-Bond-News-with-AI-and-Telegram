# Summarize Bond News with AI and Telegram


### 📋 Overview

This n8n workflow:
- Extracts news from bonds.finam.ru via Firecrawl API
- Formats news fields (title, content, date)
- Combines all news into a single array
- Analyzes news by issuer using the Issuer Summary Agent (Google Gemini)
- Sends the final summary to Telegram

### ⚙️ Main Steps:
1. Extract News (Firecrawl API) — fetch news articles.
2. Wait 90 / 30 seconds — wait for API results.
3. Parse News JSON — convert JSON into a structured format.
4. Format News Fields — structure the data.
5. Combine All News — merge all news items.
6. Issuer Summary Agent — analyze and create issuer summaries.
7. Send to Telegram — deliver the summary.

### 📬 Outputs

Telegram screenshots of the summary delivery:

<img width="1178" height="1192" alt="image" src="https://github.com/user-attachments/assets/8b3843bb-15a7-4a0d-892d-df7be311ffb1" />


<img width="1105" height="1182" alt="image" src="https://github.com/user-attachments/assets/c485ce10-4454-426b-ab22-e7fad2d552b3" />


<img width="783" height="599" alt="image" src="https://github.com/user-attachments/assets/b5c34025-2f9e-49db-8915-eb5e11eb964a" />








