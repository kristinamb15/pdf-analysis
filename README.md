# Exploratory Data Analysis of PDF File

PDF File is downloaded, parsed, and analyzed.

See [Data Analysis Notebook](pdf_analysis.ipynb) for process, analysis, and visualizations.

To make sure interactive plots are visible, you can visit [this version of the notebook]().

**Language**: Python

## Setup

If you wish to run the notebook, install the environment:

    conda env create -f environment.yml

## Files

    📦PDFAnalysis
    ┣ 📂data                        # All data extracted from PDF file
    ┃ ┣ 📂processed
    ┃ ┃ ┣ 📜dataframe.csv
    ┃ ┃ ┣ 📜dt_matrix.csv
    ┃ ┃ ┣ 📜stats_dataframe.csv
    ┃ ┃ ┣ 📜tfidf_matrix.csv
    ┃ ┃ ┗ 📜topics.csv
    ┃ ┗ 📂raw
    ┃ ┃ ┣ 📜back_matter.txt
    ┃ ┃ ┣ 📜chapter_1.txt
    ┃ ┃ ┣ 📜chapter_2.txt
    ┃ ┃ ┣ 📜chapter_3.txt
    ┃ ┃ ┣ 📜chapter_4.txt
    ┃ ┃ ┣ 📜chapter_5.txt
    ┃ ┃ ┣ 📜chapter_6.txt
    ┃ ┃ ┣ 📜chapter_7.txt
    ┃ ┃ ┣ 📜chapter_8.txt
    ┃ ┃ ┣ 📜chapter_9.txt
    ┃ ┃ ┣ 📜eda_brantley.ipynb
    ┃ ┃ ┣ 📜front_matter.txt
    ┃ ┃ ┗ 📜output_Aviation Maintenance Technician Handbook - Airframe Volume 1.txt
    ┣ 📜.gitignore
    ┣ 📜environment.yml             # Environment file
    ┣ 📜int_plot.html               # Interactive plot
    ┣ 📜pdf_analysis.ipynb          # Data analysis notebook
    ┣ 📜plotly_graph.png            # PNG of interactive plot
    ┗ 📜README.md

## License

Files in this project are free for appropriate use under the [MIT License](LICENSE.txt).