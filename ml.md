## Machine Learning

### Jump to Section

- [Unit 1: The 4th Industrial Recolution](#unit1)
- [Unit 2: EDA Introduction](#unit2)
- [Unit 3: Correlation and Regression](#unit3)
- [Unit 5: Jaccard Coefficient Calculation](#unit5)
- [Unit 6: Developmental Project](#unit6)
- [Unit 7: Perceptron Activites](#unit7) 
- [Unit 8: Gradient Cost Function](#unit8) 
- [Unit 9-10: Legal and Ethical ANN Applications](#unit9)
- [Unit 11: Individual Development Project on CIFAR-10 ](#unit11)
- [Personal Reflection](#reflection)


### Learning Outcomes
- Articulate the legal, social, ethical and professional issues faced by machine learning professionals.
- Understand the applicability and challenges associated with different datasets for the use of machine learning algorithms.
- Apply and critically appraise machine learning techniques to real-world problems, particularly where technical risk and uncertainty is involved.
- Systematically develop and implement the skills required to be effective member of a development team in a virtual professional environment, adopting real-life perspectives on team roles and organisation.

### Unit 1 - 3 The 4th Industrial Revolution <a name="unit1"></a>

The advancement of Industry 4.0 through artificial intelligence (AI), automation technology, and big data analytics has transformed social media platforms, internet accessibility, and data science disciplines. While AI personalization on social media platforms increases user engagement, it also generates ethical issues about the spread of misinformation and the protection of personal data (Schwab 2016). AI-driven speech-to-text systems enhance inclusivity, while data science predictive analytics create more accurate decision-making capabilities.A significant failure of Industry 4.0 occurred during the Meta outage on October 4th, 2021 when Facebook, Instagram and WhatsApp were offline for six hours. A configuration error in backbone routers triggered the incident which blocked global communications and disrupted commerce (Meta, 2021). The outage resulted in businesses losing advertising income and the value of Meta stock fell by 5%, which decreased Mark Zuckerberg’s wealth by $6 billion according to The Guardian (2021). The outage demonstrated how centralized digital systems pose significant risks and underscored the importance of developing decentralized and robust systems (Cloudflare, 2021).

The evolution of Industry 4.0 demands a careful balance between technological innovation and ethical standards along with infrastructure strength. It is essential for organizations to channel their resources into adaptive technologies and crisis management strategies to lessen technological dependence risks.

References: 

Cloudflare (2021) October 2021 Facebook outage. Available at: https://blog.cloudflare.com/october-2021-facebook-outage (Accessed: 8 February 2025).

Meta (2021) Outage report. Available at: https://engineering.fb.com/2021/10/04/networking-traffic/outage (Accessed: 8 February 2025).

Schwab, K. (2016) The Fourth Industrial Revolution. Geneva: World Economic Forum.

The Guardian (2021) Facebook outage: What went wrong?. Available at: https://www.theguardian.com/technology/2021/oct/05/facebook-outage-what-went-wrong (Accessed: 8 February 2025).

### Unit 2 EDA Introduction <a name="unit3"></a>
In this unit, we were able to perform EDA on the Auto-MPG dataset. I set out to identify missing values, estimate skewness and kurtosis. I created a heat correalation map along with various other visualizations of parameters to analyze. This excerise felt like a great introductory point as it allowed me to play around with various plotting techniques and replace some categorical values with numerical values to experiment with the effects in outcome. 

![Unit2HeatMap](https://github.com/user-attachments/assets/bce8a8d4-dd52-4243-9828-95c5980cd953)
![Unit2Scat](https://github.com/user-attachments/assets/4a2716fd-3aa4-4c59-9910-c74cd4846a75)
![Unit2Scew](https://github.com/user-attachments/assets/ad0c66f0-24b6-419e-b1a2-a35dfb2c3d5b)

### Unit 3 Correlation and Regression <a name="unit3"></a>
Using Jupyter notebooks, in this unit, we modified parameters and observed how changes affect data correlation and regression. This unit provided another foundational layer of understanding to various types of regressions: Polynomial, Multiple Linear, Linear, and Pearson Correlation. These exercises were more challenging to me, I kept confusing the multiple techniques and doubting my understanding of the unit concepts. My understanding was more solidified thanks to the visualizations generated through testing. 

Linear Regression experiment: Adding random noise to our data changes the regression model. 
![Unit3Linear1](https://github.com/user-attachments/assets/47ef86e1-4d28-4350-b7a2-cd175bba39d4)
![Unit3Linear2](https://github.com/user-attachments/assets/f6e51b88-34a5-4dff-bbc2-e27686b4c8fa)

Pearson correlation experiment: Changing covariance highly affects the data in this model. 
![Unit3Pearson1](https://github.com/user-attachments/assets/2b7afaa5-9a88-4e0d-ab5b-cfee240b119d)
![Unit3Pearson2](https://github.com/user-attachments/assets/4564147f-9901-467a-aa8e-7ed0065c1683)

### Unit 5 Jaccard Coefficient Calculation  <a name="unit5"></a>
Unit 5 we learned how to calculate the Jaccard Coefficient. 

<img width="559" alt="Unit6Jac" src="https://github.com/user-attachments/assets/d57c3e73-4903-4112-910d-2cbfb225b45d" />

## Unit 6 Development Team Project  <a name="unit6"></a>
This unit was dedicated to our submission of our Development Team Project. We were tasked to complete a data analysis report and a peer review of our team members. 
This project challenged me to take more initiative and lead in scheduling meetings and becoming more of a team leader. Confidence during team discussions is also something I have to work on, and to approach each challenge with an open mind rather than what I believe is the ideal solution. My greatest strengths in this team project was my literary skills and willingness to cooperate, which both carried the team greatly during the report writing and summarization needed. Our team was the most productive during our discussions, setting realistic goals and assigning tasks to each member in a realistic time frame. Our greatest weakness was a certain pessimistic outlook on the perceived difficulty of the task, while I believed it was a reasonable project. 

The link to our report can be found here: [Project Report](/assets/css/ml/ml_report_u6.pdf)


## Unit 7 Perceptron Activites <a name="unit7"></a>

Utilizing our new knowledge on Perceptron, this unit explored changing input values and weights to result in neuron activation. But when the inputs remain the same and only the weight changes, neuron activation does not happen. 

## Unit 8 Gradient Cost Function <a name="unit8"></a>

What is the minimum cost with minimum iterations? In this unit, we had an exercise of reaching that goal. The original set had 100 iterations with a learning rate of 0.8,  the decrease had 50 iterations and a learning rate of 0.7

## Unit 9 - 10 Legal and Ethical ANN Applications <a name="unit9"></a>
The increase in use of AI has grown exponentially in the last decade, and even more in the last couple of years. Despite its many benefits, unregulated anything can lead to many ethical concerns. The lack of transparency in training data regarding AI remains a huge issue (European Council, 2024). While bringing AI into our daily lives is proving numerous advantages in customer experience and in the medical field of diagnostics. The energy industry has also started to utilize AI to boost efficiency, while banking systems are improving their fraud detection and security with AI (Google, 2024).

AI does, however, cause concern for quality bias, since poorly cleaned data can lead to harmful results. The issue is greatly exacerbated without safeguards and regulations (European Council, 2024). As AI technology spreads and becomes increasingly available in every industry and individual's lives, the responsibility of its impact will fall on lawmakers and ethical discussions of where AI belongs and, more importantly, where it does not. 

Reference list: 
Arena, C. (2022). 7 Disadvantages of Artificial Intelligence Everyone Should Know About. [online] Liberties.eu. Available at: https://www.liberties.eu/en/stories/disadvantages-of-artificial-intelligence/44289. 

European Council. (2024). Benefits and risks of AI. [online] Available at: https://www.consilium.europa.eu/en/policies/benefits-and-risks-of-ai/#benefits. 

Google (2024). Applications of Artificial Intelligence (AI). [online] Google Cloud. Available at: https://cloud.google.com/discover/ai-applications. 

## Unit 11 Individual Development Project on CIFAR-10 <a name="unit11"></a>
This unit was centered around an individual development project. 

A full presentation is available here: <a href="https://docs.google.com/presentation/d/1rwIDxzmcRM_dNbesnWP_qWevh05rTUAU-s1vXqhEw5w/edit?usp=sharing" target="_blank">NN Presentation</a>

A transcript of the video presentation on the project slides is available here: [NNProject_Transcript_Nilsson.docx](https://github.com/user-attachments/files/19826590/NNProject_Transcript_Nilsson.docx)

## Individual Reflection <a name="reflection"></a>

  Starting this module was exciting, as I had only recently begun playing around with what could be done with large language models such as DeepSeek and ChatGPT. The latter two intrigued me and opened my eyes to how much can be done with machine learning in real-world applications. I couldn't wait to move past using AI and understanding how it works. The first three units were excellent at establishing the ground rules of machine learning, providing us with a solid base in vocabulary, concepts, and history. I especially enjoyed how early on we were taught about the ethical implications of machine learning. Having both the risks and possibilities that come with this type of powerful technology seemed essential, and these discussions brought up crucial questions of responsibility, bias, and long-term impact.
  
  Discovering how errors in model training or algorithm conception could snowball into significant real-world consequences opened my eyes. For instance, a seemingly tiny bias in the data could spiral into discriminatory practices on a mass scale. These kinds of conversations made the subject feel real and relevant—like we weren't just learning about a technical subject, but acquiring a skillset that could shape, help, or harm people depending on how it was applied. It provided the work with a sense of ethical importance that I hadn't expected to approach the course with.
The course truly came to life for me when we progressed into Units 2 to 5, where we learned practical skills like data preprocessing and exploratory data analysis (EDA). These techniques were used to bridge the gap between raw data and meaningful insight. It was within these units that I felt the tangible benefit of what we were doing—detecting patterns, cleaning dirty datasets, and preparing data for analysis. While I completed the exercises given with some success, I soon realized how much more complexity there was to learn. For instance, I struggled to balance full preprocessing with the risk of unintentionally distorting or skewing the dataset.

  Regression and parameter tuning in Units 3 and 4 had a steep learning curve. The terminology grew more technical, and the reading material took on a more mathematical and statistical basis than I originally possessed. I began to lose some confidence, wondering if I was truly suited for this profession. But I used this as a challenge and devoted additional time to reviewing lectures, reading additional materials, and participating in online forums and communities to solidify my knowledge. Over time, things that at first seemed intimidating—like the impact of making a small change in regularization or how a model was sensitive to specific sets of parameters—slowly became more understandable.

  Unit 5 dealt with unsupervised learning and clustering, and this quite unexpectedly turned out to be one of the module's highlights for me. Learning about clustering data with algorithms like K-means and measuring results with Jaccard coefficients felt like science fiction. It was as if I could now begin to see the structure in data that had previously appeared to be random. Mathematical ideas of clustering were challenging, and I struggled with some of my personal math-related anxieties. All that aside, I was pleased with how far I was able to come in seeing the practical applications of these methods in the real world and how they could be applied, say, to marketing segmentation or anomaly detection.

  Unit 6 was comprised of our group project, which was one of the more complicated experiences of the course, not only intellectually, but socially. Although we turned out to produce a well-deserved project, it was difficult to work with certain team members due to poor teamwork and communication. I volunteered to write the final project report and was appalled when I found that some of my work was being erased without any regard. This generated a lot of tension and frustration. Although the issue was never actually resolved, the experience also provided me with lessons in teamwork, boundaries, and how essential respectful communication is in a working environment. Through the interpersonal failures, I also learned a great deal from the dataset we worked on and gained practical experience utilizing the tools and concepts of earlier units.

  The following two units, Units 7 and 8, dealt with artificial neural networks (ANNs) and the mathematics of multilayer perceptrons. I began to feel the weight of my own expectations during these weeks. I wanted to learn everything at the speed of light, but again, the learning curve was too much for me. Fortunately, the hands-on experiments with perceptrons brought a sense of clarity, making the basic concepts concrete by trying them out. Again, there was the question of ethics at issue—this time in terms of the application of ANN to use in predictive policing and medicine. I enjoyed seeing these debates discussed, as it challenged us to not only discuss how a model works, but whether it should work at all.
Unit 9, on facial recognition technology, was arguably the most impactful personally of the entire course. I had already been amazed by the ease of facial recognition use in everyday life, such as my phone unlocking itself. But this unit opened my eyes to the broader implications—surveillance, privacy invasion, racial profiling, and potential misuse by authorities. It was a tension between my prior experience and new learning, and it altered my perspective significantly.

  Units 10 and 11 covered model evaluation and performance tuning. These were applied to our final individual development project, where we were required to design, train, and tune an object detection model using the CIFAR-10 dataset. For testing purposes, I decided against using pre-trained models but built mine from the ground up. It required many iterations and careful parameter fine-tuning after many iterations for me to ultimately reach an accuracy level of 86% while keeping overfitting to a minimum. It was a very personal achievement, one that was something of a watershed moment when everything learned in preceding modules came together in something I had built myself and could professionally critique.
As we came to the final unit, I was increasingly interested to find out where the trend for machine learning was heading. I began to read research papers and articles on future trends, from reinforcement learning to AI ethics for generative AI. The latter half of the module was reflective for me. I began to ask not only what I had been studying, but how I might continue to move forward on my own through personal projects, experiments, and further reading.

  In conclusion, this module has offered far more than just technical knowledge. It has pushed me to reflect critically, collaborate under pressure, and develop resilience in the face of self-doubt. I’ve gained a foundational skill set in model development, evaluation, and ethical awareness. But I’ve also realized the importance of lifelong learning in this ever-evolving field. In the future, I will keep building projects for my portfolio, practice my data visualization, and take a refresher mathematics course to solidify my knowledge. I'm looking forward to the future, not only of machine learning, but of where I fit in it.


