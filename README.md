# Lab 2: Introduction to NLP - Regex and Word Embedding

## Objective
The main purpose behind this lab is to get familiar with NLP techniques including Rule-based NLP, Regex, and Word Embedding.

## Part 1: Rule-Based NLP and Regex
### Task Description
Using Regex, write Python code that can generate a bill from text provided by the user. This involves extracting product names, quantities, and prices to calculate total costs.

### Example
**Input**: "I bought three Samsung smartphones at $150 each, four kilos of fresh bananas for $1.2 a kilogram, and one Hamburger for $4.5."  
**Expected Output**: A table displaying the product, quantity, unit price, and total price.

## Part 2: Word Embedding Techniques
### Techniques to Apply
1. One Hot Encoding
2. Bag of Words
3. TF-IDF
4. Word2Vec Approaches (Skip Gram, CBOW)
5. GloVe and FastText

### Visualization
Apply the t-SNE algorithm to plot all encoded/vectorized vectors.

### Evaluation
Evaluate these approaches based on the visualizations and discuss the effectiveness of each in encoding semantic information.

## Student Synthesis:
At the end of each student must give a brief synthesis about what he has learned during the proposed lab.

## GitHub Repository and README:
The work has been pushed to the GitHub repository, and this README file serves as a brief report summarizing the lab objectives, implementation details, and student synthesis.

---

## Student Synthesis:

During this lab, I gained valuable insights into various techniques in Natural Language Processing (NLP). Here's a brief summary of what I've learned:

1. **Rule-Based NLP and Regex**: I learned how to use regular expressions (Regex) to extract structured information from unstructured text data. This involved identifying patterns and using them to parse text and generate useful output, such as a bill from a shopping description.

2. **Word Embedding Techniques**: I explored several word embedding techniques, including:
    - One Hot Encoding: Representing words as sparse vectors with a single '1' indicating the presence of the word.
    - Bag of Words (BoW): Creating a sparse matrix representing the frequency of each word in a document.
    - TF-IDF: Calculating the importance of a word in a document based on its frequency across the corpus.
    - Word2Vec (Skip Gram and CBOW): Learning distributed representations of words in a continuous vector space.
    - GloVe and FastText: More advanced word embedding models incorporating global word co-occurrence statistics and subword information.

3. **Visualization and Evaluation**: I visualized word embeddings using t-SNE to understand the semantic relationships between words in the embedding space. I evaluated the effectiveness of each technique in capturing semantic information and observed their strengths and weaknesses.

Overall, this lab provided a comprehensive overview of NLP techniques, from basic text processing with Regex to advanced word embedding models. I gained practical experience in implementing these techniques and learned how to evaluate their performance for various NLP tasks.

---

## Report:

### Lab 2: Introduction to NLP - Regex and Word Embedding

#### Objective:
The objective of this lab was to familiarize students with NLP techniques, including rule-based NLP, Regex, and word embedding techniques, and to provide hands-on experience in implementing these techniques.

#### Part 1: Rule-Based NLP and Regex:
In this part, students were tasked with writing Python code to generate a bill from text provided by the user using Regex. The code extracted product names, quantities, and prices from the input text and calculated the total cost of the items.

#### Part 2: Word Embedding Techniques:
Students explored various word embedding techniques, including One Hot Encoding, Bag of Words (BoW), TF-IDF, Word2Vec (Skip Gram and CBOW), GloVe, and FastText. They implemented these techniques using libraries such as scikit-learn and gensim. Visualization using t-SNE was employed to evaluate the effectiveness of these techniques in capturing semantic information.

#### Student Synthesis:
At the end of the lab, each student was required to provide a brief synthesis of their learning experience. They reflected on the concepts covered in the lab, the challenges faced during implementation, and the insights gained from evaluating the word embedding techniques.

#### GitHub Repository and README:
Students were instructed to push their work to a GitHub repository and write a brief report in the README file. The README file should contain a summary of the lab objectives, a description of the implemented code, and the student's synthesis of their learning experience.

Overall, Lab 2 provided students with a practical introduction to NLP techniques and allowed them to gain hands-on experience in implementing rule-based NLP, Regex, and word embedding techniques. It emphasized the importance of understanding text data and provided a foundation for more advanced NLP tasks.
