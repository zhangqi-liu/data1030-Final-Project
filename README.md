# data1030-Final-Project

Briefly described, the dataset utilized considers work-related measures concerning
staff who leave the service, and our target of this project is to understand the overall
situation of employee attrition and distinguish the reasons behind it. Furthermore,
prediction of whether an employee will leave could then be made based on his
information.

Starting with Exploratory Data Analysis, variables with zero variance, null and
duplicate values were checked to do a preliminary data processing. At the same
time, Univariate and bivariate analysis were conducted to help us gain primary insight
of the data. We then detected high correlations to tackle the multicollinearity
problem.

Finally, our optimal model was determined based F1 score as the
metrics,  Gradien Bossting has highest F1-score (58%). We then
identified some more significant factors like monthly income, age, and overtime that
affect people’s decision on attrition, and according to these results, a clearer picture
of the reasons behind attrition was gained, and further discussion like strategic plans
for companies were made.


Python 3.9.12

Package Verison:
_py-xgboost-mutex         2.0                       cpu_0    conda-forge
anyio                     3.6.1              pyhd8ed1ab_1    conda-forge
appnope                   0.1.3              pyhd8ed1ab_0    conda-forge
argon2-cffi               21.3.0             pyhd8ed1ab_0    conda-forge
argon2-cffi-bindings      21.2.0          py310h1961e1f_2    conda-forge
asttokens                 2.0.8              pyhd8ed1ab_0    conda-forge
attrs                     22.1.0             pyh71513ae_1    conda-forge
babel                     2.10.3             pyhd8ed1ab_0    conda-forge
backcall                  0.2.0              pyh9f0ad1d_0    conda-forge
backports                 1.0                        py_2    conda-forge
backports.functools_lru_cache 1.6.4              pyhd8ed1ab_0    conda-forge
bayesian-optimization     1.3.1                    pypi_0    pypi
beautifulsoup4            4.11.1             pyha770c72_0    conda-forge
bleach                    5.0.1              pyhd8ed1ab_0    conda-forge
brotli                    1.0.9                h5eb16cf_7    conda-forge
brotli-bin                1.0.9                h5eb16cf_7    conda-forge
brotlipy                  0.7.0           py310h1961e1f_1004    conda-forge
bzip2                     1.0.8                h0d85af4_4    conda-forge
ca-certificates           2022.6.15.1          h033912b_0    conda-forge
certifi                   2022.6.15.1        pyhd8ed1ab_0    conda-forge
cffi                      1.15.1          py310h96bbf6e_0    conda-forge
charset-normalizer        2.1.1              pyhd8ed1ab_0    conda-forge
cloudpickle               2.2.0              pyhd8ed1ab_0    conda-forge
colorama                  0.4.5              pyhd8ed1ab_0    conda-forge
cryptography              37.0.4          py310h52c3658_0    conda-forge
cycler                    0.11.0             pyhd8ed1ab_0    conda-forge
debugpy                   1.6.3           py310h154be8b_0    conda-forge
decorator                 5.1.1              pyhd8ed1ab_0    conda-forge
defusedxml                0.7.1              pyhd8ed1ab_0    conda-forge
dnspython                 2.2.1                    pypi_0    pypi
entrypoints               0.4                pyhd8ed1ab_0    conda-forge
et-xmlfile                1.1.0                    pypi_0    pypi
executing                 1.0.0              pyhd8ed1ab_0    conda-forge
flit-core                 3.7.1              pyhd8ed1ab_0    conda-forge
fonttools                 4.37.0          py310h90acd4f_0    conda-forge
freetype                  2.12.1               h3f81eb7_0    conda-forge
icu                       70.1                 h96cf925_0    conda-forge
idna                      3.3                pyhd8ed1ab_0    conda-forge
imageio                   2.22.4                   pypi_0    pypi
importlib-metadata        4.11.4          py310h2ec42d9_0    conda-forge
importlib_metadata        4.11.4               hd8ed1ab_0    conda-forge
importlib_resources       5.9.0              pyhd8ed1ab_0    conda-forge
ipykernel                 6.15.2             pyh736e0ef_0    conda-forge
ipython                   8.5.0              pyhd1c38e8_1    conda-forge
ipython_genutils          0.2.0                      py_1    conda-forge
ipywidgets                7.7.0              pyhd8ed1ab_0    conda-forge
jedi                      0.18.1             pyhd8ed1ab_2    conda-forge
jinja2                    3.1.2              pyhd8ed1ab_1    conda-forge
joblib                    1.1.0              pyhd8ed1ab_0    conda-forge
jpeg                      9e                   hac89ed1_2    conda-forge
json5                     0.9.5              pyh9f0ad1d_0    conda-forge
jsonschema                4.16.0             pyhd8ed1ab_0    conda-forge
jupyter_client            7.3.1              pyhd8ed1ab_0    conda-forge
jupyter_core              4.10.0          py310h2ec42d9_0    conda-forge
jupyter_server            1.17.0             pyhd8ed1ab_0    conda-forge
jupyterlab                3.4.2              pyhd8ed1ab_0    conda-forge
jupyterlab_pygments       0.2.2              pyhd8ed1ab_0    conda-forge
jupyterlab_server         2.15.1             pyhd8ed1ab_0    conda-forge
jupyterlab_widgets        1.1.1              pyhd8ed1ab_0    conda-forge
jupytext                  1.13.8             pyh4b9bcc7_0    conda-forge
kiwisolver                1.4.4           py310habb735a_0    conda-forge
lcms2                     2.12                 h577c468_0    conda-forge
lerc                      4.0.0                hb486fe8_0    conda-forge
libblas                   3.9.0           16_osx64_openblas    conda-forge
libbrotlicommon           1.0.9                h5eb16cf_7    conda-forge
libbrotlidec              1.0.9                h5eb16cf_7    conda-forge
libbrotlienc              1.0.9                h5eb16cf_7    conda-forge
libcblas                  3.9.0           16_osx64_openblas    conda-forge
libcxx                    14.0.6               hccf4f1f_0    conda-forge
libdeflate                1.14                 hb7f2c08_0    conda-forge
libffi                    3.4.2                h0d85af4_5    conda-forge
libgfortran               5.0.0           10_4_0_h97931a8_25    conda-forge
libgfortran5              11.3.0              h082f757_25    conda-forge
libiconv                  1.16                 haf1e3a3_0    conda-forge
liblapack                 3.9.0           16_osx64_openblas    conda-forge
libllvm11                 11.1.0               hd011deb_3    conda-forge
libopenblas               0.3.21          openmp_h429af6e_3    conda-forge
libpng                    1.6.37               h5481273_4    conda-forge
libsodium                 1.0.18               hbcb3906_1    conda-forge
libsqlite                 3.39.3               ha978bb4_0    conda-forge
libtiff                   4.4.0                hdb44e8a_4    conda-forge
libwebp-base              1.2.4                h775f41a_0    conda-forge
libxcb                    1.13              h0d85af4_1004    conda-forge
libxgboost                1.5.1            cpu_h598c753_2    conda-forge
libxml2                   2.9.14               hea49891_4    conda-forge
libxslt                   1.1.35               heaa0ce8_0    conda-forge
libzlib                   1.2.12               hfe4f2af_2    conda-forge
llvm-openmp               14.0.4               ha654fa7_0    conda-forge
llvmlite                  0.38.1          py310h8fbb61a_0    conda-forge
lxml                      4.9.1           py310h6c45266_0    conda-forge
markdown-it-py            2.1.0              pyhd8ed1ab_0    conda-forge
markupsafe                2.1.1           py310h1961e1f_1    conda-forge
matplotlib                3.5.2           py310h2ec42d9_1    conda-forge
matplotlib-base           3.5.2           py310h4510841_1    conda-forge
matplotlib-inline         0.1.6              pyhd8ed1ab_0    conda-forge
mdit-py-plugins           0.3.0              pyhd8ed1ab_0    conda-forge
mdurl                     0.1.0              pyhd8ed1ab_0    conda-forge
mglearn                   0.1.9                    pypi_0    pypi
mistune                   2.0.4              pyhd8ed1ab_0    conda-forge
munkres                   1.1.4              pyh9f0ad1d_0    conda-forge
mysql-connector-python-rf 2.2.2                    pypi_0    pypi
nbclassic                 0.4.3              pyhd8ed1ab_0    conda-forge
nbclient                  0.6.8              pyhd8ed1ab_0    conda-forge
nbconvert                 7.0.0              pyhd8ed1ab_0    conda-forge
nbconvert-core            7.0.0              pyhd8ed1ab_0    conda-forge
nbconvert-pandoc          7.0.0              pyhd8ed1ab_0    conda-forge
nbformat                  5.4.0              pyhd8ed1ab_0    conda-forge
ncurses                   6.3                  h96cf925_1    conda-forge
nest-asyncio              1.5.5              pyhd8ed1ab_0    conda-forge
notebook                  6.4.12             pyha770c72_0    conda-forge
notebook-shim             0.1.0              pyhd8ed1ab_0    conda-forge
numba                     0.55.2          py310hab1bff6_0    conda-forge
numpy                     1.22.4          py310hed37afb_0    conda-forge
openjpeg                  2.5.0                h5d0d7b0_1    conda-forge
openpyxl                  3.0.10                   pypi_0    pypi
openssl                   1.1.1q               hfe4f2af_0    conda-forge
packaging                 21.3               pyhd8ed1ab_0    conda-forge
pandas                    1.4.2           py310h3099161_2    conda-forge
pandoc                    2.19.2               h694c41f_0    conda-forge
pandocfilters             1.5.0              pyhd8ed1ab_0    conda-forge
parso                     0.8.3              pyhd8ed1ab_0    conda-forge
pexpect                   4.8.0              pyh9f0ad1d_2    conda-forge
pickleshare               0.7.5                   py_1003    conda-forge
pillow                    9.2.0           py310h54af1cc_2    conda-forge
pip                       22.2.2             pyhd8ed1ab_0    conda-forge
pkgutil-resolve-name      1.3.10             pyhd8ed1ab_0    conda-forge
plotly                    5.8.0              pyhd8ed1ab_1    conda-forge
prometheus_client         0.14.1             pyhd8ed1ab_0    conda-forge
prompt-toolkit            3.0.31             pyha770c72_0    conda-forge
psutil                    5.9.2           py310h90acd4f_0    conda-forge
pthread-stubs             0.4               hc929b4f_1001    conda-forge
ptyprocess                0.7.0              pyhd3deb0d_0    conda-forge
pure_eval                 0.2.2              pyhd8ed1ab_0    conda-forge
py-xgboost                1.5.1           cpu_py310h22f808f_2    conda-forge
py4j                      0.10.9.5                 pypi_0    pypi
pycparser                 2.21               pyhd8ed1ab_0    conda-forge
pygments                  2.13.0             pyhd8ed1ab_0    conda-forge
pymongo                   4.3.3                    pypi_0    pypi
pyopenssl                 22.0.0             pyhd8ed1ab_0    conda-forge
pyparsing                 3.0.9              pyhd8ed1ab_0    conda-forge
pyrsistent                0.18.1          py310h1961e1f_1    conda-forge
pysocks                   1.7.1              pyha2e5f31_6    conda-forge
pyspark                   3.3.1                    pypi_0    pypi
python                    3.10.5          hdaaf3db_0_cpython    conda-forge
python-dateutil           2.8.2              pyhd8ed1ab_0    conda-forge
python-fastjsonschema     2.16.1             pyhd8ed1ab_0    conda-forge
python_abi                3.10                    2_cp310    conda-forge
pytz                      2022.2.1           pyhd8ed1ab_0    conda-forge
pyyaml                    6.0             py310h1961e1f_4    conda-forge
pyzmq                     23.2.1          py310hcabbbd4_0    conda-forge
readline                  8.1.2                h3899abd_0    conda-forge
requests                  2.28.1             pyhd8ed1ab_1    conda-forge
rise                      5.7.1           py310h2ec42d9_1    conda-forge
scikit-learn              1.1.1           py310hfc06b38_0    conda-forge
scipy                     1.9.1           py310h240c617_0    conda-forge
seaborn                   0.12.0                   pypi_0    pypi
send2trash                1.8.0              pyhd8ed1ab_0    conda-forge
setuptools                65.3.0             pyhd8ed1ab_1    conda-forge
shap                      0.41.0                   pypi_0    pypi
six                       1.16.0             pyh6c4a22f_0    conda-forge
slicer                    0.0.7              pyhd8ed1ab_0    conda-forge
sniffio                   1.3.0              pyhd8ed1ab_0    conda-forge
soupsieve                 2.3.2.post1        pyhd8ed1ab_0    conda-forge
sqlite                    3.39.3               h9ae0607_0    conda-forge
stack_data                0.5.0              pyhd8ed1ab_0    conda-forge
tabulate                  0.9.0                    pypi_0    pypi
tenacity                  8.0.1              pyhd8ed1ab_0    conda-forge
terminado                 0.15.0          py310h2ec42d9_0    conda-forge
threadpoolctl             3.1.0              pyh8a188c0_0    conda-forge
tinycss2                  1.1.1              pyhd8ed1ab_0    conda-forge
tk                        8.6.12               h5dbffcc_0    conda-forge
toml                      0.10.2             pyhd8ed1ab_0    conda-forge
tornado                   6.2             py310h6c45266_0    conda-forge
tqdm                      4.64.1             pyhd8ed1ab_0    conda-forge
traitlets                 5.3.0              pyhd8ed1ab_0    conda-forge
typing_extensions         4.3.0              pyha770c72_0    conda-forge
tzdata                    2022c                h191b570_0    conda-forge
unicodedata2              14.0.0          py310h1961e1f_1    conda-forge
urllib3                   1.26.11            pyhd8ed1ab_0    conda-forge
wcwidth                   0.2.5              pyh9f0ad1d_2    conda-forge
webencodings              0.5.1                      py_1    conda-forge
websocket-client          1.4.1              pyhd8ed1ab_0    conda-forge
wheel                     0.37.1             pyhd8ed1ab_0    conda-forge
widgetsnbextension        3.6.1              pyha770c72_0    conda-forge
xgboost                   1.5.1           cpu_py310hce1aae2_2    conda-forge
xlrd                      2.0.1                    pypi_0    pypi
xorg-libxau               1.0.9                h35c211d_0    conda-forge
xorg-libxdmcp             1.1.3                h35c211d_0    conda-forge
xz                        5.2.6                h775f41a_0    conda-forge
yaml                      0.2.5                h0d85af4_2    conda-forge
zeromq                    4.3.4                he49afe7_1    conda-forge
zipp                      3.8.1              pyhd8ed1ab_0    conda-forge
zlib                      1.2.12               hfe4f2af_2    conda-forge
zstd                      1.5.2                hfa58983_4    conda-forge

