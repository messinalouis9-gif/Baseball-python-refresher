# Python & Anaconda Code Refresher: Baseball Data Edition

A free starter guide and cheat sheet for players, coaches and fans who want to start working with baseball data in Python.

- **Part 1** explains the tools (Python, Anaconda, Jupyter, pandas, pybaseball) and walks through setup from scratch.
- **Part 2** is a cheat sheet of 84 short, numbered steps: get public Statcast data, look at it, clean it, filter it, build baseball columns (swings, whiffs, count, movement), summarize, check, chart and save.

Every example uses free, public data from [Baseball Savant](https://baseballsavant.mlb.com).

## What's here

| File | What it is |
|---|---|
| `Python-Anaconda-Code-Refresher-Baseball.pdf` | The guide, ready to read or print |
| `Python-Anaconda-Code-Refresher-Baseball.docx` | Editable Word version |
| `baseball_python_refresher.ipynb` | All 84 steps as a Jupyter notebook. Open it and run top to bottom |
| `movement_example.png` | Sample chart from step 72 |

## Quick start

1. Install [Anaconda Distribution](https://www.anaconda.com/download) (free for personal use).
2. Open Anaconda Prompt (Terminal on a Mac) and run:
   ```
   conda create -n baseball python=3.11 -y
   conda activate baseball
   pip install pandas numpy matplotlib openpyxl pyarrow pybaseball jupyter ipykernel
   jupyter notebook
   ```
3. Open `baseball_python_refresher.ipynb` and choose Kernel > Restart & Run All.

No install? Upload the notebook to [Google Colab](https://colab.research.google.com) and run `!pip install pybaseball` in the first cell.

## What I wrote and what AI helped with

I put this together while working on my own skills. AI tools helped draft the explanations and code, and every example was run in order on public Statcast data (May 11-17, 2024) before it went in. I'm still learning, which is the point: this is the guide I wanted when I started.

## Help improve it

This is open source, and I'd love help making it better. Fix a mistake, suggest a clearer way to write a step, or add a section (SQL, R, hitting data, defense, Excel). See [CONTRIBUTING.md](CONTRIBUTING.md).

## Data and credits

- Statcast data from Baseball Savant, pulled with [pybaseball](https://github.com/jldbc/pybaseball). Column definitions: [Savant CSV docs](https://baseballsavant.mlb.com/csv-docs). This repo does not include any data files; the notebook downloads them.
- This is a personal project. It has no connection to any club and uses no club data.

## License

Text and guide: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Code in the notebook: MIT. See [LICENSE](LICENSE).

Louis G. Messina
