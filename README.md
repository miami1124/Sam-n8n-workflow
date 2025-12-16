# ⚡ [Sam]'s n8n Automation Lab

Welcome to my automation repository! Here, you will find the **n8n Workflow templates** that I use daily, have tested thoroughly, and find highly effective.

## 🧩 Automation Categories

This repository focuses on solving pain points for video creators, covering three core areas:

* **🤖 AI Video Post-Production**
    * **Shorts Automation**: Uses GPT-4o to select highlights, combined with FFmpeg to automatically crop and synthesize vertical short-form videos.
    * **Smart Editing**: Automates audio splitting and transcoding processes to bypass API limitations.

* **🌍 Content Localization & SEO**
    * **Subtitle Localization Factory**: Automatically translates Chinese subtitles into English and syncs updates to YouTube video metadata.
    * **Structured SEO**: AI generates chapter summaries with timestamps to improve search rankings.

* **📊 Channel Analytics Ops**
    * **Performance Tracking**: Integrates with the YouTube Data API to automatically fetch viewing data.
    * **Automated Reporting**: Generates bi-weekly reports and pushes them to LINE, saving time on manual spreadsheet compilation.

## 🚀 How to Use

All templates are stored in `.json` format.

1. **Find a Template**: Browse the list or folders above to find the automation workflow that interests you.
2. **Get the Code**: Enter the folder and download the file.
3. **Import to n8n**:
    * In your n8n canvas interface.
    * Click `Import from...` > `From File` or simply paste the code (Ctrl+V).
4. **Configure Credentials**:
    * After importing, click on the red nodes to bind your own account credentials.

* *Note: API calls (e.g., OpenAI) may incur costs; please monitor your usage accordingly.*
* *Please ensure you understand the workflow logic before use to avoid accidentally deleting important data.*
