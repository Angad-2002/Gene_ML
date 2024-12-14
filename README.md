# Gene_ML

Gene_ML is a machine learning-based project that uses natural language processing (NLP) techniques to classify genome sequences for different species. The classifier achieves high accuracy in identifying genome sequences for chimpanzees, humans, and dogs, leveraging a Multinomial Naive Bayes model.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Future Scope](#future-scope)
- [Contributing](#contributing)
- [License](#license)

## Features

- Classification of genome sequences into species (chimpanzees, humans, dogs).
- High accuracy achieved through optimized preprocessing and feature extraction.
- Intuitive user interface built with Gradio for seamless interactions.

## Technologies Used

- **Programming Language:** Python
- **Libraries:**
  - `numpy`
  - `pandas`
  - `nltk`
  - `scikit-learn`
  - `Gradio`

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Angad-2002/Gene_ML.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Gene_ML
   ```

3. Create and activate a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate # For Linux/macOS
   venv\Scripts\activate   # For Windows
   ```

4. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Prepare your genome sequence data in the required format.

2. Run the application:
   ```bash
   python app.py
   ```

3. Open the Gradio interface in your browser (link will be displayed in the terminal).

4. Upload or input genome sequences to classify them into species.

## Results

The Multinomial Naive Bayes classifier achieves the following accuracies:

- **Chimpanzees:** 99.8%
- **Humans:** 98.6%
- **Dogs:** 92%

These results demonstrate the robustness of the model and its ability to differentiate genome sequences effectively.

## Future Scope

- Expand the dataset to include genome sequences from additional species.
- Explore other machine learning algorithms like Support Vector Machines (SVM) and Neural Networks for improved accuracy.
- Enhance the user interface for better usability.
- Implement a real-time genome sequence analyzer using APIs.

## Contributing

Contributions are welcome! To contribute:

1. Fork this repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to explore, modify, and extend Gene_ML to suit your needs. For any issues or suggestions, please open an issue in the repository or contact the project maintainer.

---

**Maintainer:** Angad Singh  
[GitHub](https://github.com/Angad-2002) | [LinkedIn](https://linkedin.com/in/angad2002)
