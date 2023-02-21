# systemc.org

Website sources rendered using [MkDocs][1]

See the published website at [https://systemc.org][2]

Copyright &copy; 2023 [Accellera Systems Initiative][3]

# Contributing via pull requests

Please check the [CONTRIBUTING][5] guidelines how to contribute to [https://systemc.org][2]. It is recommended to install MkDocs to validate your contributions first.

```
pip install mkdocs
```

A detailed MkDocs installation procedure can be found [here][4].

Before creating a pull request, it is recommended to preview your edits in a locally rendered website, by running the `mkdocs serve` command:

```
$ mkdocs serve
INFO    -  Building documentation...
INFO    -  Cleaning site directory
[I 160402 15:50:43 server:271] Serving on http://127.0.0.1:8000
[I 160402 15:50:43 handlers:58] Start watching changes
[I 160402 15:50:43 handlers:60] Start detecting changes
```

Open up `http://127.0.0.1:8000/` in your browser, and you'll see the website displayed. If your rendered content looks good, you can proceed with the submission of your pull request.


[1]: https://www.mkdocs.org/
[2]: https://systemc.org
[3]: https://accellera.org
[4]: https://www.mkdocs.org/getting-started/#installation
[5]: CONTRIBUTING.md
