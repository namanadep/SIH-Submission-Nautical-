# Ship Route Optimization

## Overview
A Python application that optimizes sea routes between ports using Ant Colony Optimization (ACO) and Neural Networks. The project visualizes routes between Indian ports while considering weather conditions and various maritime factors.

## Features
- Ant Colony Optimization for route finding
- Neural Network for route prediction
- Interactive visualization using Plotly
- Weather condition consideration
- Real-time optimization progress tracking

## Dependencies
```python
streamlit
numpy
geopy
plotly
tensorflow
keras
scikit-learn
pandas
```

## Installation
1. Clone the repository
2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Project Structure
- [main.py](main.py) - Core implementation with ACO algorithm and visualization
- [Historical_data.csv](Historical_data.csv) - Training data for routes
- [parameters.txt](parameters.txt) - Configuration parameters
- [requirements.txt](requirements.txt) - Project dependencies

## Usage
Run the application using Streamlit:
```bash
streamlit run main.py
```

The UI provides:
- Adjustable ship parameters (fuel efficiency, speed)
- Real-time optimization progress
- Interactive map visualization
- Neural network training results

## Key Components
- [`AntColonyOptimization`](main.py) - Main optimization algorithm
- [`train_ANN`](main.py) - Neural network training
- [`plot_route`](main.py) - Route visualization

## Parameters
- Weather conditions: Clear, Cloudy, Rainy, Stormy
- Port coordinates for Mumbai, Cochin, and Rajula
- Configurable ACO parameters (ants, iterations, alpha, beta)

## License
MIT License
