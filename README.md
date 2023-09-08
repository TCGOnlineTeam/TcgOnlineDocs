# TCG Online Docs

In this repository are docs for the software used for TCG Online things. Everything that is pushed to main will be automatically built and hosted online [here](https://docs.tcg-online.creativebubble.de/).
To built the documentation on your system you first have to install [MkDocs Material](https://squidfunk.github.io/mkdocs-material/). This can be done with:

```bash
pip install mkdocs-material
```

Afterwards start the test server with

```bash
mkdocs serve
```

and type in the address: `http://127.0.0.1:8000` into your browser. You should see the documents then.

`MkDocs` will render a [Markdown](https://markdown-syntax.de/Was-ist-Markdown/) Document into HTML so one does not have to write HTML,CSS or JavaScript.

## How to Contribute

You found things that are missing or incorrect? Then feel free to create a pull request!

Please make sure that the page can still be built correctly with your changes. To test this build the website and check in your browser if the website looks correct.
