# ReportWright live demo

The static build behind **https://mrarun005.github.io/reportwright-demo/**: the report gallery, the drag-and-drop designer playground, the embed samples and the import switcher (drop a `.jrxml`, `.rdl` or `.rptdesign` and see what carries over).

Everything here is generated from the main project; file issues and read the docs there: **[MrArun005/reportwright](https://github.com/MrArun005/reportwright)**.

| Page | What it shows |
|---|---|
| [`index.html`](https://mrarun005.github.io/reportwright-demo/) | Gallery of rendered reports in the embeddable viewer |
| [`play.html`](https://mrarun005.github.io/reportwright-demo/play.html) | Designer playground with your own pasted JSON or CSV |
| [`learn.html`](https://mrarun005.github.io/reportwright-demo/learn.html) | Building a report step by step in the designer |
| [`switch.html`](https://mrarun005.github.io/reportwright-demo/switch.html) | Importers for JasperReports, SSRS and BIRT, running in the browser |
| [`bench.html`](https://mrarun005.github.io/reportwright-demo/bench.html) | Benchmarks against other engines |

The viewer and designer run the engine in a Web Worker; fonts and the HarfBuzz subsetter are served as static files from this repo.
