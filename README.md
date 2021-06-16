# Exploration of Danish humanitarian NGO's during Covid-19 

*By Nadia Schouw, Victoria Hjørtoft and Sofie Andersen*

Exam numbers in Digital Methods: 13, 24, and 29

Exam numbers in ASDS II: 6, 12, and 18


**Characters in total: 47,994** 

# 1 Introduction (29, 24, 13)
Humanitarian non-governmental organizations (NGOs) handle aid, communicate about crises and provide support for vulnerable people, criticizing injustice and fighting for social and humanitarian sustainability. The NGOs are playing an important role in society affecting political agendas and setting the public debate (Schäfer 2012). In a time of crisis, where the Covid-19 pandemic rages and more people are distressed, the NGOs are facing new emergencies embedded in all previous existing ones. Consequently, the NGOs must fight for their agendas, while also being financially challenged due to fewer lucrative activities and more people in need of help. This fight has partially taken place on social media, as these platforms play an increasingly important role in political communication including both agenda setting, decision making and public dialogue (Yang et al. 2016). In the context of these new challenges, we will in this paper map the public debate of the Danish humanitarian NGOs across social media platforms during Covid-19 to understand how the NGOs communicate and interrelate under these circumstances by making an empirical quanti-qualitative in-depth analysis.

# 2 Research question (29, 24, 13)
*What dominate the Danish humanitarian NGOs’ focuses in their communication on social media platforms during the Covid-19 pandemic and how do the NGOs interrelate on social media during this time?*

## 2.1 Problem statements (29, 24, 13)

**Digital methods**
* What is prominent in the Danish humanitarian NGOs communication across different social media platforms and how are the NGOs thematically clustered in relation to each other?
* Based on different types of network analysis, what is the interrelations between Danish humanitarian NGOs on different social media platforms?

**ASDS II**
* Which topics are present in the communication of the Danish humanitarian NGOs during Covid-19 on Twitter?
* What classifies the Danish humanitarian NGOs’ communication on Twitter during Covid-19?


The problem statements will be used throughout the paper to investigate the overall research question. Notably, the questions will not be answered in chronological order, but will serve as an overall framework.

# 3 State of the art (29)
NGOs are characterized by their work and focus on a wide range of areas including health, education, human rights and corporate social responsibility (Amstrong & Butcher 2017; Ryfman 2007). NGOs act as mediators between scientific expertise and the public and rely heavily on strategic communication by news coverage and public attention to accomplish their goals (Ladle et al. 2005; Schäfer 2012). Past research has focused on the area of climate change, environmental communication and framing, by exploring how the NGOs use social media and interrelate with each other, as well as mobilize support in time of crises (Takahashi et al. 2015; Allan & Hadden 2017; Vu et al. 2020; Lück et al. 2018).

Further, in the context of Covid-19, Blok et al. (2020) have demonstrated similarities and differences in how Scandinavian, climate-active environmental or green NGOs engage in framing their work during the initial phase of the coronavirus pandemic. Their research shows a gap investigating Covid-19 in relation to human rights and how the humanitarian NGOs frame their communication in time of a worldwide crisis. This perspective has not yet been investigated in a Danish context, amongst others.

We define humanitarian aid and development as being built on the principles of humanity, neutrality, and impartiality, with the objective of providing aid and assistance to people in need, enabling people to lead long, healthy, educated and fulfilling lives. Hence, creating positive social impact and long-term effectiveness of developing aid (Neumayer 2012; Haavisto & Kovacs 2013). Thus, humanitarian development without being sustainable cannot be true human development (Neumayer 2012), since sustainable development is defined by the United Nations as “meeting the needs of the present without compromising the ability of future generations to meet their own needs” (WCED 1987).

The work of the humanitarian NGOs has changed with the entry of digital technologies and social media, as it has provided new means of communication, conveyance, collaboration, and cultivation amongst interconnected networks of people, communities, and organizations (Caliandro 2018). Studies have explored how humanitarian NGOs utilize social media platforms as an instrument to provide knowledge, to engage people to act in situations of crisis (Amstrong & Butcher 2017; Wukich & Khemka 2017). Dereli et al (2019) analyze how The International Federation of Red Cross uses Twitter and which topics they focus on. They use quantitative methods, such as word labeling, topic models, and sentiment analysis based on machine learning classification algorithms, which we are inspired by, when exploring the communication and interrelations between the Danish humanitarian NGOs in the context of Covid-19.

# 4 Overall method-plan (24)
In this paper, we have an inductive and exploratory approach to generating understandings from data analysis. Hence, we start with a problem description that is aiming at the social processes and social structures of the humanitarian NGOs communication on social media throughout the global pandemic crisis of Covid-19. Our research and analysis approach can be labeled as symphonic social science, in terms of our data, methods, and theoretical interpretations (Halford & Savage 2017). We work with multiple empirical data sources, both deep and wide. This means that our data collection and analysis take place as a simultaneous action, thus making the sampling process theoretically saturated and critically assessed (Carlsen & Ralund 2017; Halford & Savage 2017). Furthermore, we will be moving between qualitative and quantitative analysis, by combining the method of netnography with the tools of social network analysis and content- and natural language processing analysis (Munk 2019).

## 4.1 Sampling strategy (13)
We have collected two types of data. First, we have collected substantial observations in an online version of ethnographic fieldnotes, also termed netnography, in  an immersion journal, cf. Kozinets. The immersion journal contains recordings and reflections about the field and the actors (Kozinets 2019: 283ff) and is collected across social media platforms including Facebook, Twitter, Instagram, and LinkedIn, along with the organizations’ webpages. Second, we have collected a Twitter dataset with 12,139 observations containing the full population of tweets from the 30 identified actors in the period from 1st of January 2020 to 26th May 2021. This period was chosen since the Covid-19 virus was detected on 31 December 2019 and we argue that the content on social media would be seen in the light of Covid-19 starting here after (WHO 2021). The scraping is completed through Tweepy and the official twitter API. As we are only interested in the text data we removed emojis, URL’s, @mentions, special characters, numbers and hashtags, including lowercasing the text. After, we used the fasttext language detector only keeping Danish tweets (notably, the retweet networks presented later contain all tweets across languages). Fourth, we used the Danish lemmatizer Lemmy and removed stop words from the NLTK library including 41 self-identified stop words (App. 1).

