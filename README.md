# Investigating Literary Representation in BERTopic 

American high school reading curricula often rely on a limited collection of texts, commonly known as "the classics." These texts are drawn from the Western Literary Canon, a curated set of "good" books that are deemed essential for everyone to read. However, the notion of an objective "standard" for literature has come under scrutiny, sparking debates about the potential consequences of exclusive authorship, biased representations, and their socio-cultural impacts. This project delves into these issues by employing BERTopic, a neural topic modeling framework, to analyze plot summaries of canonical works and uncover underlying themes, genres, and patterns.

Unlike traditional topic modeling, which tends to be rigid in extracting topic representations, BERTopic utilizes contextual embeddings. This allows it to create topic clusters based on the semantic meaning of the text, grouping together documents or sentences with similar underlying concepts, even if they use different words. This ability to capture broader and more abstract representations is especially useful in literary analysis, where themes and context are critical.

Additionally, the class-based tfidf procedure in BERTopic helps ensure that even seemingly "noisy" terms can contribute meaningfully to an analysis of the literary canon. This flexibility not only allows for minimal preprocessing, but a more nuanced exploration of literary themes. Finally, the option to use language model chaining to fine-tune topics for greater interpretability helps maintain coherence, offering a balance between abstract insights and structured results. Therefore, with BERTopic, it is possible to carry out a critique of the Western Literary Canon, and in turn, high school reading curricula.
