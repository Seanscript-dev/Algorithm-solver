# 🎯 Project Overview
<img width="1919" height="987" alt="image" src="https://github.com/user-attachments/assets/98fa031e-c205-4515-b657-153fe61da698" />

# AlgoSolver

> Algorithm Visualization Laboratory — visualize sorting algorithms step by step.

AlgoSolver is a desktop-based algorithm visualization application built with Python. It provides an interactive way to understand how sorting algorithms work by displaying the dataset as animated bars and highlighting comparisons, movements, and swaps in real time.

The project is designed to make algorithm behavior easier to understand through visual feedback rather than relying only on traditional code or theoretical explanations.

---

## ✨ Features

- 📊 Interactive sorting visualization
- 🎨 Modern dark-themed desktop interface
- 🔢 Manual dataset input
- 🎲 Random dataset generation
- 🔄 Dataset reset functionality
- ⚡ Adjustable animation speed
- 📈 Real-time comparison counter
- 🔁 Real-time swap counter
- 👣 Step counter
- 📝 Activity/event logging
- 🖥️ Fullscreen mode
- ⌨️ `F11` fullscreen shortcut
- 🌌 Optional technology-themed background
- 📐 Supports datasets of up to 40 elements

---

## 🧠 Supported Algorithms

AlgoSolver currently supports:

| Algorithm | Average Time | Worst Time | Space |
|---|---:|---:|---:|
| Bubble Sort | O(n²) | O(n²) | O(1) |
| Selection Sort | O(n²) | O(n²) | O(1) |
| Insertion Sort | O(n²) | O(n²) | O(1) |
| Shell Sort | Depends on gap sequence | Depends on gap sequence | O(1) |
| Merge Sort | O(n log n) | O(n log n) | O(n) |

Each algorithm is visualized using colored bars representing the values in the dataset.

### Visualization Colors

- 🔵 **Blue** — Normal element
- 🟦 **Cyan** — Currently active element
- 🟡 **Yellow** — Elements being compared
- 🔴 **Pink/Red** — Elements being swapped or moved
- 🟢 **Green** — Sorted elements

---

## 🖥️ Interface

AlgoSolver is organized into several sections:

### Dataset Controls

Enter a custom dataset such as:

```text
12, 4, 8, 2, 10, 6

Or generate a random dataset with one click.

Algorithm Controls

Choose between:

Bubble Sort
Selection Sort
Insertion Sort
Shell Sort
Merge Sort

The animation speed can also be adjusted before or during visualization.

Visualization

The main visualization area displays each number as a vertical bar.

As the algorithm executes, the bars change state to show what the algorithm is currently doing.

Statistics

The application tracks:

Comparisons
Swaps
Steps

These statistics provide additional insight into how much work each algorithm performs.

Activity Log

The activity panel records important events during execution, such as:

Dataset loaded: 10 elements.
Running Bubble Sort...
Swap 8 ↔ 4
Swap 10 ↔ 6
Sorting completed successfully.
🛠️ Technologies

## AlgoSolver is built using:

Python
PySide6
Qt
Object-Oriented Programming
Sorting Algorithms
GUI-based visualization

The original prototype was developed using Tkinter, with the interface later being redesigned around PySide6 for a more modern desktop experience.

## 📦 Installation
1. Clone the repository
git clone https://github.com/Seanscript-dev/Algorithm-solver.git
2. Enter the project directory
cd Algorithm-solver
3. Install dependencies

If the project contains a requirements.txt file:

pip install -r requirements.txt

Otherwise, install PySide6 manually:

pip install PySide6

If the application uses a background image through Pillow:

pip install pillow
4. Run the application

Run the project's main Python file:

python main.py

Replace main.py with the actual entry-point filename if your repository uses a different name.

🚀 How to Use
Step 1 — Create a Dataset

Enter numbers separated by commas:

25, 10, 42, 7, 18, 31, 4

Or use the Random button.

Step 2 — Choose an Algorithm

Select the algorithm you want to visualize from the algorithm selector.

Step 3 — Adjust Animation Speed

Use the speed control to make the visualization slower for studying individual operations or faster for larger datasets.

Step 4 — Start Sorting

Press:

▶ Start Sorting

The visualization will begin.

Step 5 — Analyze the Statistics

After sorting, compare the number of:

Comparisons
Swaps
Steps

This can help demonstrate the practical differences between sorting algorithms.

🎓 Educational Purpose

AlgoSolver is primarily designed as an educational tool.

Instead of simply displaying:

data.sort()

the application exposes the individual operations performed by a sorting algorithm.

For example, Bubble Sort repeatedly compares neighboring elements:

[8] [3] [5] [1]

 ↓ compare

[8] [3]

 ↓ swap

[3] [8] [5] [1]

This makes concepts such as comparisons, swaps, iterations, and algorithm complexity easier to understand.

 📊 Why Visualization?

Sorting algorithms can be difficult to understand when presented only as source code.

Visualization provides an immediate representation of:

How elements move
Which elements are being compared
When swaps occur
How the dataset gradually becomes sorted
How different algorithms behave

This makes AlgoSolver useful for students, beginners, and anyone learning fundamental algorithms.

🏗️ Project Structure

A typical project structure may look like:

Algorithm-solver/
│
├── main.py
├── README.md
├── requirements.txt
├── tech.jpg
└── ...

The exact structure may vary depending on the current version of the project.

🔮 Future Improvements

Possible future improvements include:

 Quick Sort visualization
 Heap Sort visualization
 Counting Sort visualization
 Radix Sort visualization
 Algorithm complexity panel
 Side-by-side algorithm comparison
 Sorting performance benchmarks
 Dataset presets
 Export visualization statistics
 Custom visualization themes
 Pause/resume animation
 Improved accessibility
 More detailed algorithm explanations
 Code-view panel showing the algorithm being executed
🤝 Contributing

Contributions, suggestions, and improvements are welcome.

If you would like to contribute:

Fork the repository.
Create a new branch.
git checkout -b feature/my-feature
Make your changes.
Commit them.
git commit -m "Add my feature"
Push the branch.
git push origin feature/my-feature
Open a Pull Request.
📄 License

Add your preferred license here.

For example:

MIT License

If the repository does not currently have a license, choose one before publishing this section.

👨‍💻 Author

Created by Seanscript-dev

GitHub:

https://github.com/Seanscript-dev

⭐ Support

If you find AlgoSolver useful for learning algorithms, consider giving the repository a ⭐ on GitHub.
algorithms.py: A module containing the Python implementations of the various sorting algorithms.

README.md: The project's documentation file (currently minimal in this repository).

To contribute or learn from the code, the best approach is to clone the repository and examine the seanscriptALGO directory and the AlgoSolver.spec file, which may contain the main source code and build configuration.
