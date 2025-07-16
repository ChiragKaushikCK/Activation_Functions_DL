# Activation_Functions_DL

<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy" />
  <img src="https://img.shields.io/badge/Matplotlib-EE6633?style=for-the-badge&logo=matplotlib&logoColor=white" alt="Matplotlib" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter" />
</div>

<h1 align="center" style="color: #FF5733; font-family: 'Segoe UI', sans-serif; font-size: 3.5em; text-shadow: 2px 2px 4px rgba(0,0,0,0.2);">
  <br>
  <a href="https://github.com/your-username/activation-functions-visualization">
    <img src="https://placehold.co/600x200/FF5733/FFFFFF?text=Activation+Functions" alt="Activation Functions Banner" style="border-radius: 15px; box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);">
  </a>
  <br>
  🌟 Linear & Non-Linear Activation Functions 🌟
  <br>
</h1>

<p align="center" style="font-size: 1.2em; color: #555; max-width: 800px; margin: 0 auto; line-height: 1.6;">
  Unlock the magic behind neural networks with this **Linear & Non-Linear Activation Functions** Jupyter Notebook! This project offers a vibrant visual exploration of fundamental activation functions like **Linear, ReLU, Sigmoid, and Tanh**. Understand their behavior, impact on neural network capabilities, and why non-linearity is crucial for deep learning. Perfect for students, researchers, and anyone curious about the building blocks of AI! ✨
</p>

<br>

<details style="background-color: #FFF3E0; border-left: 5px solid #FF5733; padding: 15px; border-radius: 8px; margin: 20px auto; max-width: 700px; box-shadow: 0 2px 10px rgba(0,0,0,0.1);">
  <summary style="font-size: 1.3em; font-weight: bold; color: #333; cursor: pointer;">Table of Contents</summary>
  <ol style="list-style-type: decimal; padding-left: 25px; line-height: 1.8;">
    <li><a href="#about-the-project" style="color: #FF5733; text-decoration: none;">📚 About The Project</a></li>
    <li><a href="#activation-functions-explored" style="color: #FF5733; text-decoration: none;">💡 Activation Functions Explored</a></li>
    <li><a href="#features" style="color: #FF5733; text-decoration: none;">🎯 Features</a></li>
    <li><a href="#prerequisites" style="color: #FF5733; text-decoration: none;">🛠️ Prerequisites</a></li>
    <li><a href="#how-to-run" style="color: #FF5733; text-decoration: none;">📋 How to Run</a></li>
    <li><a href="#example-output" style="color: #FF5733; text-decoration: none;">📊 Example Output</a></li>
    <li><a href="#code-breakdown" style="color: #FF5733; text-decoration: none;">🧠 Code Breakdown</a></li>
    <li><a href="#customization-ideas" style="color: #FF5733; text-decoration: none;">🌈 Customization Ideas</a></li>
    <li><a href="#contribute" style="color: #FF5733; text-decoration: none;">🤝 Contribute</a></li>
  </ol>
</details>

---

<h2 id="about-the-project" style="color: #333; font-family: 'Segoe UI', sans-serif; font-size: 2.5em; border-bottom: 3px solid #FFD700; padding-bottom: 10px;">
  📚 About The Project
</h2>
<p style="font-size: 1.1em; color: #444; line-height: 1.6;">
  This project offers a clear and concise visualization of various **activation functions** commonly used in artificial neural networks. [cite: uploaded:linear_and_Non_Linear_Activation_Function.ipynb] Understanding activation functions is crucial as they introduce non-linearity into the network, enabling it to learn complex patterns and relationships in data. Without non-linear activation functions, a neural network, no matter how many layers it has, would behave like a simple linear regression model. This notebook uses `NumPy` for numerical operations and `Matplotlib` for plotting, making the concepts easy to grasp visually.
</p>

---

<h2 id="activation-functions-explored" style="color: #333; font-family: 'Segoe UI', sans-serif; font-size: 2.5em; border-bottom: 3px solid #FFD700; padding-bottom: 10px;">
  💡 Activation Functions Explored
