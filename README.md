## Notes Pembelajaran Python dari Fork Digital Talent Scholarship

## Persiapan
#### 1. Saya menggunakan Anaconda
#### 2) Buat lingkugan kerja (environment) Anaconda
Di direktori repo utama

    conda env create -f binder/environment.yml
    conda activate py-dts
    pip install jupyter_contrib_nbextensions ``jika belum terinstall``
     - jupyter labextension install @jupyter-widgets/jupyterlab-manager
     - jupyter labextension install @bokeh/jupyter_bokeh
     - jupyter contrib nbextension install --user
     - jupyter nbextension enable hinterland/hinterland

Perhatikan bahwa opsi ini akan mengubah lingkungan Anda yang ada, berpotensi mengubah versi paket yang sudah Anda miliki telah diinstal.
