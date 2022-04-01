# Como usar

- O projeto tem duas pastas. Uma contendo os projetos do Jupyter Notebook e outra com os scripts python caso o desenvolvedor opte por executar sem o Jupyter.

- É importante que os dois (projeto notebook e scripts) estejam com os códigos iguais atualizados.

- Por conta disto, prefere-se que utilize o jupyter notebook pois caso haja alguma atualização é só exportar o script python na própria plataforma.

**Instalações prévias**

- python3 (e o pip)
```
sudo apt install python3-pip
```

- jupyter notebook (caso queira utilizar)
```
sudo snap install jupyter
```

**Usando o Jupyter Notebook**
- entre na pasta jupyter e execute
```
jupyter notebook
```

- escolha o projeto que quer usar

- para rodar o script, no menu, vá em Cell e depois Run All

- caso dê erro de falta de module, execute no terminal

```
pip install nomedomodule
```

