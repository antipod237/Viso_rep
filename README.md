# Viso_rep

Maskrcnn - папка с исходниками нееросети

Для запуска нейросети мы использовали Visual Studio Code и среду в Anaconda и репозитории https://github.com/matterport/Mask_RCNN.git и https://github.com/philferriere/cocoapi.git
Для использования библиотеки tensorflow требуется установить NVIDIA GPU Computing Toolkit версии 9.0, для работы с CUDA ядрами
Для проверки работы tensorflow используйте файл testtf.py в папке MASKRCNN
Для быстрой установки прочих библиотек используйте pip install -r .\requirements.txt (в папке MASKRCNN) (создайте отдельную среду в конде, в которую и импортируйте библиотеки)
Создаем питоновский терминал в Visual Studio Code
Через встроенную функцию Git Clone выолпнить команду git clone https://github.com/matterport/Mask_RCNN.git
Для дальнейшей установки pycocotools нужны Visual C++ 2015 Build Tools скачанные с сайта microsoft
Клонировать в Visual Studio Code репозиторий git clone https://github.com/philferriere/cocoapi.git
В Anaconda Promt выполнить команду pip install git+https://github.com/philferriere/cocoapi.git#subdirectory=PythonAPI
Разместить скачанный файл в Mask_RCNN директории
Запустить демку, располагающуюся в пути MASKRCNN/Mask_RCNN/samples/demo.ipynb

Библиотеки, установленные у нас
Package                       Version
----------------------------- ---------
absl-py                       0.15.0   
alabaster                     0.7.12   
argon2-cffi                   21.1.0   
astunparse                    1.6.3    
async-generator               1.10     
attrs                         21.2.0   
Babel                         2.9.1    
backcall                      0.2.0    
bleach                        1.5.0    
cached-property               1.5.2    
certifi                       2020.12.5
cffi                          1.15.0   
clang                         5.0      
colorama                      0.4.4    
cycler                        0.10.0   
Cython                        0.29.24  
dataclasses                   0.8      
decorator                     4.4.2    
defusedxml                    0.7.1    
docutils                      0.17.1   
entrypoints                   0.3      
flatbuffers                   1.12     
google-auth                   2.3.0    
google-auth-oauthlib          0.4.6    
h5py                          3.1.0    
html5lib                      0.9999999
imageio                       2.9.0    
imagesize                     1.2.0    
imgaug                        0.4.0    
importlib-metadata            4.8.1
ipykernel                     5.5.6
ipyparallel                   7.1.0
ipython                       7.16.1
ipython-genutils              0.2.0
ipywidgets                    7.6.5
jedi                          0.18.0
Jinja2                        3.0.2
jsonschema                    3.2.0
jupyter                       1.0.0
jupyter-client                7.0.6
jupyter-console               6.4.0
jupyter-core                  4.8.1
jupyterlab-pygments           0.1.2
jupyterlab-widgets            1.0.2
keras                         2.6.0
kiwisolver                    1.3.1
Markdown                      3.3.4
MarkupSafe                    2.0.1
matplotlib                    3.3.4
mistune                       0.8.4
nbclient                      0.5.4
nbconvert                     6.0.7
nbformat                      5.1.3
nest-asyncio                  1.5.1
networkx                      2.5.1
nose                          1.3.7
notebook                      6.4.5
numpy                         1.19.5
opencv-python                 4.5.3.56
packaging                     21.0
pandocfilters                 1.5.0
parso                         0.8.2
pickleshare                   0.7.5
Pillow                        8.4.0
pip                           21.0.1
prometheus-client             0.11.0
prompt-toolkit                3.0.20
protobuf                      3.18.1
psutil                        5.8.0
pycparser                     2.20
Pygments                      2.10.0
pyparsing                     2.4.7
pyrsistent                    0.18.0
python-dateutil               2.8.2
PyWavelets                    1.1.1
pywin32                       302
pywinpty                      1.1.4
pyzmq                         22.3.0
qtconsole                     5.1.1
QtPy                          1.11.2
requests                      2.5.0
scikit-image                  0.17.2
scipy                         1.5.4
Send2Trash                    1.8.0
setuptools                    58.0.4
Shapely                       1.7.1
six                           1.16.0
snowballstemmer               2.1.0
Sphinx                        4.2.0
sphinxcontrib-applehelp       1.0.2
sphinxcontrib-devhelp         1.0.2
sphinxcontrib-htmlhelp        2.0.0
sphinxcontrib-jsmath          1.0.1
sphinxcontrib-qthelp          1.0.3
sphinxcontrib-serializinghtml 1.1.5
tensorflow-gpu                1.5.0
tensorflow-tensorboard        1.5.1
terminado                     0.12.1
testpath                      0.5.0
tifffile                      2020.9.3
tornado                       6.1
tqdm                          4.62.3
traitlets                     4.3.3
typing-extensions             3.10.0.2
wcwidth                       0.2.5
Werkzeug                      2.0.2
wheel                         0.37.0
widgetsnbextension            3.5.1
wincertstore                  0.2
wrapt                         1.12.1
zipp                          3.6.0