Both datasets contain data on the same 30 NGOs, though only 27 of the NGOs are represented in the Twitter dataset due to no Twitter activity in the period for 3 of the NGOs. The NGOs are identified through a snowball sampling. The sampling started from the Danish fundraising Danmarks Indsamlingen, which is a yearly TV show collecting money for supporting 12 Danish humanitarian NGOs. Starting from looking at these 12 NGOs' cooperation and social media activity including following @mentions, retweets, comments and their use of hashtags, we have in an iterative process identified further 18 active NGOs. The strategy can be criticized as applying selection bias towards the sampling. However, looking at fig. 1, it can be argued that the original 12 NGOs cover different aspects of the humanitarian support field making it likely to discover new NGOs in different areas of the field.

**Fig. 1. Field areas of NGOs in Danmarks Indsamlingen**

Lastly, it should be noted that the 30 NGOs are not the exhaustive population of humanitarian NGOs in Denmark. Though we have tried to identify the field, we risk excluding the smaller and area-focused NGOs as these will not interact with the main field. Table 1 presents all the actors.
Table 1. 

## 4.2 Ethical considerations (29)
Throughout this paper, we have made several ethical considerations that we will present in this section. We chose to only focus on the NGOs’ social media profiles which is why we have anonymized the observations in our immersion journal, not mentioning any personal information. When scraping, we did in some cases include personal profiles, e.g., when scraping retweets, however, these are not included in the paper in a personal identifiable manner in relation to GDPR (Hoofnagle et al. 2019). We argue that the social media profiles belonging to the NGOs are publicly available since we can gain access to their posts without login in. Further, we also assume that the NGOs have published their content to be viewed and accessed publicly, making it ethically acceptable to scrape and note down their social media content. However, in some tweets, the NGOs also share personal stories including both personal and sensitive data. We assume that the NGOs are not sharing content without consent from the individuals. As this paper is conducted for research purposes, we find it ethically acceptable for us to include these types of posts in our data since we do not present the data in text, it is solely used as qualitative knowledge and as input data for our computational methods.

# 5 Netnography and qualitative analysis (24)
For this paper, we will be using the netnographic framework of Kozinets to gain deep and valuable insights into what the humanitarian organizations communicate about and how they interrelate (Kozinets 2019). Kozinets describes netnography as the synergy between the internet and ethnography. He includes several different procedural steps in his framework that we use as an inspiration and guideline for our netnographic approach. For this section, we will go through the relevant steps for this paper.

## 5.1 Method (13)
Our first step, called initiation, consisted of laying out our research focus, of humanitarian communication during a worldwide pandemic (Kozinets 2019: Ch. 5). The second netnographic step was to investigate data sites to find information about our focus, leading us to Danmarks Indsamlingen’s website, where we found the 12 initial NGOs. We immersed ourselves into the field of humanitarian NGOs by observing their communication, though we did not interact directly with the field by commenting, liking or posting with the purpose of not inferring ourselves in the communication (ibid). We started searching for the 12 NGOs at the most popular social media sites (Kozinets 2019: Ch. 8). Most of the NGOs have accounts on Twitter, Facebook, Instagram and LinkedIn. Consequently, these platforms became our starting point for scouting for relevant knowledge and more humanitarian NGOs (ibid). Through this process we ended up with 30 NGOs. The observations that were made in the searching and scouting process were saved and recorded in an immersion journal that is located on a One Drive provided by University of Copenhagen to ensure the security of our data (ibid) (App. 2). We chose to record our observations using an Excel file with a separate sheet for each NGO, a list of collaborations between NGOs and a sheet for other relevant observations. The fig. 2 shows the categories of observation.

**Fig. 2. Immersion journal categories**

 
We noted down general descriptions of our observations, the actual observations and additional information relevant for decoding and translating some of the findings (Kozinets 2019: Ch. 5). Further, we made room for reflection and analytical ideas though we did not go as much in detail as Kozinets suggests (Kozinets 2019: Ch. 10).

## 5.2 Analysis (29)
We prepared for analysis by collating, gathering and preparing our data (Kozinets 2019: Ch. 12). We began with an inductive coding process, where each researcher open coded a sub-set from the Twitter dataset and the immersion journal (261 tweets in total) (ibid). Each pool had an overlap, to ensure that all data were coded by two different researchers, creating intercoder reliability. Next, we combined our inductive codes in each dataset separately into pattern codes, by looking at similarities, patterns, and code combinations to be able to discover conceptual codes that can be used to answer our research question (ibid). We ended up with 22 different pattern codes for the subset of tweets, presented in fig. 3, and 10 different pattern codes in the immersion journal visualized in fig. 4.

**Fig. 3. Pattern codes from Tweets**

**Fig. 4. Pattern codes from Immersion Journal**

We see in the pattern codes that a lot of the content and observations are dominated by the following codes: Børn (children), Menneskerettigheder (human rights), Covid-19, support (emergency aid), socially vulnerable (and refugees), klima (climate), Conflict, and Politics. Interestingly, the pattern code Conflict emerged from our immersion journal but not from our tweets. This might be because our immersion journal includes observations across different social media platforms and as the noted observations are already subjectively processed by the researcher. Further, we see a larger number of emotional and activist stories being posted on Facebook, while the content on Twitter has a broader focus on politics opposed to Facebook (including Instagram and LinkedIn). We especially see this in the NGOs use of hashtags like #dkpol, #dkmedia, and #dkaid. This can be explained by Twitter often being used to communicate about politics, in a Danish context (Breslin et. al 2019). To further explore these pattern codes, we went through our data and qualitatively assessed which of the NGOs are focusing their communication on the different conceptual pattern codes. This qualitative assessment is visualized in fig. 5, where we have created an analogue positional map of how the NGOs are thematically clustered around the codes (Campagnolo 2020).

