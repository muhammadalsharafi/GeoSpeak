# GeoSpeak

[cite_start]Developed by **Yemen Coders** [cite: 3][cite_start], **GeoSpeak** is a GenAI Smart Solution [cite: 4] [cite_start]designed to eliminate language barriers through context-aware, real-time translation[cite: 31, 33]. [cite_start]Unlike conventional tools that provide literal translations, GeoSpeak uses semantic analysis to ensure the intended meaning is preserved across different sectors like diplomacy, business, and education[cite: 31, 33].

---

## Problem Definition
[cite_start]Language barriers significantly impact global communication[cite: 27]. [cite_start]A survey indicated that **70% of international organizations** reported business losses or expensive misunderstandings due to language obstacles[cite: 28]. [cite_start]Traditional translation services often lack contextual awareness, leading to errors in words with multiple meanings, such as "bank" (financial institution vs. river side)[cite: 29, 30].

## Proposed Solution
[cite_start]GeoSpeak addresses these issues by leveraging state-of-the-art language models, including **GPT-4 Turbo**, **GPT-4 Vision**, and the **ChatGPT OpenAI API**[cite: 33]. [cite_start]By employing semantic translations, the application interprets both the input text and its surrounding context to promote accurate interaction[cite: 33].

## Key Features
* [cite_start]**Contextual Accuracy:** Uses semantic analysis to distinguish between homonyms and idiomatic expressions[cite: 33, 91].
* [cite_start]**Real-Time Processing:** Built for immediate web-based translation[cite: 33, 39].
* [cite_start]**Vector Database Integration:** Queries a vector database for translation examples to enhance reliability[cite: 39].
* [cite_start]**Large Input Capacity:** Supports up to **2000 characters** per request[cite: 45, 47].

## Project Specifications
* [cite_start]**Purpose:** To facilitate seamless, contextually accurate communication across multiple languages[cite: 37].
* [cite_start]**Scope:** A real-time web application utilizing Embedding APIs, Vector Databases, and LLMs[cite: 39].
* **Constraints:**
    * [cite_start]Requires high-quality, precomputed embeddings in the Vector Database[cite: 41].
    * [cite_start]Currently does not support audio or speech translations[cite: 44].
    * [cite_start]Maximum input limit of 2000 characters to ensure efficient processing[cite: 45].
    * [cite_start]Requires an active internet connection to run[cite: 107].

---

## System Workflow
[cite_start]The application follows a structured process to ensure high-quality output[cite: 63, 64]:
1.  [cite_start]**Text Input:** User inputs English text and selects a target language[cite: 47, 64].
2.  [cite_start]**Vector Generation:** A pre-trained model generates high-dimensional embedding vectors[cite: 48, 64].
3.  [cite_start]**Retrieval:** The system queries a Vector Database for matching documents and examples[cite: 49, 64].
4.  [cite_start]**Generation:** A context-aware prompt is created for the Language Model to generate the final translation[cite: 50, 51, 64].
5.  [cite_start]**Display:** The translation is presented in a simple, easy-to-understand interface[cite: 52, 54, 64].

---

## Installation and Execution
### Requirements
* [cite_start]Internet connection[cite: 107].
* [cite_start]Jupyter Notebook environment[cite: 72, 107].
* [cite_start]All necessary libraries are included within the project code[cite: 106].

### Steps to Run
1.  [cite_start]**Access the Repository:** Click on the GitHub link to access the GeoSpeak files[cite: 68, 102].
2.  [cite_start]**Open the Notebook:** Locate and open the main notebook file `main.ipynb`[cite: 70].
3.  [cite_start]**Execute Cells:** In the Jupyter environment, run each cell in the correct order using the play button or `Shift + Enter`[cite: 72, 73].
4.  [cite_start]**Interact:** Follow the instructions in the notebook to input text and explore translation features[cite: 75, 76].

---

## Test Data Examples
| Input Type | Input (English) | Expected Translation (Spanish) |
| :--- | :--- | :--- |
| **Basic** | [cite_start]"Hello, how are you?" [cite: 81] | [cite_start]"Hola, ¿cómo estás?" [cite: 82] |
| **Idiomatic** | [cite_start]"The early bird catches the worm." [cite: 84] | [cite_start]"Al que madruga, Dios lo ayuda." [cite: 85] |
| **Context A** | [cite_start]"I went to the bank to deposit money." [cite: 92] | [cite_start]"Fui al banco a depositar dinero." [cite: 94] |
| **Context B** | [cite_start]"I stood on the river bank to fish." [cite: 93] | [cite_start]"Me paré en la orilla del río a pescar." [cite: 95] |
| **Edge Case** | [cite_start]"Heyyyyy!!! :) :)" [cite: 89] | [cite_start]"¡Oyeeeee!!! :) :)" [cite: 90] |

---

## Links
* [cite_start]**The Old GitHub Repository:** [https://github.com/ALADEEMI/Geo-Speak.git](https://github.com/ALADEEMI/Geo-Speak.git) [cite: 102]
* [cite_start]**Project Blog:** [Link] [cite: 110]
