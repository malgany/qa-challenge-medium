# qa-challenge-medium
QA Challenge Medium

# Wealth Systems Quality Assurance Challenge
Esse desafio tem por objetivo avaliar sua capacidade de analisar cenários de testes e de automatizá-los.
Por se tratar de um desafio para todos os níveis, não se sinta preso em submeter a solução completa, envie o que conseguir fazer junto com suas considerações.
Os desafios devem ser agrupados em um único projeto.

# Desafio

O desafio consiste em:

1. Especificar cenários de testes, baseado em um protótipo;
2. <strike>Automatizar o teste front-end de 2 funcionalidades;</strike>
3. Automatizar o teste back-end de uma API;


## 1 - Cenários de Testes

Crie cenários de testes baseados no protótipo abaixo. Você está livre para usar o formato que quiser.

![Resumo do Cliente](https://github.com/WealthSystems/qa-challenge/blob/master/images/client-summary.png)

## 2 - <strike>Automação de 2 funcionalidades front-end</strike>

<strike>No site abaixo existem duas funcionalidades á serem testadas.</strike>

<strike>Na primeira, é possível renderizar um elemento escondido.
Crie uma automação que clique no botão “Start”, aguarde pelo carregamento do elemento e faça uma validação que o texto “Hello World!” foi apresentado.
https://the-internet.herokuapp.com/dynamic_loading/1</strike>

<strike>Na segunda, os seletores dos elementos que você utilizar serão avaliados. Seu desafio é encontrar bons seletores para os elementos.
Crie uma automação que clique nos três botões apresentados em tela e em todos “edit” e “delete” da grid.
https://the-internet.herokuapp.com/challenging_dom</strike>

## 3 - Automação de 1 funcionalidade back-end

Crie uma collection de testes que valide o GET, POST, PUT  e DELETE da API disponibilizada no end-point abaixo.
http://jsonplaceholder.typicode.com/users
Valide o JSON schema e http code das respostas.

# Recomendações

Os itens abaixo não são obrigatórios.

- Use Gherkin para descrição dos cenários de testes;
  - Video 1: O que é BDD: https://youtu.be/DoEzwnqB1mk
  - Video 2: O que é Gherkin: https://youtu.be/XYhaFnjvi3U?t=224
  - Video 3: BDD e a sintaxe Gherkin: https://youtu.be/SXaK4mhaerE
- <strike>Para automação das funcionalides front-end, busque usar um framework JavaScript;</strike>
- Utilize o Postman para automação da funcionalidade back-end;


# O que vamos avaliar
- A estruturação e escrita dos cenários de testes;
- <strike>Os cenários e validações das automações;</strike>
- A utilização de padrões de projetos;
- A estruturação do projeto;
- <strike>Boas práticas de programação;</strike>


# A apresentação do desafio
- Para enviar faça um fork dete projeto coloque os arquivos e abra uma Pull Request
  - Obs: Apenas abra a Pull Reques não faça o merge da mesma
  - Obs 2: Use comandos do git para subir as alterações
- Export também a collection do postman em json e também adicione o arquivo nesse projeto
  - Como exportar: https://learning.postman.com/docs/getting-started/importing-and-exporting-data/#exporting-collections
