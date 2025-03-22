# 🚀 2D Point Location using the Trapezoidal Map Method 🚀
Welcome to the 2D Point Location project! 👋
This project implements the trapezoidal map method to locate a point in a 2D plane using a randomized incremental algorithm. 🗺️
The program allows you to manually input segments, generate random segments, and visualize the process of building the trapezoidal map and locating a point. 🎨

# 📋 Table of Contents
Algorithm Overview

How It Works

Features

Usage

Complexity Analysis

# 🧠 Algorithm Overview
The trapezoidal map method is a geometric algorithm used to partition a 2D plane into trapezoids (or triangles) based on a set of non-intersecting line segments. 🗺️
The goal is to quickly determine which trapezoid contains a given query point. 🔍

The algorithm works in two main steps:

Build the Trapezoidal Map: Construct a map by incrementally adding segments in random order, splitting the plane into trapezoids.

Point Location: Use a search structure (DAG) to efficiently locate the trapezoid containing the query point.

# 🛠️ How It Works
Input: A set of non-intersecting line segments and a query point. 📏

Trapezoidal Map Construction:

Start with a bounding box that contains all segments.

Add segments one by one in random order, splitting the existing trapezoids into smaller trapezoids.

Update the search structure (DAG) to reflect the new trapezoids.

Point Location:

Traverse the DAG to find the trapezoid containing the query point.

The search is efficient, with a complexity of O(log n).

# ✨ Features
Randomized Incremental Algorithm: Segments are added in random order, ensuring an expected O(n log n) construction time. 🎲

Visualization: The program provides visualizations of the trapezoidal map construction and point location process. 🖼️

Interactive Input: You can manually draw segments or generate random ones. 🖱️

Efficient Query: Locate a point in O(log n) time using the search structure. 🔍

# 🚀 Usage
Run the Program: Open the main file nitsch_sankowska_kod in your preferred Python environment (e.g., PyCharm, VSCode). 🖥️

Input Segments:

Manually draw segments using the mouse. 🖱️

Or generate random segments using generate_segments(n, x_range, y_range).

Visualize:

Watch the trapezoidal map being built step by step. 🎥

Locate a point and see which trapezoid it falls into. 🔍

# ⏱️ Complexity Analysis
Construction Time: O(n log n) expected time to build the trapezoidal map. 🏗️

Query Time: O(log n) to locate a point in the map. 🔍

Thanks for checking out our project! 😊
If you have any questions or suggestions, feel free to open an issue or contact us! 📩

Authors: Maja Sankowska, Karolina Nitsch