</h2>
<p style="font-size: 1.1em; color: #444; line-height: 1.6;">
  The notebook provides detailed visualizations and implementations for the following activation functions:
</p>
<ul style="list-style-type: none; padding: 0; font-size: 1.1em; color: #444;">
  <li style="margin-bottom: 15px; background-color: #E0F7FA; padding: 10px 15px; border-radius: 8px; box-shadow: 0 1px 5px rgba(0,0,0,0.05);">
    <strong style="color: #00BCD4;">1. Linear Function ($y = mx + b$):</strong>
    <p style="margin-top: 5px;">A simple function where the output is directly proportional to the input. While not commonly used in hidden layers of deep networks due to its inability to introduce non-linearity, it's fundamental for understanding the basics and sometimes used in the output layer for regression tasks.</p>
  </li>
  <li style="margin-bottom: 15px; background-color: #E0F7FA; padding: 10px 15px; border-radius: 8px; box-shadow: 0 1px 5px rgba(0,0,0,0.05);">
    <strong style="color: #00BCD4;">2. ReLU (Rectified Linear Unit) Function ($y = \text{max}(0, x)$):</strong>
    <p style="margin-top: 5px;">One of the most popular activation functions in deep learning. It outputs the input directly if it's positive, otherwise, it outputs zero. Its simplicity and computational efficiency make it widely used in hidden layers.</p>
  </li>
  <li style="margin-bottom: 15px; background-color: #E0F7FA; padding: 10px 15px; border-radius: 8px; box-shadow: 0 1px 5px rgba(0,0,0,0.05);">
    <strong style="color: #00BCD4;">3. Sigmoid Function ($y = 1 / (1 + e^{-x})$):</strong>
    <p style="margin-top: 5px;">Also known as the logistic function, it squashes input values into a range between 0 and 1. Historically popular in output layers for binary classification problems, though it suffers from vanishing gradients in deep networks.</p>
  </li>
  <li style="margin-bottom: 15px; background-color: #E0F7FA; padding: 10px 15px; border-radius: 8px; box-shadow: 0 1px 5px rgba(0,0,0,0.05);">
    <strong style="color: #00BCD4;">4. Tanh (Hyperbolic Tangent) Function ($y = (e^x - e^{-x}) / (e^x + e^{-x})$):</strong>
    <p style="margin-top: 5px;">Similar to Sigmoid but squashes input values into a range between -1 and 1. It's zero-centered, which often helps with training stability compared to Sigmoid, and was a popular choice before ReLU's widespread adoption.</p>
  </li>
</ul>

---

<h2 id="features" style="color: #333; font-family: 'Segoe UI', sans-serif; font-size: 2.5em; border-bottom: 3px solid #FFD700; padding-bottom: 10px;">
  🎯 Features
</h2>
<ul style="list-style-type: none; padding: 0; font-size: 1.1em; color: #444;">
  <li style="margin-bottom: 15px; background-color: #FFF8E1; padding: 10px 15px; border-radius: 8px; box-shadow: 0 1px 5px rgba(0,0,0,0.05);">
    <strong style="color: #FF5733;">📈 Interactive Visualizations:</strong> See how each activation function transforms input values through clear plots. [cite: uploaded:linear_and_Non_Linear_Activation_Function.ipynb]
  </li>
  <li style="margin-bottom: 15px; background-color: #FFF8E1; padding: 10px 15px; border-radius: 8px; box-shadow: 0 1px 5px rgba(0,0,0,0.05);">
    <strong style="color: #FF5733;">✍️ Simple Implementations:</strong> Each function is implemented from scratch using NumPy for better understanding. [cite: uploaded:linear_and_Non_Linear_Activation_Function.ipynb]
  </li>
  <li style="margin-bottom: 15px; background-color: #FFF8E1; padding: 10px 15px; border-radius: 8px; box-shadow: 0 1px 5px rgba(0,0,0,0.05);">
    <strong style="color: #FF5733;">🔍 Side-by-Side Comparisons:</strong> Plots are arranged for easy comparison of different activation functions. [cite: uploaded:linear_and_Non_Linear_Activation_Function.ipynb]
  </li>
  <li style="margin-bottom: 15px; background-color: #FFF8E1; padding: 10px 15px; border-radius: 8px; box-shadow: 0 1px 5px rgba(0,0,0,0.05);">
    <strong style="color: #FF5733;">📚 Educational Resource:</strong> Well-commented code and clear explanations make it an ideal learning tool for deep learning fundamentals.
  </li>
