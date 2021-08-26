![Veye](https://site.veye.com.br/assets/front/img/logo.svg)

# Objetivo:
Fazer uma aplicação de Locadora de carros onde haverá o cadastro de clientes, dos carros disponíveis e seus dados básicos como descricao, marca, modelo, ano, placa e kilometragem, bem como a locação em si.

## Entidades:
Carro   (chave primaria, descricao, marca, modelo, ano, placa, kilometragem)
Cliente (chave primaria, nome, cfp)
Locacao (chave primaria, carro, cliente, data/hora registro, data/hora inicio, data/hora fim, observacao varchar)

## Regras funcionais:
Uma locacao deve impedir de locar o mesmo carro no mesmo intervalo de tempo.
A locacao deve permitir selecionar o carro pelas suas caracteristicas e disponibilidade.

## O que se espera:
A aplicação deve seguir os conceitos de separação de responsabilidades (regras de negócio).

## O que seria ótimo:
Testes unitários automatizados.
Usar NODEJS como linguagem.
Usar MYSQL como base de dados.

# Observações:
Enviar o retorno do teste em forma de pacote compacatado, ou link para o projeto em github pessoal com as instruções de como colocar no ar sua aplicação; Fará parte da avaliação a efetiva execução do mesmo.