**Fig. 5. Analogue positional map**

This positional map shows us that some of the NGOs have a broad selection of focuses that they communicate about, such as Røde Kors who are communicating about children, Covid-19, conflicts, socially vulnerable, and support. On the other hand, we also see NGOs having a narrower focus in their communication, such as Repatriate the Children who talk about children and politics. What is also interesting is that not all NGOs communicate about Covid-19. It is mostly communicated about from NGOs that have a broad focus.

Through our immersion journal, we found that the NGOs make collaborations communicated on the different social media platforms. These collaborations can be understood as interrelations on social media platforms. Here collaboration contains shared statements amongst multiple NGOs, shared campaigns, events and demonstrations hosted by multiple NGOs and shared calls for legal action (App. 3). We traced these collaborations on all four social media platforms, amongst all 30 NGOs during our studied time period. We chose to visualize these collaborations in a visual network analysis (VNA) by using the computational program Gephi and the algorithm Force Atlas 2 (Decuypere 2020). The node size is based on in-degree. The blue nodes represent the initial 12 NGOs and the green nodes represent the NGOs that were further discovered through our netnography. The edges represent collaborations between the NGOs and are weighted, so thicker edges represent multiple collaborations. Further, the direction of the edges is presented clockwise, for example, Røde Kors has posted about collaborating with Blå Kors on LinkedIn, but there is not a collaboration posted from Blå Kors to Røde Kors. Lastly, the edges are colored based on what social media platform the collaboration was recorded from. The VNA is presented in fig. 6.

**Fig. 6. VNA**

The VNA shows that the collaborations are posted on Twitter more than 50% of the time, but that collaborations posted on Instagram are posted multiple times, hence the thick edges. Further we see that there is a region of NGOs that are central to the network, consisting of Red Barnet, Care Danmark and Mellemfolkeligt Samvirke (Decuypere 2020). Interestingly, we find that the 12 initial NGOs are more central in the network, while the NGOs discovered later are less central (App. 4). This indicates that the initial NGOs either have more important roles in the field or a screwed sampling. Multiple of the less central actors are smaller NGOs based on their number of followers, e.g Sæt dem Fri, and Blå Kors, however, we also see larger NGOs in the periphery as UNDP Denmark, but these are instead represented by smaller nodes due to a more international focus, whereas they do not collaborate a lot with the field.

## 5.3 Discussion (24)
Netnography helps to create deep data about our chosen subject, contributing to a deeper understanding of the NGO’s dominant focuses and interrelations on social media platforms (Kozinets 2019: Ch. 5).  Kozinets presents a number of steps for doing netnography, but this rigid approach might be constraining to some degree when setting up an explorative research design (Kozinets 2019). Nevertheless, the netnographic method is a good supplement to the more quantitative analysis presented later in this paper, and can help us interpret some of the findings from those analyses. Though it is important to mention, when we qualitatively assess what we find important to record in the immersion journal, we inevitably introduce a human bias and subjectivity which creates for a low reliability since other researchers might focus on other observations. The same goes for our Twitter dataset as social media is changing all the time and posts might be deleted. Therefore it is important to note that this is a subjective still shot of how we interpret the situation at the time we collected our data, based on the sample of NGOs that we encountered. Further the subset of tweets might not be generalizable for our entire Twitter dataset either, since we only look at 261 tweets (including tweets from all NGOs) out of a total of 9,449 tweets and therefore might only capture specific parts of the communication that the NGOs engage in on Twitter. Related to this, the twitter activity varies across the organization, whereas some actors and their agendas are more prominent in part of the results (table 1).

# 6 Social network analyses (13)
As presented in the previous, the NGOs interact with each other by different types of collaborations. However, to get a deeper understanding of how the NGOs interrelate, we make two automated network analyses to explore who the NGOs retweet. First, we describe the methodological choices followed by results from the analyses.

## 6.1 Method (29)
The networks will be directed based on relations showing different social ties. We operationalize retweeting as endorsement and indicate joint activity, project, or shared identification. Notably, even though we make these operationalizations based on findings in our immersion journal, we include a bias to the analyses as connections also can be based on critique and disagreements.

The nodes represent the NGOs as the networks are actor restricted. Edges represent retweet connection. The node size will indicate the specific node's in-degree centrality measures, which are the NGOs connectivity to other NGOs. Thus, a user with high in-degree is retweeted a lot by one of the NGO.

Furthermore, we have chosen to look at retweets with community detection by using the Gephi plugin measuring the Louvain modularity. This will create a subset of vertices in our graph that have more connections to each other than the rest of the network, thus visually dividing our network by coloured labels. The networks are visualized using Gephi and the algorithm Force Atlas 2 (Decuypere 2020).

## 6.2 Analysis (24)
The social network of retweets has 915 nodes, 1,218 edges of retweets, and 13 communities. The network in fig. 7 shows how the NGOs mainly retweet different actors clustered in different regions of the network. However, we also see a number of central actors, in whom the NGOs interrelate through. These actors are mainly important actores for the political and humanitarian debate as Rasmus Prehn, being the Minister for Development Cooperation, and the Ministry of Foreign Affairs of Denmark, or national news sites (App. 5). These findings are corresponding with our observations in the netnography, being that Twitter is especially used for political content. Besides we also see how some of the NGOs are taken central places in the network, eg. Dansk Flygtninge Hjælp and Red Barnet. In our netnography, we also found that these NGOs were central actors of the humanitarian public debate participating in many collaborations and talks into many of the pattern codes, indicating that these two NGOs are broad in their agendas. Further, we see many clusters of actors in the outer border of our network, eg. Danmission and Caritas. These users have weak ties to the network. Moreover, Caritas is only connected to the rest of the network through two bridges, Danmission and one other user, whereas the interrelations are sparse (Wasserman & Faust 1994: 114).

