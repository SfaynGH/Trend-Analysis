# Trend-Analysis


# Social Media Automation Workflow

This project automates the process of scraping trending topics from **X (formerly Twitter)**, generating engaging content using **ChatGPT** and **DeepSeek**, and posting the content on **Twitter**. The workflow is orchestrated using **n8n**, a powerful workflow automation tool.

---

## **Features**
1. **Scraping Trends**:
   - Uses **Selenium** to scrape trending topics and related tweets from X.
   - Stores the data in a **Pandas DataFrame** and saves it locally as a CSV file.

2. **Uploading to Google Sheets**:
   - Automatically uploads the scraped data to **Google Sheets** using **n8n**.

3. **Content Generation**:
   - Generates tweets for each trend using **ChatGPT**.
   - Creates images for each trend using **DeepSeek**.

4. **Posting on Twitter**:
   - Posts the generated tweets and images on Twitter using **Tweepy**.

5. **Full Automation**:
   - The entire workflow is automated using **n8n**, ensuring efficiency and scalability.

---

## **Tools and Technologies**
- **Python**: For scraping and data processing.
- **Selenium**: For web scraping.
- **Pandas**: For data manipulation and storage.
- **n8n**: For workflow automation.
- **Google Sheets API**: For uploading data.
- **OpenAI (ChatGPT)**: For generating tweets.
- **DeepSeek**: For generating images.
- **Tweepy**: For posting on Twitter.

---

## **Setup Instructions**

### 1. **Prerequisites**
- Python 3.x installed.
- n8n installed (locally or cloud version).
- API keys for:
  - Google Sheets API.
  - OpenAI (ChatGPT).
  - DeepSeek.
  - Twitter API.

### 2. **Install Python Dependencies**
Run the following command to install the required Python libraries:

```bash
pip install selenium pandas tweepy gspread oauth2client
