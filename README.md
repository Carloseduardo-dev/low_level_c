# Cadastro de compras em C

Trabalho acadêmico da disciplina **Programação de Software Básico em C**, a partir do código disponibilizado pelo professor Alessandro Calin.

**Aluno:** Carlos Eduardo Silva Ferreira · **Matrícula:** 202408542283

## Objetivo

Aplicar conceitos de programação em C por meio de um sistema de cadastro de compras com interface gráfica no Windows, validação de dados e armazenamento em arquivo de texto.

O programa permite registrar produto, quantidade e preço unitário, calcular o valor de cada compra e consultar o total acumulado das compras cadastradas.

## Funcionalidades

- **Salvar compra:** valida os dados, calcula o total e grava o registro em `aval1234.txt`.
- **Mostrar compras:** lista os registros salvos e apresenta o total acumulado e a quantidade de compras.
- **Limpar:** esvazia os campos e a lista da janela, preservando os dados do arquivo.

## Como executar

No Windows, com Clang/LLVM-MinGW instalado, execute nesta pasta:

```powershell
clang -std=c11 -Wall -Wextra -Wno-unused-parameter index.c -o cadastro_compras.exe -mwindows -luser32 -lgdi32
.\cadastro_compras.exe
```

O arquivo `aval1234.txt` é criado na pasta de execução. O preço unitário aceita ponto ou vírgula decimal.

## Arquivos da entrega

- [Código-fonte completo](index.c).
- [Relatório com capturas de tela e respostas às questões](Cadastro_de_Compras_ARA0363.pdf).
- [Evidências da execução e dados de exemplo](evidencias/).
