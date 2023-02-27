# SmartCourseSearch

This is a course recommendation engine designed to help university students easily find courses that discuss topics they are interested in. The product works by creating sentence embeddings using a model from HuggingFace for descriptions of all courses at the University of Illinois. When a student sends a query (the topic(s) they are interested in) to the website, a sentence embedding is generated. The sentence embedding from the query is then compared to all the sentence embeddings of the course descriptions using cosine similarity. The closest matches are then returned to the user.

The website is currently paused since HuggingFace doesn't let you set billing limits 🥲