**Fig. 7. SNA retweets**
 
To get a more systematic understanding of how the NGOs retweet each other, we make a sub network containing only retweets between the NGOs. In the network three of the NGOs are disconnected including Mission East, whereas no other NGO retweets them, indicating no direct interactions.

Fig. 8 shows a different picture of interrelations than the VNA of collaborations; this retweet network indicates multiple types of interrelations. We see that Caritas and Danmission are subgraphs, where only Caritas is retweeting Danmission, whereas the two NGOs are not interacting with the rest of the field. Globalt Fokus has the highest in-degrees, opposite in the VNA, where Amnesty and Mellemfolkeligt Samvirke were central actors (App. 6). As Globalt Fokus is an umbrella organization taking multiple of the actors agendas into account, they share content about common political agendas for the NGOs, which the NGOs retweets making them central. These findings above indicate that although scraped retweets can give some understanding of social ties, it does not give the same picture as going through the text, using netnography to collect deep data. Opposite our SNA of all retweets in fig. 7, only inspecting the retweets in between the NGOS, we identify 5 communities.

**Fig. 8.  SNA retweets only actors with communities**



## 6.3 Discussion (13)
The SNAs showed relations providing information we would not be able to qualitatively interpret without the computational visualizations. However, as indicated in our netnographic findings, retweets can be systematically different for the NGOs. With other words, we risk interpreting these interrelations as one type of relation, thereby missing important information about how some of the NGOs only retweet, when they disagree with a statement, others when they are being mentioned themselves. Further, we have only covered the social ties on Twitter, but as we saw in our VNA, some of the actors are to a greater extent active on other social media platforms, such as Instagram or Facebook. Had we created a quantitative social network using data from these platforms, we might have found other insights than what we have collected.

# 7 Content analysis (29)
In this last analysis, we will look further at the interrelations between the NGOs by looking at the semantics in the twitter communication of the NGOs. We will do this by performing a principal component analysis (PCA).

## 7.1 Method of PCA (24)
PCA is a dimension-reduction method used for transforming a large dataset of variables into less dimensions, still containing much of the original information. The tradeoff of dimension-reduction lies in missing a bit of the accuracy towards gaining more simplicity, making it easier to inspect data (Pett et al. 2003). The method creates several components, which shall be thought of as dimensions representing similarities in data (Shravan & Ravi 2017). We use PCA to identify the main dimensions which are underlying the field of the Danish humanitarian NGOs. Here, the clusters of either words or actors can indicate symbolic interrelations based on similarities. Notably, the findings of the PCA can be hard to interpret without an ethnographic framework, whereas we combine the PCA with the earlier findings from both the netnography and the SNA.

We choose to include both hashtags, tokens, and bigrams based on word, not hashtags. In the PCA we argue that words co-occurring can be crucial for the semantics. We further standardize the words frequency across each NGO’s tweets to map the relative distances and interrelations. We make a PCA on this standardized matrix including the whole corpus after sorting out infrequent words.

## 7.2 Analysis (13)
Important for understanding the visualizations is that words in the graphs can be thought of as symbols tightening the actors together. Moreover, the actors are grouped together to the extent they are using the same words with the same level of frequency.

Fig. 9 shows the explained variance for the PCA: The blue dots show each individual principal component’s variance, the red dots express the cumulative variance for the 26 components. There exist several principles for evaluating how many components are useful for initially being interpreted. Using the so-called “elbow principle” common within PCA, we only get two components before the curve breaks (Linting et al. 2007).

**Fig. 9. Variance for PCA**

Fig. 10 shows the two most relevant components of discursive variation between the humanitarian NGOs on Twitter. Notably, the proportion of variance captured by each dimension is low. This indicates that there are multiple differences and similarities between the NGOs than mapped in the plot, whereas we unfortunately also see a lot of NGOs grouped in the middle of the plot with almost no variance explained. Further, multiple of the remaining NGOs' locations, like Caritas and Danmission, are centered near one axis, whereas only one of the components have explanatory value.

We interpret the first axis as a “improving vs. changing” perspective. NGOs who we interpret as world development-oriented with focus on improving living conditions are placed to the left and are symbolized by words as langsigtet (long-term) and udviklingspolitisk_humanitær (development policy_humanitarian). To the right we find more critical human rights-oriented NGOs centered around words such as stort_behov (large_needs) and torturkomite (torturecomité) indicating a focus on justice and changing human rights. We interpret the second axis as a more thematic agenda-focus component with Christian NGO in the top and child-focused NGOs at the bottom. This is further emphasized by the findings in our immersion journal, where it was clear how some of the more Christian NGOs communicated with many charity phrases and about slightly different content than the child-focused NGOs.

However, based on our understandings of the field from the netnography, we also identify words with different context being grouped together, eg. eksplosion (explosion) coming from the Beirut accident and pandemi (pandemic) are placed next to each other. These clusters of sporadic words can be understood in the perspective of the many open coding categories found in the immersion journal, together indicating how the NGOs communicate about multiple focuses based on different content. This might not always make theoretical sense to group, as we also see in the components low variance.

**Fig. 10. PCA**

## 7.3 Discussion (29) 
We see the PCA has 26 components, which are almost similar to the number of NGOs in our Twitter data set. This could indicate how each variance is showing aspects of the data mainly related to one NGO with exceptions from the main components including a frequency met by multiple NGOs.

