# deMiner_animes

Repository ini berisi kumpulan tugas dalam implementasi berbagai teknik data mining. Beberapa algoritma dan metode yang dicakup antara lain:

- Klasifikasi Naive Bayes: Implementasi untuk pengelompokan data berdasarkan probabilitas.
- ...

Setiap metode dilengkapi dengan:

- Penjelasan teoretis singkat.
- Dataset uji coba.
- Penjelasan hasil analisis secara singkat.

## Dataset

Disini kami menggunakan dataset yang sama untuk setiap metode dan disimpan pada folder src, yaitu animes.csv

Usage path:
```bash
'..\src\animes.csv' # Windows
```
```bash
'../src/animes.csv' # Linux
```

> source url: [`animes.csv`](https://www.kaggle.com/datasets/arnavvvvv/anime-dataset/data?select=animes.csv)

> Context  
> This dataset contains information about Anime (16k), Reviews (130k) and Profiles (47k) crawled from [MyAnimeList](https://myanimelist.net/)
>   
> animes.csv contains list of anime, with title, title synonyms, genre, duration, rank, populatiry, score, airing date, episodes and many other important data about individual anime providing sufficient information about trends in time about important aspects of anime. Rank is in float format in csv, but it contains only integer value. This is due to NaN values and their representation in pandas.

## TechStack

- Python
- Jupyter Notebook

## Installation

```bash
pip install jupyterlab
pip install jupyter_server

# or

pipenv install jupyterlab
pipenv install jupyter_server

# or

conda install -c conda-forge jupyterlab

```
> Install the jupyter notebook or jupyter lab on virtual environment  
> (Read the documentation about installation)

## Contributor

| last3digits_studentID  | Avatar                                                                                                    | Username |
| --- | --------------------------------------------------------------------------------------------------------- | -------- |
| 155 | <img src="https://avatars.githubusercontent.com/9Out" width="100" height="100" alt="9Out Avatar">         | 9Out     | 
| 180 | <img src="https://avatars.githubusercontent.com/tars011" width="100" height="100" alt="TARS Avatar">      | TARS     | 
| 192 | <img src="https://avatars.githubusercontent.com/Justitia18" width="100" height="100" alt="Justitia18 Avatar">      | Justitia18     | 
| 194 | <img src="https://avatars.githubusercontent.com/AdonNeet" width="100" height="100" alt="AdonNeet Avatar"> | AdonNeet | 

## License

Proyek ini dilisensikan di bawah lisensi MIT. Lihat file [LICENSE.md](LICENSE.md) untuk informasi lebih lanjut.