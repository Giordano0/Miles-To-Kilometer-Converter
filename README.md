# 🛣️ Miles to Kilometer Converter

A lightweight desktop app built with Python and Tkinter that instantly converts miles to kilometers.

## Screenshot

> _A simple GUI window where you type in miles, hit Calculate, and get the result in km._

## Features

- Clean, minimal GUI built with Tkinter (no external dependencies)
- Instant conversion on button click
- Lightweight — just one file, runs anywhere Python does

## Built With

- **Python** — the programming language the app is written in
- **Tkinter** — a GUI library bundled with Python for building desktop interfaces. Used specifically for:
  - `Tk()` — the main application window
  - `Entry` — the input field for typing miles
  - `Label` — the text elements ("Miles", "is equal to", "Km", and the result)
  - `Button` — the Calculate button that triggers the conversion
  - `grid()` — the layout system that positions elements in rows and columns

No third-party libraries or frameworks — just Python's standard library.

## Requirements

- Python 3.x
- Tkinter (included with most standard Python installations)

## Installation & Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/miles-to-km-converter.git
   cd miles-to-km-converter
   ```

2. **Run the app**
   ```bash
   python main.py
   ```

3. **Use it**
   - Type a distance in miles into the input field
   - Click **Calculate**
   - The result in kilometers appears instantly

## How It Works

The conversion uses the standard formula:

```
kilometers = miles × 1.60934
```

## Project Structure

```
miles-to-km-converter/
└── main.py       # Main application file
```

## License

This project is open source and available under the [MIT License](LICENSE).
