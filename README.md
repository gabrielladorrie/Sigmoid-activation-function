# Sigmoid Activation Function Visualisation

## 1. Project Overview

This project develops an interactive web application to visualise the **Sigmoid Activation Function** using Python and Streamlit.

The application allows users to adjust input values through an interactive slider and observe how the Sigmoid function transforms the input into an output between 0 and 1.

The graph and calculated output update automatically whenever the selected input changes.

## 2. Project Objectives

- To understand the behaviour of the Sigmoid activation function.
- To visualise the relationship between input and output values.
- To demonstrate how the Sigmoid function transforms input values into a range between 0 and 1.
- To develop an interactive web application using Python and Streamlit.

## 3. Tools and Technologies

| Tool | Purpose |
|---|---|
| Python | Main programming language |
| Streamlit | Develop the interactive web application |
| NumPy | Generate input values and calculate Sigmoid outputs |
| Matplotlib | Create and display the Sigmoid graph |
| GitHub | Source code management and documentation |
| Streamlit Community Cloud | Deploy the application online |

## 4. Sigmoid Activation Function

The Sigmoid activation function, also known as the Logistic function, is commonly used in artificial neural networks, particularly for binary classification.

Its mathematical formula is:

\[
f(x)=\frac{1}{1+e^{-x}}
\]

Where:
- \(x\) represents the input value.
- \(e\) is the mathematical constant approximately equal to 2.71828.
- \(f(x)\) represents the output value.

### Function Behaviour

- **Negative input:** The output approaches 0.
- **Zero input:** The output equals 0.5.
- **Positive input:** The output approaches 1.

### Example Outputs

| Input (x) | Sigmoid Output |
|---:|---:|
| -5 | 0.0067 |
| -2 | 0.1192 |
| 0 | 0.5000 |
| 1 | 0.7311 |
| 2 | 0.8808 |
| 5 | 0.9933 |

## 5. Application Features

### 5.1 Interactive Input Slider
Users can adjust the input value from -6 to 6 using the Streamlit slider.

### 5.2 Dynamic Graph Visualisation
The Sigmoid curve is displayed using Matplotlib. The graph updates automatically when the input value changes.

### 5.3 Selected Input Indicator
A red point highlights the selected input and its corresponding output on the graph.

### 5.4 Real-Time Output Display
The application calculates and displays the Sigmoid output based on the selected input value.

### 5.5 User-Friendly Interface
The application provides a clear title, graph labels, legend, grid, input slider, and output display.

## 6. Application Screenshot

The screenshot below shows the developed Sigmoid Activation Function web application.

![Sigmoid Activation Function Application](images/sigmoid_app.png)

**Figure 1: Sigmoid Activation Function Web Application**

### Screenshot Interpretation

Based on the displayed application:

- Selected input value: **1.00**
- Calculated Sigmoid output: **0.7311**
- The red point indicates the selected input and its corresponding output.
- The output demonstrates how the Sigmoid function transforms an input of 1 into a value between 0 and 1.

## 7. Project Structure

```text
Sigmoid-activation-function/
│
├── sigmoid_app.py
├── requirements.txt
├── README.md
│
└── images/
    └── sigmoid_app.png
```

| File | Description |
|---|---|
| `sigmoid_app.py` | Main Python script containing the Sigmoid calculation, Streamlit interface, and graph visualisation |
| `requirements.txt` | Lists the required Python libraries |
| `README.md` | Project documentation and setup instructions |
| `images/sigmoid_app.png` | Screenshot of the application |

The application is organised in a separate Python file, making it independent and easy to maintain, execute, and update.

## 8. Installation and Setup

### Step 1: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 2: Navigate to the Project Folder

```bash
cd Sigmoid-activation-function
```

### Step 3: Install Required Libraries

```bash
pip install -r requirements.txt
```

### Step 4: Run the Application

```bash
streamlit run sigmoid_app.py
```

The application will open in your default web browser.

## 9. Requirements

The required Python libraries are:

```text
streamlit
numpy
matplotlib
```

## 10. Deployment

The application is deployed using **Streamlit Community Cloud**, allowing users to access the web application through a browser.

### Deployment Steps

1. Upload the project files to the GitHub repository.
2. Visit [Streamlit Community Cloud](https://share.streamlit.io/).
3. Connect your GitHub account.
4. Select the Sigmoid project repository.
5. Set `sigmoid_app.py` as the main application file.
6. Click Deploy.
7. Test the application to ensure that the slider, graph, and output display work correctly.

**Live Streamlit Application:**

https://sigmoid-activation-function-l23fzkpqygv3v3bytn4tsn.streamlit.app/

**GitHub Repository:** Add your Sigmoid GitHub repository URL here.

## 11. Learning Outcomes

Through this project, users can understand:

- The mathematical concept of the Sigmoid activation function.
- How negative input values produce outputs closer to 0.
- How positive input values produce outputs closer to 1.
- How the Sigmoid function is used in binary classification.
- How Python libraries can be used to develop interactive machine learning visualisations.

## 12. Conclusion

The Sigmoid Activation Function application demonstrates how the Sigmoid function transforms input values into outputs between 0 and 1 through an interactive visualisation.

By using Streamlit, users can adjust input values and immediately observe the corresponding changes in the graph and calculated output.

The application provides an effective visual learning experience for understanding the Sigmoid activation function in artificial neural networks.

## 13. Author

Developed as part of an academic assignment on Neural Networks and Deep Learning.

## 14. GitHub Repository Topics

`python` `streamlit` `sigmoid` `activation-function` `neural-networks` `deep-learning` `machine-learning` `data-visualisation`
