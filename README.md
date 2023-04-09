# Scraping
## Scraping Corporate Annual Meeting for Shareholders and Proxy Statement using Edgar US. Securities and Exchange Commission: 
This program used to scrap Corporate Annual Meeting for Shareholders and Proxy Statement from Edgar. Downloading those documents by hand (manually) will require more time and effort and also introduces the likelihood of mistakes.Therefore, i build this porgram to use the machine “computer” to download them. 
## Pain Points
I spent a long time learning “Selenium” as well as get myself familiar with Edgar back-end code and how I can perform the task. I found it a challenging because you cannot download a document unless you click on it. So, I had to develop a scraping code that allows the computer to click on file name which will take it to a new page. Then, my code will download that page. 
## Outcomes Learned
1. Selenium
2. webdriver
3. send keys through selenium.webdriver.common.keys pakage 
4. Create a request interceptor
5. find_elements, get_attribute from the back-end code
6. click on element_to_be_clickable
