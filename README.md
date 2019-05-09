# sentiment-journal
WIP: suggest relevant readings based on diary/journal entries. 


## Motivation

I've wanted to start journaling for a while. I like writing and think it's one of the best ways to refine my thoughts and goals. I spend a lot of time thinking and I hate letting all that work figuring things out go to waste. I've tried paper journaling which is cathartic, but I don't think I get as much out of it as I could. There are some online journaling platforms including Evernote and Penzu and while they succeed in providing a space to write, I think more work can be done to create a platform for catharsis, insight and discovery.

I've been playing around with the idea of a journal as a friend or teacher. I'd like to build a tool for writing that will provide some useful feedback on where things look good and where there's room for expansion. When it's useful, the tool might suggest authors or articles that are relevant to the writing. In all, this would enhance journaling by making it a process that looks not only inward but also towards relevant outside sources that provide context to individual experiences and reflections. 

An ideal solution might:

- Motivate me to write daily and take notes. 
- Help me extract insight from my writing. 
- Find useful readings with similar, contrary, or otherwise illuminating thoughts.

## Planning

- Web interface
	- React Webapp?

- Backend
	- Start out w/ Simple Sentiment Analysis
		- NLTK / spaCy
	- Eventually maybe investigate text style & ideas. 
		- Doc2Vec?
		- Word2Vec?

