
# Binary Tree Visualizer 🌳

A web-based visualization tool for fundamental tree data structures, built with D3.js

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## ✨ Features

### Supported Data Structures
- **Binary Tree Visualization**
- **Max-Heap Visualization**
  - Automatic heapification of input array
  - Parent-child relationship highlighting
- **Binary Search Tree (BST) Visualization**
  - Automatic sorting and BST construction
  - Strict duplicate value prevention

### Key Functionalities
- 🎨 Modern dark theme UI with purple accents
- 🔢 Interactive array input system
- 🖱️ Click-to-highlight node relationships
- 🚫 Input validation for duplicate values
- 📊 Simultaneous tree and array representation
- 🔄 Real-time visualization updates


## 📥 Installation
1. Clone the repository:
```bash
git clone https://github.com/<your-username>/tree-visualizer.git
```
2. Navigate to project directory:
```bash
cd tree-visualizer
```

## 🚀 Usage
1. Open `index.html` in a modern web browser
2. Enter numbers separated by spaces or commas:
   - Example: `10, 20, 60, 30, 70, 40, 50`
3. Choose visualization type:
   - **Binary Tree**: Direct mapping of input sequence
   - **Max-Heap**: Automatically heapified structure
   - **BST**: Sorted binary search tree construction

## 🧠 Implementation Details

### Core Algorithms
1. **Binary Tree**
   - Sequential node placement using level-order traversal
   - Dynamic spacing calculation based on tree depth

2. **Max-Heap**
   - Heapify algorithm (O(n) implementation)
   - Bottom-up construction with sift-down operations
   - Array-based heap representation

3. **Binary Search Tree**
   - Constructed from sorted array using divide-and-conquer
   - Midpoint selection for balanced tree creation
   - In-order traversal validation

### Visualization Engine
- **D3.js** powered dynamic SVG rendering
- Adaptive node positioning based on tree depth
- Interactive elements with hover/click states
- Smooth transitions for structural changes

## 📦 Dependencies
- [D3.js v5](https://d3js.org/) (Loaded via CDN)
- Modern web browser with ES6 support

## 🤝 Contributing
Contributions are welcome! Please follow these steps:
1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License
Distributed under the MIT License. See `LICENSE` for more information.

## 🙏 Acknowledgements
- D3.js visualization library
- Classic CLRS algorithms book for heap reference
- Inspired by visualgo.net's approach to algorithm visualization

