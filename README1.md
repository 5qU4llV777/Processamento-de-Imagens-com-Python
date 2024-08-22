# Processamento-de-Imagens-com-Python

python -m pip install --upgrade pip >>> atualiza pip
<br>
python -m pip install twine >>>> instala o twine
<br>
python -m pip install setuptools >>> instala setuptools
<br>
python setup.py sdist bdist_wheel >>>> cria a distribuição
<br>
python -m twine upload --repository-url https://test.pypi.org/legacy/ dist/* >>>>sobe sua distribuição para test pypi
<br>
python -m twine upload --repository-url https://upload.pypi.org/legacy/ dist/* >>>>sobe sua distribuição para pypi