Moreover, for text data it might also be unreasonable to assume that only few components are able to capture the majority of variance. As there is no clear indication of how many components to include, it can be difficult to know how many of the dimensions need to be considered. With many new computational and digital methods for text data being interpretable for social scientists, it should be considered to apply a machine learning set up being more suitable for handling text data than PCA, which easier capture variance attached to surveys among others.

# 8 ASDS II (18, 6, 12)
We will in this part of the paper use computational methods to help answer the overall research question exploring:

* Which topics are present in the communication of the Danish humanitarian NGOs during Covid-19 on Twitter?
* What classifies the Danish humanitarian NGOs’ communication on Twitter during Covid-19?


In what follows, we will run 3 different types of analyzes on the Twitter data (section 4.1). The strengths of the methods presented in this section lies in their ability to explore larger amounts of data than a researcher could manage by hand, thereby qualifying and adding a new layer of information towards our netnography.
We will conduct two different topic models, a Latent Dirichlet Allocation (LDA) and a hierarchical stochastic block model (hSBM) to investigate what topics emerge from our data. The findings will be used with a heuristic perspective combined with findings from the netnography to perform a Lasso classifier using logistic regression to classify the NGOs types of communication. We will discuss the results and the models’ limitations continuously.

## 8.1 Pre-processing (18)
Before describing the results, we will present the methodological choices regarding the pre-processing as these steps can have profound effects on the results for unsupervised machine learning (Denny & Spirling 2018).

First, as we are interested in text data, we strip away superfluous material removing emojis, hashtags, usernames, special characters, numbers and URLs. Since we are mostly interested in coarse features, we have decapitalized all words to create a consistent flow for the NLP tasks. We used fasttext, a pre-trained text classifier, for detecting the languages removing non-Danish tweets. Further, we use the Danish lemmatizer Lemmy to shorten all words to their roots and afterwards we remove stop words. This is favorable over stemming, as we expect lemmatizing to recognize word semantics to a higher degree. However, the Danish lemmatizer is not quality assured to the same degree as lemmatizers for more common languages. To accommodate this, we add 41 stop words (App. 1) in different tenses on top of the NTLK library of Danish stop words in an iterative process.

Furthermore, we have chosen to include bigrams as words can have substantial different meanings depending on the following word. We further add the hashtags stored in a separate column to the list of tokens and bigrams, though removing the # sign. Notably, we do not create bigrams of hashtags as these would have arbitrary meaning. Lastly, for both the LDA and hSBM we chose to also remove infrequent words if they appear in less than 10 documents.

## 8.2 Topic models (6)
Topic models is an unsupervised machine learning technique using word frequency and distribution to cluster documents of text and words into latent topics based on similar expressions or word use that co-varies. These models benefit from their ability to cover a lot of data with low costs and without human coder bias (Terman 2017). Below, we run a LDA, followed by a hSBM, while continuously qualitatively assessing their results.

### 8.2.1 LDA (12) 
LDA can detect latent topics in text data using the statistical correlations between words in the documents. The model is generative assuming that the text in the documents, here tweets, are generated from a pre-chosen distribution of topics with respective weights. Further, each topic has words associated with it and when a document is created the writer randomly chooses a word from one of the topics in relation to the respective topic weights (fig. 11). The LDA model is consequently set up to capture the process of this assumption.

**Fig. 11. LDA assumption**

The LDA is used to find the parameters most likely to have generated the documents. This happens by estimations using Gibbs sampling (Blei et al. 2017). We randomly assign one of K topics for each word. However, as the assignments are random, the topic representations are poor and the LDA needs more iterations to reconsider the topics for all words. The re-iterations for the topics for a word are based on both the distribution of other topics in the word’s document and topics in other documents, where the given word occurs (Atteveldt et al. 2021). When the model has been iterated enough number of times it reaches a roughly steady state being the results (ibid).

The number of topics affect the granularity of viewing data and there is consequently no right way of choosing the number of topics as this should be considered in relation to the purpose of study and types of documents. In order to decide the hyperparameters, we choose to look at the coherence score for assessing the quality of the models (Kana 2020). The score makes it possible to evaluate the coherence between topics and includes measuring the degree of semantic similarity across the world with highest scores in a topic. We use the umass score (Kapadia 2019).

We run 30 LDA models with K topics ranging from 1 to 30 as visualized in fig. 12. We choose 5 topics in our LDA as the score plateaus here, visualized in fig. 13. As we use tweets being short documents, a relatively small number of topics make sense for the LDA.

**Fig. 12. Coherence score**

**Fig. 13. Topics of LDA**

We have inspected the  and  parameters that indicate the topics for each document and shows which words there are dominating for each topic (App. 7). We have made a qualitative assessment of naming the topics: The world support during Covid-19, social sustainability, human rights and politics, socially vulnerable children, and refugee rights. These results clarify some of the netnographic findings.

We plotted how the topics are distributed in relation to each other on two principal components, measuring the variance between the topics, se fig. 14. Notably, topic 2, 3, and 4 follows the axes, whereas only one of the dimensions affects their variance. To the right, we see the top 30 relevant words for topic 4. Words like flygtning (refugee) and Syria are almost only part of topic 4, whereas words as barn (child) and Danmark (DK) are less exclusive.

**Fig. 14. LDA components**

Based on these interpretations, we evaluate the results presented here to have an acceptable level of cohesiveness as the topics include words, which we qualitatively assess to be related. However, some top words occur in multiple topics and the model is thereby not exclusive.

### 8.2.2 hSBM (18)
We perform a hSBM to assess the NGOs communication on Twitter. A hSBM treats a text corpus as a bipartite network of documents and words. It combines already existing methods such as community detection and stochastic block models, while adding a hierarchical clustering of the words and documents (Gerlach et. al 2018). Arguably, hSBM can be said to perform better than a LDA due to 1) the hSBM relies on fewer assumptions and excludes the Dirichlet assumption, 2) the model is nonparametric capturing a much richer spectrum of topics in data, and 3) hSBM enables identification of structural patterns in real text data (ibid). The number of topics or document groups are not specified beforehand but fitted by the model itself.

