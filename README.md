# Named Entity Recognition (NER) Application

A Python-based Named Entity Recognition (NER) application that identifies and extracts entities such as **people, organizations, locations, dates, and other relevant information** from user-provided text.

## Features

* Named Entity Recognition from text
* Identifies and extracts relevant entities
* Interactive Streamlit interface
* Hugging Face Transformer model for NER
* Real-time entity extraction

## Technologies & Libraries

* Python
* Streamlit
* Hugging Face Transformers

## Model

This project uses the following Hugging Face model:

**Model:** [mdarhri00/named-entity-recognition](https://huggingface.co/mdarhri00/named-entity-recognition)

## Project Structure

```text
NER/
│
├── app.py
├── requirements.txt
├── README.md
└── screenshot/
    └── ui.png
```

## Installation

Clone the repository:

```bash
git clone https://github.com/laibabatool/Name-Entity-Recognition.git
```

Navigate to the project directory:

```bash
cd Name-Entity-Recognition
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Run the Application

Run the following command in the terminal:

```bash
streamlit run app.py
```

The application will open in your browser.

## User Interface

![NER Application UI](screenshot/ui.png)

## Example

**Input:**

```text
Barack Obama was born in Hawaii and served as the President of the United States.
```

The application identifies and extracts named entities from the provided text.

## Requirements

The main dependencies used in this project include:

```text
streamlit
transformers
torch
```

## Acknowledgements

* [Hugging Face Transformers](https://huggingface.co/docs/transformers)
* [NER Model - mdarhri00/named-entity-recognition](https://huggingface.co/mdarhri00/named-entity-recognition)
* [Streamlit](https://streamlit.io/)

## License

This project is intended for educational and demonstration purposes.
