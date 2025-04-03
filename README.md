# Data Center Predictor Module for Ignition

A predictive maintenance module for data centers that uses historical and current data to predict potential errors and equipment failures.

## Features

- Advanced machine learning algorithms for equipment failure prediction
- Anomaly detection for early problem identification
- REST API for external integration
- Custom Perspective components for visualization
- Comprehensive reporting with export capabilities
- Cloud model training with local inference

## Installation

1. Download the latest `.modl` file from the [Releases](https://github.com/CalumMcCallion/ignition-datacenter-predictor/releases) page
2. Open your Ignition Gateway web interface
3. Go to Config > Modules
4. Click "Install or Upgrade a Module..."
5. Select the downloaded `.modl` file
6. Restart the Gateway if prompted

## Development Setup

### Prerequisites

- JDK 11
- Ignition SDK 8.1.x
- Gradle 7.0+

### Building from Source

1. Clone the repository:
