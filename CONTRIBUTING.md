# Contributing to Introductory Data Science

Thanks for your interest! Here's how to help.

## Ways to Contribute

- **Report bugs**: Something not running in Colab? Open an issue.
- **Suggest improvements**: Better explanations, additional algorithms, or new labs.
- **Fix issues**: Check the [Issues](https://github.com/DrKenReid/Introductory-Data-Science/issues) tab.
- **Improve docs**: Clarify explanations, fix typos, add examples.

## Setup

These labs run in Google Colab — no local setup required:

1. Open any notebook in Colab via the links in the README
2. Run all cells
3. Make your changes

For local development:

`ash
git clone https://github.com/DrKenReid/Introductory-Data-Science.git
pip install -r requirements.txt
jupyter notebook
`

## PR Guidelines

- Keep notebooks clean — restart kernel and run all before committing.
- Clear output cells to keep diffs readable.
- Add markdown cells explaining new sections.
- Don't commit API keys or credentials.
