# GeoSpeak

Developed by **Yemen Coders**, **GeoSpeak** is a GenAI Smart Solution designed to eliminate language barriers through context-aware, real-time translation. Unlike conventional tools that provide literal translations, GeoSpeak uses semantic analysis to ensure the intended meaning is preserved across different sectors like diplomacy, business, and education.

---

## Problem Definition
Language barriers significantly impact global communication. A survey indicated that **70% of international organizations** reported business losses or expensive misunderstandings due to language obstacles. Traditional translation services often lack contextual awareness, leading to errors in words with multiple meanings, such as "bank" (financial institution vs. river side).

## Proposed Solution
GeoSpeak addresses these issues by leveraging state-of-the-art language models, including **GPT-4 Turbo**, **GPT-4 Vision**, and the **ChatGPT OpenAI API**. By employing semantic translations, the application interprets both the input text and its surrounding context to promote accurate interaction.

## Key Features
* **Contextual Accuracy:** Uses semantic analysis to distinguish between homonyms and idiomatic expressions.
* **Real-Time Processing:** Built for immediate web-based translation.
* **Vector Database Integration:** Queries a vector database for translation examples to enhance reliability.
* **Large Input Capacity:** Supports up to **2000 characters** per request.

## Project Specifications
* **Purpose:** To facilitate seamless, contextually accurate communication across multiple languages.
* **Scope:** A real-time web application utilizing Embedding APIs, Vector Databases, and LLMs.
* **Constraints:**
    * Requires high-quality, precomputed embeddings in the Vector Database.
    * Currently does not support audio or speech translations.
    * Maximum input limit of 2000 characters to ensure efficient processing.
    * Requires an active internet connection to run.

---

## System Workflow
The application follows a structured process to ensure high-quality output:
1. **Text Input:** User inputs English text and selects a target language.
2. **Vector Generation:** A pre-trained model generates high-dimensional embedding vectors.
3. **Retrieval:** The system queries a Vector Database for matching documents and examples.
4. **Generation:** A context-aware prompt is created for the Language Model to generate the final translation.
5. **Display:** The translation is presented in a simple, easy-to-understand interface.

---

## Installation and Execution
### Requirements
* Internet connection.
* Jupyter Notebook environment.
* All necessary libraries are included within the project code.

### Steps to Run
1. **Access the Repository:** Click on the GitHub link to access the GeoSpeak files.
2. **Open the Notebook:** Locate and open the main notebook file `main.ipynb`.
3. **Execute Cells:** In the Jupyter environment, run each cell in the correct order using the play button or `Shift + Enter`.
4. **Interact:** Follow the instructions in the notebook to input text and explore translation features.

---

## Test Data Examples
| Input Type | Input (English) | Expected Translation (Spanish) |
| :--- | :--- | :--- |
| **Basic** | "Hello, how are you?" | "Hola, ¿cómo estás?" |
| **Idiomatic** | "The early bird catches the worm." | "Al que madruga, Dios lo ayuda." |
| **Context A** | "I went to the bank to deposit money." | "Fui al banco a depositar dinero." |
| **Context B** | "I stood on the river bank to fish." | "Me paré en la orilla del río a pescar." |
| **Edge Case** | "Heyyyyy!!! :) :)" | "¡Oyeeeee!!! :) :)" |

---

## Links
* **Old GitHub Repository:** [https://github.com/ALADEEMI/Geo-Speak.git](https://github.com/ALADEEMI/Geo-Speak.git)
* **Project Blog:** [Link]
