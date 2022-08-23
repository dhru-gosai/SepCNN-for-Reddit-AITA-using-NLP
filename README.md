# SepCNN-for-Reddit-AITA-using-NLP
Deep learning solution for moral decision-making using Reddit AITA data via web scrapping and natural language processing (NLP)

Usually, there is certain amount of hesitance when it comes to letting the machines make decisions – be it customer service with a bot or using an automated car. Humans would rather rely on humans for support. One such community support network system is observed on Reddit, a platform where people can come and share their opinions and seek feedback. A sub-reddit called ‘Am I the Asshole?’ (AITA) provides users opinions on whether the decision they made was ethical one or not.

A user labelled metadata with years’ worth of information means a perfect opportunity to create a machine learning algorithm that could predict whether a decision made by someone was ethical or not. This research paper explores the Reddit metadata and extracts relevant information with the use of web scrapping. Employing the NLP methods, a deep learning neural networks algorithm is created to predict whether the post-verdict should have been "You're The Asshole" or "Not The Asshole”.

##Steps involved to create ML model via web crawling and NLP:
1. Web Crawler
    - Using URL handling modules (urllib) request and API to extract data
2. Data Pre-processing
3. Data Wrangling
    - vocabulary augmentation
    - Generation of sample configuration from the initial datasets:
        - The Post Verdict is a trait (observation of a variable) of the sample.
    - Generation of sample subset:
        - reference any sample distributions, biases and or data limitations
    - Create test and training subsets
        - reference any sample distributions, biases and or data limitations
4. Exploratory analysis
5. Data sub-setting
6. Defining CNN hyperparameters
7. CNN implementation and result visualisation
8. Model Evaluation
