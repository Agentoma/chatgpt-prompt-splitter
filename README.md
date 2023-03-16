<p align="center">
  <img src="static/chatgpt_prompt_splitter.png" width="150" alt="Long PROMPTs Splitter for ChatGPT" />
  <h1 align="center">ChatGPT PROMPTs Splitter</h1>
</p>

## Overview

**ChatGPT PROMPTs Splitter** is an open-source tool designed to help you split long text prompts into smaller chunks, making them suitable for usage with ChatGPT (or other language models with character limitations).

The tool ensures that the text is divided into safe chunks of up to 15,000 characters per request as default, although can be changed.

The project includes an easy-to-use web interface for inputting the long text, selecting the maximum length of each chunk, and copying the chunks individually to paste them to ChatGPT.

## Features

- Web interface for splitting text into smaller chunks
- Customizable maximum length for each chunk
- Copy chunks individually to send to ChatGPT
- Instructions for ChatGPT on how to process the chunks

## Getting Started

### Prerequisites

- Python 3.x
- Flask

### Installation

1. Clone the repository:

```bash
git clone https://github.com/username/long-prompts-splitter.git
```
2. Change to the project directory:

```bash
cd long-prompts-splitter
```
3. Install the required dependencies:

```bash
pip install -r requirements.txt
```
### Usage

1. Run the Flask application:

```bash
python app.py
```

2. Open your web browser and navigate to http://localhost:5000.

3. Input the long text prompt, select the maximum length for each chunk, and click the "Split" button.

4. Copy the chunks and paste them into ChatGPT.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please read the [CONTRIBUTING](CONTRIBUTING.md) file for details on how to contribute to the project.


## Contact

If you have any questions or suggestions, please contact me at [
hello@jjdiaz.dev](mailto:hello@jjdiaz.dev).

## Disclaimer

This project is not affiliated with OpenAI, Microsoft, or any other entity. The project is provided "as is" without warranty of any kind, express or implied. The author is not responsible for any damages or losses arising from the use of this project.

## Changelog

### 1.0.0

- Initial release