For the hSBM, we chose to aggregate the tweets for each of the NGOs. Hereby we can analyze which topics each NGO communicated most about. We risk losing some information by aggregating before running the model, such as changes in communication overtime. As we are interested in the entire time period of Covid-19, we argue that this is not problematic.

Fig. 15 shows the document group membership matrix for the hSBM in which we can explore how the NGOs are distributed amongst the document groups. It shows that most of the NGOs are associated with an individual document group and only a few are part of the same group. This means that there is a clustering of some of the NGOs, but that the rest of them are distinct in their topics.

**Fig. 15. Document group membership**

We also plotted the top 5 topics for each NGO. In total the model detected 121 topics (App. 8), though only 63 topics qualified as top 5 topics for the NGOs. Based on a combination of the words in each topic and the netnography, we hand labeled the 63 topics. We see in fig. 16 that the hashtags dkpol, dkaid, dkmedier and dkgreen are present as top topics for several NGOs. This is because the NGOs use the hashtags to classify the content of the tweet, e.g dkaid relating to aid work.

**Fig. 16. Top 5 topics**



We see the topic stå sammen (stand together) is used as a top 5 topic by 17 of the NGOs pertaining to Covid-19 with the NGOs focusing on the community in times of crisis. We also detect that the topic barn (child) is not as big in our hSBM as in both our qualitative findings and the LDA. The topic is only in top 5 for five NGOs, all having children clearly as their focus, eg. Børns Vilkår. This might be an effect of the large number of topics, whereas the model might have split the overall topic of children into subtopics. Lastly, since the model produces many topics, we also see that some of the topics mostly pertain to one NGO. For example, there is a topic called Johanne Schmidt Nielsen who is the general secretary for Red Barnet. This shows that even though the hSBM creates more meaningful topics then the LDA, it can also create too many topics.

## 8.3 Classifier (6) 
A classifier is a supervised learning task, where the algorithm will learn the classes based on labeled data. In this section, we will build our own classifier to determine what classifies the NGOs’ communication. More precisely, we will perform a binary Lasso Classifier by using scikit-learn’s LogisticRegression.
The classifier builds on a self-constructed dictionary containing words, which are either labeled as critical communication or part of a humanitarian supportive communication on Twitter. These are created based on a heuristic approach using the results from the topic models, a part of speech tagging indicating the most used words for different word classes (App. 9) and the findings from our netnography. We define critical communication as being content including critical opinions or direct criticism, and we define humanitarian support as statements about aid support or emotional stories.

### 8.3.1 Tuning the hyperparameters (12)
For all tweets, we map whether they are containing words from one of the two classes. We calculate whether a tweet contains most words from either the humanitarian class, the critical class or whether it has an equal number of words, including zero words, from the classes. We split the datasets into two; a training and test-set. With only 9,449 tweets, we prioritize having a larger training set choosing to use only 10% for testing. As we use Logistic Regression, we drop all tweets labeled with equal and end up with 6,476 tweets for training.

Before getting the final model, we need to train the Lasso classifier by finding the best hyperparameters. However, as we use text data for prediction, we start by converting the training data into a document feature matrix. After checking for the optimal hyperparameters (App. 10), while using a 5-fold cross-validation for ensuring balanced distributions across the folds, we find that the best performing model has lasso_C at 5 and is only using a vectorizer with term frequencies. This model’s accuracy score is 0.958. However, it is only slightly better than using a tf-idf vectorizer (ibid).

### 8.3.2 Fitting the classifier (18)
Before validating the performance of the classifier on the test data, we drop all words appearing in one of the two dictionaries to ensure that the model does not classify the test data based on the words used for training. The model performs with an accuracy of 0.87 meaning it predicts the right class 87% of the time. Fig. 17 shows the confusion matrix and the precision, recall and f1-scores for the model. Note that 0 represents the humanitarian support class and 1 the critical class.

The precision score represents the proportion of correct positive predictions and is higher for the critical class than the humanitarian class. The recall score, which is the proportion of all positives predicted as positive, is high for the humanitarian supportive class, but low for the critical class meaning we have a larger number of tweets that are falsely classified as not being critical even though they should be. Given the purpose of the classifier, the tradeoff between these scores can have different consequences depending on what the prediction should be used for. Lastly, the weighted average of the precision and recall score in F1 score indicates how the classifier is making a larger proportion of right predictions for the humanitarian supportive class.

**Fig. 17. Accuracy and confusion matrix for best Lasso**


Fig. 18 shows the top 20 coefficients in Lasso Classifier being the most sensitive words for classifying into one of the classes. The humanitarian supportive class is pictured on the left (red) and shows how the words determining for the class can be characterized as grateful words. Opposite are the words appearing to the right which are more critical words indicating desires or needs for changes.

**Fig. 18. Top 20 coefficients**

Looking at the mean score of classifications for each NGO in fig. 19, we see how they communicate differently in their tweets. In the test set according to the classifier, actors as Refugees Welcome and Mellemfolkeligt Samvirke are more critical in their communication, while NGOs as Red Barnet and Børns Vilkår are classified as mostly humanitarian supportive. We qualitatively assess that the classifier is performing well, since we find similar patterns in the netnography.

**Fig. 19. Mean score of classifications**

### 8.3.3 Classifier discussion (6)
The classifier can be criticized, as we risk creating lists of words, which are not exhaustive, being selective to choices of the researchers and which are not representative of the classes in general, but which are linked to this paper’s main findings risking the communication of the biggest NGOs to affect the results the most. Together this can question the external validity. However, implementing an already existing dictionary for classifying the words, could also be problematic. First, these types of dictionaries are sparse in Danish. Further, using a pre-trained model or a word2vec dictionary, we would risk measuring other aspects of the NGOs’ communication than we are interested in, as these libraries are created in another context.

