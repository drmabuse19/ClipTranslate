
# Clipboard Translator

This Python application continuously monitors your system's clipboard for new text entries. If the text copied to the clipboard is not a URL, the application translates the text to English using the Google Translate API and displays the translated text in a simple GUI. This tool is particularly useful for users who frequently work with foreign language texts.

## Prerequisites

Before you run this application, you need the following installed on your system:
- Python 3.x
- Tkinter (usually comes with Python)
- `pyperclip` and `googletrans` Python libraries

You can install the required Python libraries using pip:

```bash
pip install pyperclip googletrans==4.0.0-rc1
```

## Installation

Download the `Clipboard_Translator.py` file to your local machine.

## Usage

To start the application, run the Python script from your command line:

```bash
python Clipboard_Translator.py
```

The application will open a window displaying any translated text from your clipboard that is not a URL. It will update this text whenever new text is copied to the clipboard.

## Contributing

Contributions to this project are welcome! Please fork the repository and submit a pull request with your improvements.

## License

This project is open-sourced under the MIT License. See the LICENSE file for more details.
