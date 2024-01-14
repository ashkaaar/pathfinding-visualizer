# Pathfinding Algorithm Visualizer

## Description
This project is a visualizer for pathfinding algorithms. It allows you to choose an algorithm, set a start and end point, and place barriers on the grid. When you run the algorithm, it will visually show you the path it takes to reach the end point.

## Features
- Supports multiple pathfinding algorithms such as A*, Dijkstra's, and Breadth-First Search.
- Interactive grid to set start and end points, and to place barriers.
- Step-by-step visualization of the pathfinding process.

## Future Features
- **Custom Grid Sizes:** Allow users to customize the size of the grid, providing flexibility for different scenarios and preferences.
- **Speed Control:** Implement a speed control option for visualization, enabling users to adjust the speed of the pathfinding algorithm, making it easier to follow the process or speed it up for quick results.
- **Algorithm Comparisons:** Introduce a feature to compare the performance of different algorithms simultaneously on the same grid. This will help users understand the strengths and weaknesses of each algorithm.
- **Save/Load Grid State:** Enable users to save their current grid state and reload it later. This feature can be useful for revisiting specific scenarios or sharing interesting setups with others.
- **Additional Algorithms:** Continuously expand the algorithm options by incorporating new and advanced pathfinding algorithms, providing users with a broader range of tools for problem-solving.
- **Heuristic Function Customization:** For algorithms that use heuristics (e.g., A*), allow users to customize the heuristic function to experiment with different approaches.
- **Obstacle Pattern Generation:** Implement a tool that generates predefined obstacle patterns (mazes, loops, etc.) to test the algorithms in various challenging scenarios.
- **Accessibility Improvements:** Ensure the application is accessible to users with disabilities by incorporating features like keyboard navigation and screen reader compatibility.
- **Algorithm Information:** Provide detailed information about each algorithm, including their characteristics, best-use scenarios, and any specific considerations.

## Installation
1. Clone the repository: `git clone https://github.com/yourusername/pathfinding-algorithm-visualizer.git`
2. Navigate into the directory: `cd pathfinding-algorithm-visualizer`
3. Install the dependencies: `npm install`
4. Start the application: `npm start`

## Usage
1. Select a pathfinding algorithm from the dropdown menu.
2. Click on the grid to set the start point (green) and end point (red).
3. Click and drag on the grid to create barriers.
4. Click 'Start' to begin the visualization.
