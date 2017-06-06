# tfidf-profile-retrieval
---

This project creates amethod based in the space vector model to deliver small text snippets to different users depending on their profile using the the tf-idf (term frequency-inverse document frequency) criteria. Different users have different profiles which are composed of topics of interest (such as sport, politics or music). The user can have any combination of those topics as their profile, be it a single topic or multiple ones. The main idea is that users want to receive texts corresponding to those topics that are selected in their profile. So, if a text’s main topic is the French presidential election, then this text should be delivered to all the users which have the topic ”politics” included in their profile.
