## Deciphering Big Data

### Jump to Section

- [Unit 1: Introduction to Big Data Techniques and Data Management](#unit1)
- [Unit 2: Introduction to Data Types and Formats](#unit2)
- [Unit 3: Data Collection and Storage](#unit3)
- [Unit 4: Data Cleaning and Transformation](#unit4)
- [Unit 5: Data Cleaning and Automating Data Collections](#unit5)
- [Unit 6: Database Design and Normalisation](#unit6)
- [Unit 7: Constructing Normalised Tables and Database Build](#unit7) 
- [Unit 8-10: Comparing Compliance Laws](#unit8) 
- [Unit 10: APIs for Data Parsing](#unit10)
- [Unit 11: DBMS Transaction and Recovery](#unit11)
- [Unit 12: Personal Reflection](#reflection)

### Learning Outcomes
 - Introduce and review various concepts of big data, technologies, and data management to enable you identify and manage challenges associated with security risks and limitations.
 - Critically analyse data wrangling problems and determine appropriate methodologies and tools in problem solving.
 - Explore different data types and formats. Evaluate various data storage formats ranging from structured, quasi structured, semi structured, and unstructured formats. We explore the various memory and storage requirements.
 - Critically examine various data collection methods and sources. Review fact finding methods to determine the integrity, reliability and readiness of data extracted and presented for pre-processing, cleaning, and usage.
 - Examine data exploration methods and analyse data for presentation in an organisation. Critically evaluate data readability, readiness, and longevity within the data Pipeline. Examine cloud services, API (Application Programming Interfaces) and how this enables data interoperability and connectivity.
 - Examine and analyse the ideas and theoretical concepts underlying DBMS (Database Management Systems) Database Design and Modelling.
 - Explore the future of use of data and deciphering by examining some fundamental ideas and concepts of machine learning and how these concepts are applied in various methods in handling big data.

### Unit 1 Introduction to Big Data Techniques and Data Management <a name="unit1"></a>

Data acquisition will change into continuous, real-time insight into the connected devices through the Internet of Things (IoT). According to Huxley et al. (2020), the IoT generates huge volumes of data that can improve decision-making in many areas, such as healthcare, manufacturing, and urban planning. Microsoft's (2023) description was about the different cloud-based big data architectures, such as Azure IoT Hub and Stream Analytics, which enabled scalable processing of IoT data streams.

Significantly, the use of IoT in continuous data provision opens many potential benefits, but it also opens doors to many critical challenges. The IoT devices usually produce unstructured or low-quality data, so significant cleaning and transformation will have to go through the long data wrangling process (Kandel et al., 2011). Without this step, the analysis comes out misleading or invalid. One of the major concerns is security, as many IoT devices do not get appropriate encryption and are therefore prone to cyberattacks (Roman, Zhou & Lopez, 2013). Large, scalable IoT systems also imply a lot of ethical dilemmas, particularly on issues of data ownership, consent, and surveillance (Zuboff, 2019), as to how much people generally do not know about the amount of data collected about them. 

Henceforth, the whole vision of the IoT cannot become a reality without securing the ethical and well-managed data pipelines in the organizations. Most importantly, good governance policies and investments in data wrangling tools and expertise should be put in place to ensure data accuracy, compliance, and meaningful outcomes.


References
Huxley, C. et al. (2020) Data Wrangling in the Era of Big Data: The Role of Automation and Human Insight. [Course material].

Kandel, S. et al. (2011) ‘Research directions in data wrangling: Visualizations and transformations for usable and credible data’, Information Visualization, 10(4), pp. 271–288.

Microsoft (2023) Big data architectures. Available at: https://learn.microsoft.com/en-us/azure/architecture/databases/guide/big-data-architectures (Accessed: 4 May 2025).

Roman, R., Zhou, J. and Lopez, J. (2013) ‘On the features and challenges of security and privacy in distributed Internet of Things’, Computer Networks, 57(10), pp. 2266–2279.

Zuboff, S. (2019) The Age of Surveillance Capitalism. New York: PublicAffairs.

### Unit 2 Introduction to Data Types and Formats <a name="unit2"></a>
In this unit, we covered the various types of data and how they are structured, and why that matters when dealing with them. I have been familiar with file formats such as JSON and CSV files, but in terms of storage or access I have never given thought as to how they might differ. Breaking down these files into structured, semi/quasi-strucuted, or unstructured data has given me a sense of how flexible these formats are. I spent some time re-reading chapters 3 and 6 of the McKinnery textbooks and running the sample Python code provided,  which helped give further clarity on how things behave differently when you manipulate data. I also got a better understanding of how XML is organized, something I had once spent time on in my Undergrad but have since forgotten. 

One of the most interesting takeaways of this unit was learning how APIs function. I have been exposed to APIs in the past, but this unit gave me more time to see the role it plays in moving data between different systems and formats. By the end of this unit, I feel a lot more confident in the "why" behind various data formats. I have a better understanding of how Python handles these datatypes and how it compares to other programming languages I have used in the past. 

### Unit 3 Data Collection and Storage <a name="unit3"></a>

This week's unit delves into web scraping. I followed the example provided from <a href="https://realpython.com/beautiful-soup-web-scraper-python">realpython.com</a> and created a sippit of code that searches for the phrase "data scientist" on Wikipedia. This exercise helped me go from theory to practice, creating more confidence in not just pulling data in Python, but parsing it into structured files.
I analyzed the various collection methods: APIs, scraping, and crowdsourcing, and by weighing the multiple approaches to understand the choice of where to store the output (JSON, XML, etc.) is more than a format decision. 
For my unit 3 activity, I chose to scrape the phrase 'data scientist' from a Wikipedia page utilizing Beautiful Soup and Requests libraries. 

A link to this activity can be found here: [Unit3](https://github.com/matilda-nilsson/matilda-nilsson.github.io/blob/main/assets/css/BD/Unit3.ipynb)

I thoroughly enjoyed this process. It let me explore and truly "play around" with various code snippets. I find that more hands-on approaches to programming will always be superior to textbook reading and chapter reviews.

### Unit 4 Data Cleaning and Transformation <a name="unit4"></a>

Exploring the techniques and methods of data cleaning this week gives a critical understanding to how data design and the process of automation works. The ability to clean and transform data effectively by following the data pipeline as a guide has given me the neccessary tools to creating an atumoated process. 
For this week's exercise, we used this dataset by Jackie Kazil. This work is referenced in ‘UNICEF’s Child Labor datasets taken from the Kazil & Jarmul, 2016.'
After I created a cleaned version of the data, I continued exploring the dataset by summarizing some statistics on the data itself, as well as checking for remaining missing values. In the future, I think it would be fun to explore this data further with some visuals using a dashboard format, as I have done in previous projects.

A link to my exploration can be found here: [Unit4](https://github.com/matilda-nilsson/matilda-nilsson.github.io/blob/main/assets/css/BD/Unit4Cleaning.ipynb)

### Unit 5 Data Cleaning and Automating Data Collections <a name="unit5"></a>

Unit 5 builds upon the previous week's UNICEF data, this time diving deeper into the automation of data cleaning. This unit has introduced the idea of scripting processes that can handle multiple files across different formats, which differs from last week's singular cleaning of a scalable and production-ready file. 
Working with the same repository, I started to think beyond the single DataFrame and instead build a pipeline that could loop through files, standardize column names, handle missing values, and save clean outputs that would be ready for analysis. 

My key takeaways from this unit are that automation isn't just about convenience, it's also about reducing error and consistency.

### Unit 6 Database Design and Normalisation <a name="unit6"></a>

This unit shifts the focus from raw data to how that data is structured and stored through relational database design. A big part of this week was learning how proper cleaning and formatting of data directly supports building reliable databases. I spent time understanding how relational databases are constructed, why key fields are essential for linking different tables, and how normalization plays a role in reducing redundancy and improving efficiency.

I also explored some of the core concepts and terminology used in database architecture, like primary keys, foreign keys, and relationships between entities.
A highlight of this unit was working on our group project, where we collaborated to outline the structure for a MySQL database and the concept of ZeroTrace, our group's idea of an accessibility tool form for those who need it. It was a hands-on way to apply what we were learning, and it really helped reinforce the importance of planning before building. 

Our report on ZeroTrace can be found here: [Developmental Team Project](https://github.com/matilda-nilsson/matilda-nilsson.github.io/blob/main/assets/css/BD/DevelopmentTeamProject-BigData.pdf)

### Unit 7 Constructing Normalised Tables and Database Build <a name="unit7"></a>
This week I got to utalize skills I have already honed in from my work as a lead data scienctist within my career. We were given an un-normalized table and asked to break it down into 1NF, 2NF, and 3NF (first, second, and third normal form). This task was easy for me as I do a lot of normalization tasks within my daily scope of work. I did enjoy thinking about normalization in terms of students, teachers, and courses instead of a more cooporate setting. Next, we were tasked with creating a database build for the tables we had normalized. This step was smooth and unchallaging and did not take much of my time, I used PostgresSQL as it is what I am the most confident in and utalized PGAdmin to completete the query work. 

Here is a link my SQL file: [Data Build](https://github.com/matilda-nilsson/matilda-nilsson.github.io/blob/main/assets/css/BD/UNIT7Databuild.sql)

Here is a PDF of my normalization task: [Normalization Task](https://github.com/matilda-nilsson/matilda-nilsson.github.io/blob/main/assets/css/BD/UNIT7Normalization.pdf)

As well as an image of the completed final table being queried on my local environment. 
<img width="791" height="595" alt="Unit7DataBuildPIC" src="https://github.com/user-attachments/assets/041b8c5c-6aa9-4ca1-8936-7a01ffb26ede" />

### Unit 8-10 Comparing Compliance Laws <a name="unit8"></a>
In the EU under Article 5 and 32 of the GDPR, personal data must be processed in a secure and appropriate way. Meaning encryption and pseudonymization are essential to protect confidentiality. These measures must also be visible and proactive in order to reduce the harm of data loss or data leaks. 

In the United States where I reside, there are no national rivacy laws like those under the GDPR, but in states like California there are regulations through the CCPA/CPRA. These regulations require buisnesses to implement "reasonable security" based on the company size and practices. These rules fall very short of the same standard that is met in the European sector. While data breaches open happen, the GDPR requires testing and risk-based assessments, while in the state where I reside there are no such regulations. This means data breaches are often met with liability charges in the court of law. The GDPR spins an expectation that is privacy and data centric, and it aligns with Privacy By Design, an international effort advocating for privacy-focused engineering from the start. 

While I hope to one day reside in a place where privacy is encouraged and endorsed, the federal government does not currently meet such standards in the United States. 
European Union, 2016. Regulation (EU) 2016/679 of the European Parliament and of the Council of 27 April 2016 (General Data Protection Regulation). Official Journal of the European Union, L119, pp.1–88. Available at: https://gdpr-info.eu/art-32-gdpr/ [Accessed 15 July 2025].

Information Commissioner's Office (ICO), 2024. Principle (f): Integrity and confidentiality (security). [online] ICO. Available at: https://ico.org.uk/for-organisations/guide-to-data-protection/guide-to-the-general-data-protection-regulation-gdpr/principles/integrity-and-confidentiality-security/ [Accessed 15 July 2025].

California Legislative Information, 2023. California Consumer Privacy Act (CCPA) as amended by the California Privacy Rights Act (CPRA). [online] Available at: https://leginfo.legislature.ca.gov/ [Accessed 15 July 2025].

Singh, J. and Cobbe, J., 2019. Privacy rights and obligations in data access frameworks: Problematising data subject access and portability rights. arXiv preprint arXiv:1905.13005. Available at: https://arxiv.org/abs/1905.13005 [Accessed 15 July 2025].

Bloomberg Law, 2024. State Privacy Legislation Tracker. [online] Bloomberg Law. Available at: https://pro.bloomberglaw.com/insights/privacy/state-privacy-legislation-tracker/ [Accessed 15 July 2025].

WP Legal Pages, 2024. Pennsylvania Consumer Data Privacy Act (PCDPA). [online] Available at: https://wplegalpages.com/blog/pennsylvania-consumer-data-privacy-act-pcdpa/ [Accessed 15 July 2025].

### Unit 10 Application Programming Interfaces for Data Parsing  <a name="unit10"></a>

APIs play a pivotal role in parsing data and enabling communication between programs. Whether it's scraping JSON from a web service or passing structured XML between systems, APIs act as a connector between the applications. We looked into how APIs are used for data parsing and inter-process communication, especially in Python where modules like 'requests' 'http.client' or external packages like 'Flask' and 'FastAPI' make it more streamlined. But ease of access also pose more of a security risk; the more open an API is, the more careful a developer has to be in regards to authenticated users, sensitive data, and to fight misuse. 

I also learned about the most common security practices like API key management, token-based authentication, HTTPS enforcement, and data validation. Each practice plays a vital role in how API can fight to not expose the system or data to any risk.

I decided to draft a security specification outline based on a publicly available API called OpenWeatherMap API. The security requirement specification is listed below: 
A link to my draft is found here: [OpenWeatherMap Idea](https://github.com/matilda-nilsson/matilda-nilsson.github.io/blob/main/assets/css/BD/Unit10APIIdea.pdf)

### Unit 11 DBMS Transaction and Recovery <a name="unit11"></a>
The Grandfather-Father-Son (GFS) backup system is a smart way to manage backups without using too much storage. It works by saving daily backups (sons), weekly ones (fathers), and a monthly version (the grandfather). These are rotated on a schedule, which means you don’t need to do a full backup every single day—saving both time and space. This is especially helpful for large databases where daily full backups would be too heavy to handle. 

While GFS is not as up-to-the-minute as real-time or continuous backup systems, it’s a reliable method for long-term storage and disaster recovery. It’s easy to set up, and still gives plenty of restore points if something goes wrong. For many organizations, it’s a good balance between efficiency and protection.

Also on this unit, I learned how databases handle transactions and prevent data loss when things go wrong. We looked at the ACID principles: Atomicity, Consistency, Isolation, and Durability. Which make sure transactions are processed safely and reliably. I also explored how databases manage multiple transactions at once through interleaving and scheduling, and how checkpoints and transaction logs help recover data after a system failure. 

By the end of the unit, I understood how a transaction manager keeps everything running smoothly and ensures that every transaction is either fully completed or fully undone.

Also in this unit, we completed a final assignment expanding on the group project from Unit 6. I provided an executive summary, which can be found here: [Executive Summary](https://github.com/matilda-nilsson/matilda-nilsson.github.io/blob/main/assets/css/BD/ExecSummary_NILSSON.pdf)

As a personal evaluation of Unit 6 vs. the final project in Unit 11, I found that expanding on the thoughts and ideas individually let me expand a lot more on things I struggled to share in Unit 6. I did not enjoy the group assignment in the beginning, but finalizing this project now at the end of this module has let me explore more with the learning materials along with the initial project design. Overall, I am satisfied with my final product, and wish I had put more effort into the initial group effort to finalize a proper submission in Unit 6.

### Unit 12 Final Reflection <a name="reflection"></a>

Over the course of this module, I have developed a much deeper and more practical understanding of data wrangling. From the initial stages of data extraction and parsing to the complexities of cleaning, transformation, and secure storage, I have been exposed to a full workflow that reflects real-world data challenges. Working with tools like Python, SQL, Beautiful Soup, and APIs has allowed me to apply theoretical knowledge in practical ways. More importantly, I’ve discovered that I really enjoy the problem-solving nature of data wrangling and feel that I’ve found a niche within data science that I want to pursue further.

One of the biggest highlights of the module for me was the collaborative database project in Unit 6. As a team, we worked to build a logical relational database and document its structure and design. This required not only technical planning but clear communication and shared decision-making. We had to think through how best to organize the data, how tables would relate, and what constraints were necessary to protect the data's integrity. I contributed by outlining the normalization process, reviewing relational keys, and helping refine the final entity-relationship diagram. This collaborative project helped me gain more confidence in my skills and a better understanding of how databases are used in real business environments.

I started this module with a solid understanding of data processing, particularly in Python. However, I lacked confidence in branching out into areas like working with more complex file types, structuring data for scale, or integrating legal considerations like GDPR compliance. Throughout this course, I was able to work hands-on with a variety of file formats such as JSON, XML, and CSV, and using Python scripts to parse, clean, and convert these into usable datasets. I especially enjoyed working with web scraping tools like Beautiful Soup and Requests, where I learned to automate data extraction and transform it into structured formats that could then be stored or analyzed. This felt like a big step forward in becoming more confident with automating parts of my workflow and managing larger and messier datasets.

Throughout the module, I also contributed to class discussions and group chats around topics like API security, data governance, and compliance. I found these conversations helpful in contextualizing the technical work within real-world responsibilities. For example, our discussions around GDPR made me reflect on how privacy laws (or lack thereof) impact the work I will be doing, especially since I live in Pennsylvania in the United States, where data privacy protections basically nonexistent. It made me realize how important it is to not just build efficient systems, but responsible ones too.

One part of the course that really stood out to me was the section on transaction processing and disaster recovery strategies in Units 10 and 11. The Grandfather-Father-Son backup system was something I had heard of before but had never explored in detail. It was interesting to revisit it through the lens of large-scale databases and to see how important redundancy, recovery points, and rollback mechanisms are in maintaining data integrity. I especially appreciated learning about ACID properties: Atomicity, Consistency, Isolation, and Durability; how they form the backbone of transactional reliability. These concepts helped connect everything I had learned earlier in the module, tying together the processes of data parsing, transformation, and storage with the need for long-term resilience.

The biggest shift in my mindset came during Units 5 and 7, when we focused on automation and normalization. Unit 5’s exercise on automating the cleaning of UNICEF survey datasets was both frustrating and rewarding. I ran into several issues dealing with malformed CSVs and inconsistent column naming, which at times left me questioning whether I was making progress at all. But once I successfully completed a script that could loop through multiple files, clean the data, and output clean, usable formats, I had a moment of real pride. That feeling—of turning confusion into something organized and functional—showed me how rewarding this field can be. It also helped me appreciate the often-invisible work that goes into data infrastructure across industries.

Unit 7’s focus on normalization made me think much more critically about how data is structured at the source. Designing for scalability, rather than short-term convenience, became a recurring theme. I learned how important it is to think about relationships between data entities early on and to build systems that are adaptable. This reinforced the idea that data wrangling isn't just a technical task, but a design challenge.

The lectures on transaction logs, rollback strategies, and checkpointing also helped round out the picture for me. By the end of Unit 11, I had a much clearer view of how all the pieces, collection, cleaning, modeling, and storing, fit together into a complete pipeline. Understanding that data systems need to not only function efficiently, but also recover from failure gracefully, has given me a more holistic perspective on data engineering.

Looking ahead, I feel far more confident in approaching real-world data projects. I now understand how to build a well-structured database schema, write robust Python scripts for parsing and cleaning, and think critically about issues like system failures and long-term data durability. I want to continue learning more about API design and deployment, particularly through frameworks like FastAPI. While this module introduced the basics of configuring and securing APIs, I’d like to explore building and deploying my own endpoints and implementing token-based authentication systems. Ethical data handling and legal compliance have also become more personal to me. The lack of comprehensive privacy protections in my state has made me more aware of the responsibility data professionals have in designing systems that prioritize user privacy—even when laws don’t require it. Learning about GDPR, privacy by design, and secure API access has inspired me to dig deeper into this area, and to bring those values with me into my future work.

Finally, this module has given me not just technical knowledge, but also a clearer sense of identity as an emerging data scientist. I’ve learned to reflect more on how I approach problems, how I collaborate with others, and how I adapt to unfamiliar challenges. I now have a portfolio of scripts, visualizations, and reflections that document my progress and can serve as both evidence of my learning and a launchpad for further development. 

