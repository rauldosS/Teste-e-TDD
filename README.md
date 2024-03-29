# Teste e TDD

Testes e introdução ao TDD no Python

## Asserções (Assertions)

Geralmente usado de desenvolvedores para desenvolvedores.

## Doctest — Test interactive Python examples

[Documentação](https://docs.python.org/3/library/doctest.html)

- [Teste calculadora](https://github.com/rauldosS/Teste-e-TDD/blob/main/src/calculadora.py)

## Unittest — Unit testing framework

[Documentação](https://docs.python.org/3/library/unittest.html)

- [Teste calculadora](https://github.com/rauldosS/Teste-e-TDD/blob/main/tests/test_calculadora.py)

## TDD - Test-driven development

### Ciclo de desenvolvimento

1. Adicione um teste
2. Execute todos os testes e veja se algum deles falha
3. Escrever código
4. Execute os testes automatizados e veja-os executarem com sucesso
5. Refatorar código
6. Repita tudo

- Red
    - Parte 1 -> Criar o teste e ver falhar

- Green
    - Parte 2 -> Criar o código e ver o teste passar

- Refactor
    - Parte 3 -> Melhorar meu código

- [Teste Bacon com ovos](https://github.com/rauldosS/Teste-e-TDD/blob/main/tests/test_baconcomovos.py)
    - [Classe Bacon com ovos](https://github.com/rauldosS/Teste-e-TDD/blob/main/src/baconcomovos.py)

- [Teste Pessoa](https://github.com/rauldosS/Teste-e-TDD/blob/main/tests/test_pessoa.py)
    - [Classe Pessoa](https://github.com/rauldosS/Teste-e-TDD/blob/main/src/Pessoa.py)

## Executando e organizando testes

```shell
python -m unittest -v
```
- Todos os testes estão no diretório `tests`
- Todos os arquivos de testes começam com `test_` ou terminam com `_test`
## MyPy

```shell
pip install mypy
```

```shell
mypy <arquivo>
```

## Type hints

- [Meu teste](https://github.com/rauldosS/Teste-e-TDD/blob/main/typehints.py)