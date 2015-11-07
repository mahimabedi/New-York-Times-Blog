# New-York-Times-Blog
Prediction model for popularity of blog articles in R

Data sample size:
September 2014-December 2014
Training dataset: 6532 articles
Testing dataset: 1870 articles

Data structure:
NewsDesk = the New York Times desk that produced the story (Business, Culture, Foreign, etc.)
SectionName = the section the article appeared in (Opinion, Arts, Technology, etc.)
SubsectionName = the subsection the article appeared in (Education, Small Business, Room for Debate, etc.)
Headline = the title of the article
Snippet = a small portion of the article text
Abstract = a summary of the blog article, written by the New York Times
WordCount = the number of words in the article
PubDate = the publication date, in the format "Year-Month-Day Hour:Minute:Second"
UniqueID = a unique identifier for each article

Popular is the dependent variable, which labels if an article had 25 or more comments in its online comment section (equal to 1 if it did, and 0 if it did not).