</ul>

---

<h2 id="prerequisites" style="color: #333; font-family: 'Segoe UI', sans-serif; font-size: 2.5em; border-bottom: 3px solid #FFD700; padding-bottom: 10px;">
  🛠️ Prerequisites
</h2>
<p style="font-size: 1.1em; color: #444; line-height: 1.6;">
  To run this project, ensure you have the following installed:
</p>
<ul style="list-style-type: disc; padding-left: 20px; font-size: 1.1em; color: #444;">
  <li><strong style="color: #FF5733;">Python 3.x</strong></li>
  <li><strong style="color: #FF5733;">Jupyter Notebook</strong> (or JupyterLab, Google Colab)</li>
  <li>Required Libraries:
    <pre style="background-color: #2D2D2D; color: #E0E0E0; padding: 15px; border-radius: 8px; overflow-x: auto; font-family: 'Fira Code', monospace; font-size: 0.95em; box-shadow: 0 2px 10px rgba(0,0,0,0.15);"><code>pip install numpy matplotlib</code></pre>
  </li>
</ul>

---

<h2 id="how-to-run" style="color: #333; font-family: 'Segoe UI', sans-serif; font-size: 2.5em; border-bottom: 3px solid #FFD700; padding-bottom: 10px;">
  📋 How to Run
</h2>
<ol style="list-style-type: decimal; padding-left: 20px; font-size: 1.1em; color: #444; line-height: 1.8;">
  <li style="margin-bottom: 10px;">
    <strong style="color: #FF5733;">Download the Notebook:</strong>
    <p style="margin-top: 5px;">Download <code>linear_and_Non_Linear_Activation_Function.ipynb</code> from this repository.</p>
    <p style="margin-top: 5px;">Alternatively, open it directly in <a href="https://colab.research.google.com/" style="color: #FF5733; text-decoration: none;">Google Colab</a> for a zero-setup experience.</p>
  </li>
  <li style="margin-bottom: 10px;">
    <strong style="color: #FF5733;">Install Dependencies:</strong>
    <pre style="background-color: #2D2D2D; color: #E0E0E0; padding: 15px; border-radius: 8px; overflow-x: auto; font-family: 'Fira Code', monospace; font-size: 0.95em; box-shadow: 0 2px 10px rgba(0,0,0,0.15);"><code>pip install numpy matplotlib</code></pre>
  </li>
  <li style="margin-bottom: 10px;">
    <strong style="color: #FF5733;">Run the Notebook:</strong>
    <p style="margin-top: 5px;">Open <code>linear_and_Non_Linear_Activation_Function.ipynb</code> in Jupyter or Colab.</p>
    <p style="margin-top: 5px;">Execute each cell sequentially to visualize the activation functions!</p>
  </li>
</ol>

---

<h2 id="example-output" style="color: #333; font-family: 'Segoe UI', sans-serif; font-size: 2.5em; border-bottom: 3px solid #FFD700; padding-bottom: 10px;">
  📊 Example Output
</h2>
<p style="font-size: 1.1em; color: #444; line-height: 1.6;">
  The notebook will generate plots for each activation function, similar to the examples below:
</p>

