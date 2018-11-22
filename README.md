# Variance risk on the FX market sing-along
Replication study engine for paper 'Variance risk on the FX market' by Igor Pozdeev

## Installation
First, download library [`paper_vrp_mini`](https://github.com/ipozdeev/paper_vrp_mini) containing necessary classes and functions. Make sure the library is where Python can find it. Then, download the database with previously estimated model-free implied variances from [my page (60MB)](https://igorpozdeev.me/files/vrp_paper_hangar_mini.h5) and save it to location of your choice. This is an HDF-based data storage, for which `paper_vrp_mini.database` provides an API.

Finally, download and run the notebooks in this repository like any IPython notebooks.

## Requirements
On my machine:

| python | conda  | pandas | numpy |
|:------:|:------:|:------:|:-----:|
|3.5.4   |4.5.11  |0.23.4  |1.13.3 |
