## Notes Pembelajaran Python

## Persiapan
#### 1. Saya menggunakan Anaconda
#### 2a) Buat lingkugan kerja (environment) Anaconda
Di direktori repo utama

    conda env create -f binder/environment.yml
    conda activate note
    pip install jupyter_contrib_nbextensions

    jupyter labextension install @jupyter-widgets/jupyterlab-manager
    jupyter labextension install @bokeh/jupyter_bokeh
    jupyter contrib nbextension install --user
    jupyter nbextension enable hinterland/hinterland

#### 2b) Instal ke lingkungan yang ada
Anda akan membutuhkan perpustakaan inti berikut:

    conda install numpy pandas h5py pillow matplotlib scipy toolz pytables snakeviz scikit-image dask distributed -c conda-forge

Anda mungkin menemukan perpustakaan berikut berguna untuk beberapa latihan

    conda install python-graphviz -c conda-forge

Perhatikan bahwa opsi ini akan mengubah lingkungan Anda yang ada, berpotensi mengubah versi paket yang sudah Anda miliki telah diinstal.
