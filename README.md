# Benchmark-Agent data set

How does the level of human guidance affect the quality of LLM-generated performance benchmarks compared to an established reference benchmark for a known open-source system?

Data of the bachelor thesis by Willi Leonard Horn (Technische Universität Berlin, Scalable Software Systems group, 2026), licensed under CC BY 4.0 (see `LICENSE.md`). The code that produced the data is in the repository `benchmark-agent`.

## Structure

The data is in `benchmark-agent-dataset.zip`, which contains `results/` with:

- `artifacts/`: one folder per run, with the generated benchmark, prompt, model replies, validation and measurements
- `raw/`: raw output of each matrix invocation
- `reports/`: figures and tables used in the thesis
