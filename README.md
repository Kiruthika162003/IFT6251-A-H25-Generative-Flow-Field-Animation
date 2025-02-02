# **Generative Flow Field Animation**

## **About the Project**
This repository contains a **generative animation** that uses **Perlin noise-driven flow fields** to animate geometric shapes (circles, triangles, and squares). The movement is smooth and organic, creating a visually appealing effect.

## **How to Run**
### **In Google Colab**
1. Open Google Colab.
2. Copy & paste the provided Python script into a new notebook cell.
3. Run the cell to generate and display the animation as a GIF.

### **On Your Local Machine**
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/generative-flow-field.git
   cd generative-flow-field
   ```
2. Install dependencies:
   ```bash
   pip install matplotlib numpy noise imageio moviepy
   ```
3. Run the script:
   ```bash
   python animation.py
   ```
4. The script will generate and save an `output.gif` that you can view.

## **Concepts Used**
- **Flow Field**: Uses Perlin noise to generate structured, natural motion.
- **Geometric Shapes**: Circles, triangles, and squares change dynamically.
- **Randomness & Noise**: Ensures smooth, non-repetitive motion.
- **GIF Output**: Automatically generated and displayed in Google Colab or saved locally.

## **Repository Structure**
```
/ generative-flow-field
│── animation.py       # Main script generating the animation
│── README.md          # Project documentation
│── output.gif         # Sample animation output
```

