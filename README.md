## Purpose
We are attempting build a conversational chatbot that is built on an LLM. It’s primary purpose is to help **GE field engineers** & **customers** of GE by eliminating the need to comb through a lot of documentation to find the information they need. Instead they will be able directly type their queries into a chat interface and receive context appropriate answers with citations to the original user manuals & documents. 

Our intention is that in the eyes of the end user it will appear as though they are talking to an **expert** on every GE engineered product. 

## Tech Stack
1. LLM: **Llama 2** (Open Source) , **GPT-4**, **GPT 3.5 turbo**
2. **BeautifulSoup** and **Selenium** for scraping their customer care portal
3. Vectorstore: **ChromaDB**

