.. title: llm-dataset-converter release
.. slug: 2023-10-27-ldc-release
.. date: 2023-10-27 09:47:00 UTC+13:00
.. tags: release
.. category: software
.. link: 
.. description: 
.. type: text


Over the last couple of months, we have been working on a little command-line tool that
allows you to convert LLM datasets from one format into another, appropriately called
`llm-dataset-converter`:

`https://github.com/waikato-llm/llm-dataset-converter <https://github.com/waikato-llm/llm-dataset-converter>`__

With the first release (0.0.1), you can not only load data from and save to in various formats
(csv/tsv, text, json, jsonlines, parquet). The tool lets you define pipelines using the following format:

`reader [filter [filter ...]] [writer]`

Each component in the pipeline comes with its own set of command-line parameters. You can even *tee* off
records and process them differently (e.g., writing the same data to different output formats).

The library also has other tools, for downloading files or datasets from huggingface or combining text files.

In order to make building such pipeline-oriented tools simpler to develop, we created a base library
that manages the handling of plugins (and, if necessary, their compatibility) called `seppl`
(*Simple Entry Point PipeLines*):

`https://github.com/waikato-datamining/seppl <https://github.com/waikato-datamining/seppl>`__

Thanks to seppl, the llm-dataset-converter library can be easily extended with additional modules, as it uses
a dynamic approach to locating plugins: you only need to define in what modules to look for what superclass
(like `Reader`, `Filter`, `Writer`).