<div style="text-align: center; background-color: #F8F8F8; padding: 15px; border-radius: 10px; box-shadow: 0 4px 15px rgba(0,0,0,0.1); margin-top: 20px; display: flex; flex-wrap: wrap; justify-content: center; gap: 20px;">
  <div style="flex: 1 1 45%; min-width: 300px;">
    <h3 style="color: #FF5733; font-size: 1.5em; margin-bottom: 10px;">Linear & ReLU Functions:</h3>
    <img src="https://placehold.co/400x250/FFDDC1/333333?text=Linear+%26+ReLU+Plot" alt="Linear and ReLU Plot Placeholder" style="width: 100%; height: auto; border-radius: 8px; border: 1px solid #ddd;">
    <p style="font-size: 0.9em; color: #666; margin-top: 10px;">Comparison of Linear and ReLU activation functions.</p>
  </div>
  <div style="flex: 1 1 45%; min-width: 300px;">
    <h3 style="color: #FF5733; font-size: 1.5em; margin-bottom: 10px;">Sigmoid & Tanh Functions:</h3>
    <img src="https://placehold.co/400x250/C1FFDD/333333?text=Sigmoid+%26+Tanh+Plot" alt="Sigmoid and Tanh Plot Placeholder" style="width: 100%; height: auto; border-radius: 8px; border: 1px solid #ddd;">
    <p style="font-size: 0.9em; color: #666; margin-top: 10px;">Comparison of Sigmoid and Tanh activation functions.</p>
  </div>
</div>

---

<h2 id="code-breakdown" style="color: #333; font-family: 'Segoe UI', sans-serif; font-size: 2.5em; border-bottom: 3px solid #FFD700; padding-bottom: 10px;">
  🧠 Code Breakdown
</h2>
<p style="font-size: 1.1em; color: #444; line-height: 1.6;">
  Here are the core implementations of the activation functions:
</p>

<h3 style="color: #FF5733; font-size: 1.8em; margin-top: 25px;">Linear Function:</h3>
<pre style="background-color: #2D2D2D; color: #E0E0E0; padding: 15px; border-radius: 8px; overflow-x: auto; font-family: 'Fira Code', monospace; font-size: 0.95em; box-shadow: 0 2px 10px rgba(0,0,0,0.15);"><code><span style="color: #569CD6;">def</span> <span style="color: #6A9955;">linear_function</span>(<span style="color: #9CDCFE;">x</span>, <span style="color: #9CDCFE;">m</span><span style="color: #CE9178;">=</span><span style="color: #B5CEA8;">1</span>, <span style="color: #9CDCFE;">b</span><span style="color: #CE9178;">=</span><span style="color: #B5CEA8;">0</span>):
    <span style="color: #C586C0;">return</span> <span style="color: #9CDCFE;">m</span> <span style="color: #CE9178;">*</span> <span style="color: #9CDCFE;">x</span> <span style="color: #CE9178;">+</span> <span style="color: #9CDCFE;">b</span></code></pre>

<h3 style="color: #FF5733; font-size: 1.8em; margin-top: 25px;">ReLU Function:</h3>
<pre style="background-color: #2D2D2D; color: #E0E0E0; padding: 15px; border-radius: 8px; overflow-x: auto; font-family: 'Fira Code', monospace; font-size: 0.95em; box-shadow: 0 2px 10px rgba(0,0,0,0.15);"><code><span style="color: #569CD6;">def</span> <span style="color: #6A9955;">relu_function</span>(<span style="color: #9CDCFE;">x</span>):
    <span style="color: #C586C0;">return</span> <span style="color: #569CD6;">np.maximum</span>(<span style="color: #B5CEA8;">0</span>, <span style="color: #9CDCFE;">x</span>)</code></pre>

<h3 style="color: #FF5733; font-size: 1.8em; margin-top: 25px;">Sigmoid Function:</h3>
<pre style="background-color: #2D2D2D; color: #E0E0E0; padding: 15px; border-radius: 8px; overflow-x: auto; font-family: 'Fira Code', monospace; font-size: 0.95em; box-shadow: 0 2px 10px rgba(0,0,0,0.15);"><code><span style="color: #569CD6;">def</span> <span style="color: #6A9955;">sigmoid</span>(<span style="color: #9CDCFE;">x</span>):
    <span style="color: #C586C0;">return</span> <span style="color: #B5CEA8;">1</span> <span style="color: #CE9178;">/</span> (<span style="color: #B5CEA8;">1</span> <span style="color: #CE9178;">+</span> <span style="color: #569CD6;">np.exp</span>(<span style="color: #CE9178;">-</span><span style="color: #9CDCFE;">x</span>))</code></pre>

