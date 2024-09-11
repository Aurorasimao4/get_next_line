# get_next_line

**get_next_line** é um projeto da Ecole 42 que visa implementar uma função em C para ler uma linha de um arquivo ou da entrada padrão. A função deve ser capaz de ler a próxima linha a partir do ponto em que a leitura anterior parou, o que é útil para processamento de arquivos linha por linha.

## Objetivo

O objetivo do projeto é criar a função `get_next_line`, que lê uma linha de um arquivo ou da entrada padrão, retornando-a como uma string. O projeto é uma oportunidade para aprender sobre manipulação de arquivos, buffers e gerenciamento de memória em C.

## Funcionalidade

- **Leitura de Arquivo**: A função deve ler uma linha de um arquivo especificado.
- **Leitura da Entrada Padrão**: A função deve ser capaz de ler a entrada padrão (`stdin`).
- **Buffer de Leitura**: A função deve usar um buffer interno para armazenar temporariamente os dados lidos.
- **Retorno de Linha**: A função deve retornar a próxima linha disponível ou NULL se não houver mais linhas.

## Requisitos

- **Sistema Operacional**: Linux
- **Compilador**: GCC

## Compilação

Para compilar o projeto, use o Makefile incluído no repositório. Execute os seguintes comandos:

```bash
git clone https://github.com/Aurorasimao4/get_next_line.git
cd get_next_line
