# Passo a passo para criar, compilar e executar um script python

## Passo a passo

1. Abrir o terminal
![Abrindo o Terminal](1.png)

3. Criar um arquivo com extensão .py (Ex no CMD: type nul > nome_do_arquivo.py)
![Criando o Arquivo](2.png)

5. Abrir o arquivo criado em um editor de texto/código (Neste exemplo foi usado o Visual Studio Code)
![Abrindo o arquivo num editor](3.png)

7. Escrever o script e salvar (CTRL + S no Visual Studio Code)
![Escrevendo o script](4.png)

9. Pelo terminal, navegar até o diretório que está o arquivo que foi criado

10. Executar o comando python -m compileall nome_do_arquivo.py
![Compilando](5.png)

12. Será gerado uma pasta __pycache__ no diretório 

13. Navegar até a pasta __pycache__ (como já está no diretório atual, executar o comando: cd __pycache__)
![Navegando ate a pasta __pycache__](6.png)

15. Visualizar o arquivo com extensão .pyc no diretório __pycache__ (comando dir no CMD, pode ser ls em outros terminais)

16. Digitar o nome do arquivo que está listado no diretório __pycache__, no caso desta explicação é: ex_one.cpython-313.pyc e então, o arquivo será executado e mostrará o resultado do script
![Executando](7.png)

18. Para visualizar o bytecode gerado ao compilar, basta abrir o arquivo com extensão .pyc em algum editor de texto ou código (Ex:Bloco de notas)
![Abrindo no VSCODE](8.png)
![Visualizando o ByteCode](9.png)
