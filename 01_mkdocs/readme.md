# Building a portfolio

we will use mkdocs for building the portfolio. Mkdocs is a static site generator that is geared towards project documentation. It is written in Python and uses the Jinja2 templating engine. Mkdocs is easy to use and has a lot of features that make it a great choice for building a portfolio.

Link the documentation is [here](https://www.mkdocs.org/getting-started/)

## 1. Install mkdocs
'''bash
conda create -n mkdocs python=3.12 -y
conda activate mkdocs
pip install mkdocs
'''
## 2. Create a new mkdocs project
'''bash
mkdocs new mera_portfolio
'''

## 3. Run the development server
'''bash
mkdocs serve
'''

this is how you can specify the port and host
'''bash
mkdocs serve --host 0.0.0.0 --port 8000
'''

## 4. Build the project
'''bash
mkdocs build
'''