Importantly, we also remove all equal tweets in the training data. This is not done for the test data set, meaning that tweets that might not fit this binary classification are still included, this is a pitfall of using a Lasso classifier. This bias also has significance for the accuracy, recall and precision scores.

## 8.4 Main findings (18, 6, 12)
In this part of the paper, we have built a heuristic research process creating elements of knowledge in steps useful for answering how the Danish humanitarian NGOs communicate on Twitter during Covid-19. The topic models create 5 and 121 topics related to different agendas dominating the NGOs’ communication. Among these we see topics related to aid emergencies, world conflicts, children and Covid-19. Overall, qualitatively assessing the topics makes sense, however, the numbers of topics are a bit arbitrary indicating how the models probably are not exhaustive. Based on these findings, we create a Lasso classifier with logistic regression classifying tweets as either critical or humanitarian supportive. The classifier has an accuracy of 87%, but makes better predictions for the humanitarian support class. Further, the predictions show how the NGOs in the test data vary in their average of being either critical or humanitarian supporting indicating different focuses in their Twitter communication.

# 9 Quali-quantitative integrations across methods (29)
We have in this paper performed a quali-quantitative analysis through curation and single-level analysis (Munk 2019). Through curation, we used a critical practice in which our sampling strategy was characterized by iteratively determining how to demarcate our data, thus moving from data sampling to analysis (Munk 2019). This strategy became integral to the way in which our data should be sourced and quantified. We were left with the only possibility of following the digital traces on Twitter and using them in our quantitative social networks analysis, the netnography showed how the NGOs utilize different social media platforms (Venturini et al. 2018). Although we knew the scope of our investigation, we are left with the limitations of not being able to generalize our findings to social media platforms in general, as we know the coverage is not sufficient.

Through single-level analysis we were analysing and interpreting our quantitative patterns emerged directly from our qualitative observations, thus understanding how our macro phenomena of NGOs communications are enabled by interactions on the micro level (Munk 2019). Through our qualitative netnography, and visual network analysis we acquired deep information which could be used in interpreting our social network, principal component analysis and computational analysis (Marres & Gerlitz 2016). This is a great strength of single-level analysis, as we, with quantitative methods, are left with a meaning problem, where we see associations and interrelations, but not the meaning of underlying practices. Therefore, our qualitative analysis has helped solve this meaning problem.

# 10 Conclusion (29, 24, 13) 
We have investigated what dominated the Danish humanitarian NGOs’ communication during the period of Covid-19 and how the NGOs interrelated on Twitter. Using the netnographic framework adopted from Kozinets we found what focus the  NGOs included in their communication.

The topic of Covid-19 was prominent in the communication, but not all NGOs communicated about the pandemic, some had very specific focuses that were not affected by Covid-19. Many of the NGOs had a huge focus on children in their communication, though with different focuses. We further explored how multiple of the NGOs interrelated through collaborations and which they actively used as framing in their communication across platforms. Moreover, the NGOs retweeted each other indicating a coherent public debate. However, some of the larger NGOs were more prominent in the debate, amongst others due to their multiple set of agendas.
We further explored the interrelations through a PCA explaining similarities across the NGOs. The PCA explained a minimum of discursive variance, but showed clusters, which qualitatively assessed supports the findings in the netnography. Lastly, we draw on computational methods including a LDA and hSMB topicmodels for pattern finding, identifying 5 and 121 topics. We used the findings from these and the netnography in a heuristic process identifying two types of rhetoric classes, a humanitarian supportive and a critical class, which we used for training a binary Lasso Classifier.

# 11 References 

Allan, J. I., & Hadden, J. (2017). “Exploring the Framing Power of NGOs in Global Climate Politics.” Environmental politics 26.4: 600–620. Web.

Armstrong, C., & Butcher, C. (2018). “Digital Civil Society: How Nigerian NGOs Utilize Social Media Platforms.” International journal of politics, culture, and society 31.3: 251–273. Web.

Atteveldt, W. v., Trilling, D. & Arcila, C. (2021). “Computational Analysis of Communication: A practical introduction to the analysis of texts, networks, and images with code examples in Python and R”

Blei, D., Papanikolaou, Y., Foulds, J. R., Rubin, T. N. & Tsoumakas, G. (2017). Dense Distributions from Sparse Samples: Improved Gibbs Sampling Parameter Estimators for LDA. In Journal of Machine Learning Research 18 (2017) 1-58

Blok, A., Enggaard, T. R., Isfeldt, A., Møller, A. H.Carlsen, H. B. & Albris (2020). ‘Inter-risk framing contests’. Under review for American Journal of Cultural Sociology

Breslin, A., Enggard, T.R., Blok, A., Gårdhus, T., & Pedersen, M.A (2020). “How We Tweet About Coronavirus, and Why: A Computational Anthropological Mapping of Political Attention on Danish Twitter during the COVID-19 Pandemic. Somatosphere.” 

Caliandro, A. (2018). “Digital methods for ethnography: Analytical concepts for ethnographers exploring social media environments”. Journal of Contemporary Ethnography, 47(5), 551-578

Campagnolo, G.M. (2020). “The analogue mapping”. Chapter 3 in Social Data Science Xennials, 35-50

Carlsen, H. and Ralund S..(2021) “Computational grounded theory revisited: from computer lead to computer assisted text analysis”. Working Paper.

Decuypere, M. (2020). “Visual network analysis: a qualitative method for 
researching sociomaterial practice”. Qualitative Research, 20(1).

Denny, J, & Spirling, A.. “Text Preprocessing For Unsupervised Learning: Why It Matters, When It Misleads, And What To Do About It.” Political analysis 26, no. 2 (2018): 168–189.

