# 💫 About Me
🔭 Computer Science MSc candidate researching NLP @HUJI ([publications](https://www.semanticscholar.org/author/Nitzan-Barzilay/2305813534)), former Data Scientist @PayPal & Research Assistant @AI2

💬 Feel free to ask me about any of my repos, I love getting messages about my work! 
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/nitzan-barzilay) [![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?logo=Twitter&logoColor=white)](https://twitter.com/Nitzan_Barzilay)   
☕ If my code or my notes helped you, you can buy me a coffee if you'd like [![Ko-Fi](https://img.shields.io/badge/Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/sikumim) 

# 📄 Detailed NLP Notes and Resources (Hebrew)
## [Detailed Notes Collection](https://github.com/NitzanBarzilay/Notes)
I have collected all of the detailed notes I wrote during my studies at HebrewU as well as courses I studied independently, and published them as a part of my goal to make Data Science & NLP topics more accessible to Hebrew speakers. 

This colelction contains detailed notes in Hebrew on subjects such as Math (Calculus, Linear Algebra, Probability, Discrete Math), foundations of Computer Science (Data Structures, Algorithms, Complexity), as well as advanced Data Science (Machine Learning, NLP). 

This includes my recent [detailed notes (90 pages) for Stanford's CS224N (NLP with DL) course](https://github.com/NitzanBarzilay/Notes/blob/main/3%20-%20Advanced%20CS%20Courses/Stanford%20CS224n%202021%20-%20DL%20for%20NLP%20-%20Nitzan%20Barzilay.pdf), that gained more than 1K likes across Israeli DS & ML communities.


## [NLP Knowledge Hub](https://nitzanbarzilay.notion.site/Nitzan-s-NLP-Knowledge-Hub-94f244a659664ef18e2b781ba0c1a81b)
Recently I decided to share my private [Notion hub](https://nitzanbarzilaynlp.simple.ink/) where I organize all of my NLP knowledge (mostly in Hebrew). This hub is meant for my personal use, but since many people found it useful I decided to share it. It conatains some notes by topic (such as NLP tasks, architectures or uses) that has significant ovarlaps with my CS224N notes, as well as noted I wrote for a few dozens NLP papers I have read in the past year for my studies and my reasearch. 

![image](https://github.com/NitzanBarzilay/NitzanBarzilay/assets/36603609/0039645a-2eb8-4a71-a238-bdaebaf12332)


## [Notion template for scientific papars knowledge managment](https://www.notion.so/templates/scientific-papers-knowledge-hub)
I shared my simple-but-useful [system](https://www.notion.so/templates/scientific-papers-knowledge-hub) for queueing and reviewing papers I read (or plan to read). This Notion template is free to use, and also contains tips on how to personalize it to work for your needs. 
![image](https://user-images.githubusercontent.com/36603609/228277258-881a824f-9f2c-4a8a-b646-92744439d2b9.png)

# 👩‍💻 NLP / Data Science Public Projects

## [Corpify](https://github.com/maayansharon10/Corpify) (2023)
#### A Language model that rephreases spoken English into workplace-appropriate language! 

In this project, we introduce the novel NLP task of _corpy textual style-transfer_, which involves the transformation of casual English text into a style suited for a professional workplace setting. We constructed an original parallel corpus comprising 634 sentences in casual English and their corporate-style paraphrases. 

This project includes the dataset itself, the code for fine-tuning the style transfer models, 2 of the best performing fine-tuned models, and code for fine-tuning a style detection model for detecting corpy style in text.

_Methods used in this NLP projects: Textual style transfer, text classification._

![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54) 

![image](https://github.com/NitzanBarzilay/NitzanBarzilay/assets/36603609/5fe6b651-2560-4649-9364-1544fbc0967d)


## [Knesset Topic Classification](https://github.com/NitzanBarzilay/KnessetTopicClassification) (2022)
#### An independant multi-phase NLP project for classifying parlemintary quotes in Hebrew into 8 topics. Also includes the annotated dataset. 

In this project, I started with a raw dataset of quotes (in Hebrew) gathered from protocoles of the Knesset (the Israeli parliment). In the first stage of the project, I used unsupervised topic modeling methods in order to cluster quotes by topics. The topic assignment that was created during the first stage were used to prioritize qoutes for manual tagging process - quotes with the highest confidence score were sent to mannual tagging. This process created ~2,700 quotes that were manually tagged into 8 topics (in addition to a "no topic" tag). Then, in the second phase of this project, I trained a supervised classifier to predict quotes topics.

_Methods used in this NLP projects: Topic modeling (unsupervised), Topic classification (supervised)._

![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54) 

![image](https://user-images.githubusercontent.com/36603609/208291089-f72c5df3-8985-46d1-9d4a-8222aa82d420.png)


## [PickUsLunch](https://github.com/NitzanBarzilay/PickUsLunch) (2022)
#### AI assistant that helps groups of friends or co-workers find a restaurant to order from together, that best matches the group members' dining preferences.

In this project, we used restaurants menus gathered via Wolt's API and created a smart system that helps groups of friends or co-workers find a single restaurant that matches everyone's needs and preferences (such as vegeterianism, price limits, prefered cuisines etc). We examined several different algorithms (neither are ML-based), all of them provided solutions who were incredibly close to the optimal solution (that could be found by iterating over the entire 30M combinations dataset) in a fraction of the time (up to 11K times faster)!

_Methods used in this AI projects: local search, genetic algorithms._

![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54)

![image](https://user-images.githubusercontent.com/36603609/208291119-0ad15f9c-fed5-4e6c-b20a-92c59f316ef4.png)