<h3 style="color: #FF5733; font-size: 1.8em; margin-top: 25px;">Tanh Function:</h3>
<pre style="background-color: #2D2D2D; color: #E0E0E0; padding: 15px; border-radius: 8px; overflow-x: auto; font-family: 'Fira Code', monospace; font-size: 0.95em; box-shadow: 0 2px 10px rgba(0,0,0,0.15);"><code><span style="color: #569CD6;">def</span> <span style="color: #6A9955;">tanh</span>(<span style="color: #9CDCFE;">x</span>):
    <span style="color: #C586C0;">return</span> (<span style="color: #569CD6;">np.exp</span>(<span style="color: #9CDCFE;">x</span>) <span style="color: #CE9178;">-</span> <span style="color: #569CD6;">np.exp</span>(<span style="color: #CE9178;">-</span><span style="color: #9CDCFE;">x</span>)) <span style="color: #CE9178;">/</span> (<span style="color: #569CD6;">np.exp</span>(<span style="color: #9CDCFE;">x</span>) <span style="color: #CE9178;">+</span> <span style="color: #569CD6;">np.exp</span>(<span style="color: #CE9178;">-</span><span style="color: #9CDCFE;">x</span>))</code></pre>

---

<h2 id="customization-ideas" style="color: #333; font-family: 'Segoe UI', sans-serif; font-size: 2.5em; border-bottom: 3px solid #FFD700; padding-bottom: 10px;">
  🌈 Customization Ideas
</h2>
<p style="font-size: 1.1em; color: #444; line-height: 1.6;">
  Want to expand your understanding of activation functions? Here are some ideas:
</p>
<ul style="list-style-type: none; padding: 0; font-size: 1.1em; color: #444;">
  <li style="margin-bottom: 15px; background-color: #E0F7FA; padding: 10px 15px; border-radius: 8px; box-shadow: 0 1px 5px rgba(0,0,0,0.05);">
    <strong style="color: #00BCD4;">📈 Explore Derivatives:</strong> Add plots for the derivatives of each non-linear activation function. This is crucial for understanding backpropagation.
  </li>
  <li style="margin-bottom: 15px; background-color: #E0F7FA; padding: 10px 15px; border-radius: 8px; box-shadow: 0 1px 5px rgba(0,0,0,0.05);">
    <strong style="color: #00BCD4;">🧪 More Functions:</strong> Implement and visualize other activation functions like Leaky ReLU, ELU, Swish, or Softmax.
  </li>
  <li style="margin-bottom: 15px; background-color: #E0F7FA; padding: 10px 15px; border-radius: 8px; box-shadow: 0 1px 5px rgba(0,0,0,0.05);">
    <strong style="color: #00BCD4;">📊 Network Impact:</strong> Create a very simple neural network and demonstrate how different activation functions affect its ability to learn a non-linear decision boundary.
  </li>
  <li style="margin-bottom: 15px; background-color: #E0F7FA; padding: 10px 15px; border-radius: 8px; box-shadow: 0 1px 5px rgba(0,0,0,0.05);">
    <strong style="color: #00BCD4;">🎨 Interactive Widgets:</strong> Use Jupyter widgets to create sliders for changing parameters (e.g., `m` and `b` for linear function, or `alpha` for Leaky ReLU) in real-time.
  </li>
</ul>

---

<h2 id="contribute" style="color: #333; font-family: 'Segoe UI', sans-serif; font-size: 2.5em; border-bottom: 3px solid #FFD700; padding-bottom: 10px;">
  🤝 Contribute
</h2>
<p align="center" style="font-size: 1.2em; color: #555; max-width: 800px; margin: 0 auto; line-height: 1.6;">
  Contributions are always welcome! If you have ideas for new activation functions to add, improvements to existing visualizations, or any other enhancements, please feel free to open an issue or submit a pull request. Let's illuminate the concepts of deep learning together! 💡
</p>
<p align="center" style="font-size: 1.2em; color: #555; max-width: 800px; margin: 15px auto 0; line-height: 1.6;">
  Star this repo if you find it helpful! ⭐
</p>
<p align="center" style="font-size: 1em; color: #777; margin-top: 30px;">
  Created with 💖 by Chirag
</p>