Dereli, T., & Eligüzel, N., & Çetinkaya, C. (2021). “Content Analyses of the International Federation of Red Cross and Red Crescent Societies (ifrc). Based on Machine Learning Techniques through Twitter.” Natural hazards (Dordrecht) 106.3: 2025–. Web.

Gerlach, M., Peixoti, T.P. & Altman, E.G (2018). “A network approach to topic models”. Science Advances. 

Haavisto, I. S. & G. Kovacs (2013). ’Chapter 27: Sustainbility in humanitarian operations’. In A. Lindgreen, F Maon, J Vanhamme & S. Sen (eds), Sutainable Value Chain Management: Analyzing, Designing, Implementing and Monitoring for Social and Environmental Responsibility. Gower, Farnham, pp. 489-507. 

Halford, S. & Savage, M. (2017). “Speaking sociologically with big data: symphonic social science and the future for big data research”. Sociology 51(6): 1132-1148

Hoofnagle, C. J., van der Sloot, B.  & Borgesius, F. Z. (2019). “The European Union general data protection regulation: what it is and what it means”. Information & Communications Technology Law

Kana, Michel (2020). “Topic model tutorial with Latent Dirichlet Allocation (LDA)”

Kapadia, Shashank (2019). “Evaluate Topic Models: Latent Dirichlet Allocation (LDA)”

Kozinets, Robert V (2019). “The Essential Guide to Qualitative Social Media Research”. SAGE. 

Ladle, R. J., Jepson, P., & Whittaker, R. J. (2005). ”Scientists and the media: The struggle for legitimacy in climate change and conservation science”. Interdisciplinary Science Reviews, 30(3), 231-240. https://doi.org/10.1179/030801805X42036

Linting, M., Meulman, J. J., Groenen, P. J. F., & van der Koojj, A. J. (2007). “Nonlinear principal components analysis: Introduction and application”. Psychological Methods, 12(3), 336–358. https://doi.org/10.1037/1082-989X.12.3.336

Lück, J., Wessler, H., Wozniak, A., & Lycarião, D. (2018). “Counterbalancing global media frames with nationally colored narratives: A comparative study of news narratives and news framing in the climate change coverage of five countries”. Journalism, 19(12), 1635-1656. https://doi.org/10.1177/1464884916680372

Munk, A.K. (2019). “Four styles of quali-quantitative analysis: making sense of the new Nordic food movement on the web”, Nordicom Review 40(1): 159-176

Neumayer, Eric (2012). “Human Development and Sustainability.” Journal of human development and capabilities 13.4: 561–579. Web.

Pett, M.A., Lackey, N.R. and Sullivan, J.J. (2003) “Making Sense of Factor Analysis: The Use of Factor Analysis for Instrument Development in Health Care Research”. SAGE Publications, Thousand Oaks. http://dx.doi.org/10.4135/9781412984898

Ryfman, Philippe (2007). “Non-Governmental Organizations: An Indispensable Player of Humanitarian Aid.” International review of the Red Cross (2005) 89.865: 21–46. Web.

Schäfer, M. S. (2012). “Online communication on climate change and climate politics: A literature review”. Wiley Interdisciplinary Reviews: Climate Change, 3(6), 527-543. https://doi.org/10.1002/wcc.191

Shravan Kumar B., & Ravi, V. (2017). “Text Document Classification with PCA and One-Class SVM”. In: Satapathy S., Bhateja V., Udgata S., Pattnaik P. (eds) Proceedings of the 5th International Conference on Frontiers in Intelligent Computing: Theory and Applications. Advances in Intelligent Systems and Computing, vol 515. Springer, Singapore. https://doi.org/10.1007/978-981-10-3153-3_11

Takahashi, B., Edwards, G., Roberts, J. T., & Duan, R. (2015). “Exploring the use of online platforms for climate change policy and public engagement by NGOs in Latin America. Environmental Communication”, 9(2), 228-247. https://doi.org/10.1080/17524032.2016.1275731

Terman, Rochelle (2017). “Islamophobia and Media Portrayals of Muslim Women: A Computational Text Analysis of US News Coverage, International Studies Quarterly”, Volume 61, Issue 3, September 2017, Pages 489–502, https://doi.org/10.1093/isq/sqx051

Venturini, T., Bounegru, L., Gray, J., & Rogers, R. (2018). “A reality check(list) for digital methods”. New Media & Society, 20(11), 4195–4217. https://doi.org/10.1177/1461444818769236

Vu, H. T., Blomberg, M., Seo, H., Liu Y., Fatemeh Shayesteh & Hung Viet Do (2021). “Social Media and Environmental Activism: Framing Climate Change on Facebook by Global NGOs.” Science communication 43.1: 91–115. Web.

Wasserman, S., & Faust, K. (1994). “Social network analysis: Methods and applications
(Vol. 8). Cambridge university press.

Wukich, C. & Khemka, A. (2017). “Social media adoption, message content, and reach: an examination of Red Cross and Red Crescent national societies”. International Journal of Emergency Management. 13. 89. 10.1504/IJEM.2017.10003683.

WCED (1987). “Report of the World Commission on Environment and Development” (The Brundtland Report), United Nations World Commission on Environment and Development, UN publication A/42/427

WHO (2021). “Coronavirus disease (COVID-19) update”. https://www.who.int/bangladesh/emergencies/coronavirus-disease-(covid-19)-update#:~:text=On%20this%20website%20you%20can,on%2031%20December%202019 [Viisted 18-06-2021]

Yang X., Chen B. C., Maity M. & Ferrara E. (2016). “Social Politics: Agenda Setting and Political Communication on Social Media”. In: Spiro E., Ahn YY. (eds) Social Informatics. SocInfo 2016. Lecture Notes in Computer Science, vol 10046. Springer, Cham. https://doi.org/10.1007/978-3-319-47880-7_20
