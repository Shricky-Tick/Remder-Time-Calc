# Render Time Calculator

A desktop application built with Python and Tkinter that helps 3D artists estimate completion times for Blender rendering projects. Features a dark theme UI and precise time calculations.

![Render Time Calculator Screenshot](screenshots/calculator.jpg) 

## Features

- Calculate total render time based on frame count and per-frame render time
- Support for mathematical expressions in frame input (e.g., "260-200")
- Dark theme UI for reduced eye strain
- Precise completion time estimation
- Error handling for invalid inputs
- Cross-platform compatibility (Windows, Linux, MacOS)

## Installation

### Option 1: Running from Source

1. Clone this repository:
```bash
git clone https://github.com/yourusername/render-time-calculator.git
cd render-time-calculator
```

2. Install requirements:
```bash
pip install -r requirements.txt
```

3. Run the application:
```bash
python render_calculator.py
```

### Option 2: Windows Executable

Download the latest release from the [Releases](https://github.com/yourusername/render-time-calculator/releases) page.

## Usage

1. Enter the number of frames to render (can use mathematical expressions like "300-100")
2. Enter the render time per frame in seconds
3. Click "Calculate" or press Enter
4. View the estimated total render time and completion time

## Technical Details

- Built with Python 3.x and Tkinter/ttk
- Features a custom dark theme
- Handles timezone calculations for accurate completion time estimates
- Input validation and error handling for robustness

## Contributing

Feel free to open issues or submit pull requests if you have suggestions for improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
