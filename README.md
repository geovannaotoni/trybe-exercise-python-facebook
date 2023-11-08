# Batalha Naval com Python 🚢
Nesse exercício foi implementada uma função em Python para resolver um teste técnico que já foi aplicado no processo seletivo do Facebook. Ele consistiu em escrever uma função chamada `count_words` que, a partir de uma lista de palavras e uma string, decide quais palavras podem ser formadas com os caracteres da string (cada caractere só pode ser utilizado uma vez) e retorna a soma do comprimento das palavras escolhidas.

> Exemplo 1:

```py
words = ["hello", "world", "students"], chars = "welldonehoneyr"
# saída: 10
"""As palavras que podem ser formadas com os caracteres da string são "hello" (tamanho 5) e "world" (tamanho 5)."""
```

## :hammer: Tecnologias Utilizadas
- Python
- Pytest
- Ambiente Virtual venv
- Trabalhar com Hashmap e Dict
- Análise assintótica de algoritmos
- Lógica de Programação

## :computer: Visualize este projeto:
Para executar o projeto, você deve ter o Python instalado em sua máquina. Em seguida, siga os passos abaixo:
- Clone o repositório em sua máquina;
- Crie o ambiente virtual para o exercício: `python3 -m venv .venv && source .venv/bin/activate`
- Instale as dependências: `python3 -m pip install -r dev-requirements.txt`.

## :mag: Executando os testes:
Utilize o comando no terminal:
```bash
  $ python3 -m pytest
```