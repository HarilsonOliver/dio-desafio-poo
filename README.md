# DIO - Trilha .NET - Programação orientada a objetos
www.dio.me

## Contexto
Modelar um sistema que trabalha com celulares. Para isso, foi solicitado que você faça uma abstração de um celular e disponibilize maneiras de diferentes marcas e modelos terem seu próprio comportamento, possibilitando um maior reuso de código e usando a orientação a objetos.

## Proposta
Criar um sistema em .NET, do tipo console, mapeando uma classe abstrata e classes específicas para dois tipos de celulares: Nokia e iPhone. 
Criar as suas classes de acordo com o diagrama abaixo:

![Diagrama classes](sys-smartphones/Imagens/diagrama.png)

## Classes:
- **Smartphone (abstrata)**: Classe base que contém as propriedades e métodos comuns a todos os smartphones.
- **Nokia**: Classe que herda de `Smartphone` e implementa o comportamento específico para um celular Nokia.
- **Iphone**: Classe que herda de `Smartphone` e implementa o comportamento específico para um iPhone.

## Como Executar o Projeto

1. Clone o repositório:
   ```bash
   git clone (https://github.com/HarilsonOliver/dio-desafio-poo.git)
2. Navegue até o diretório do projeto:
   ```bash
   cd sys-smartphones
3. Execute o projeto:
   ```bash
   dotnet run
## Conceitos Utilizados

- **Abstração**: A classe `Smartphone` define um modelo abstrato para todos os smartphones.
- **Herança**: As classes `Nokia` e `Iphone` herdam de `Smartphone`.
- **Polimorfismo**: O método `InstalarAplicativo` é implementado de forma diferente para cada marca, permitindo comportamentos distintos.

## Licença

Este projeto é livre para uso educacional e demonstração de conceitos de orientação a objetos.
```
