# Comparador de Hashes com RIPMD160

Este projeto foi desenvolvido como parte de uma aula da **Digital Innovation One (DIO)**. O objetivo é comparar dois arquivos de texto (`a.txt` e `b.txt`) usando o algoritmo de hash **RIPEMD-160**. O script verifica se os arquivos são iguais ou diferentes, gerando os hashes de ambos os arquivos e comparando-os.

## Como Funciona

O código utiliza o módulo `hashlib` do Python para gerar os hashes dos arquivos. O algoritmo utilizado é o **RIPEMD-160**, que é um algoritmo de hash criptográfico.

### Passos:

1. O arquivo `a.txt` é lido em modo binário e seu hash é gerado.
2. O arquivo `b.txt` é lido da mesma forma e seu hash é gerado.
3. Ambos os hashes são comparados. Se forem diferentes, a mensagem informando que os arquivos são diferentes será exibida.
4. Se os hashes forem iguais, a mensagem informando que os arquivos são iguais será exibida.

## Requisitos

- Python 3.x
- O módulo `hashlib` já está incluído na biblioteca padrão do Python.

## Como Usar

1. Crie dois arquivos de texto chamados `a.txt` e `b.txt` no mesmo diretório onde o script Python está localizado.
2. Execute o script Python.

python comparador_hashes.py


Agora, o `README.md` inclui a menção de que o projeto foi desenvolvido como parte de uma aula da DIO.

