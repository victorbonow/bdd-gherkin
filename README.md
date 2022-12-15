# ✨ bdd-gherkin
Este repositório é um versionamento de casos de comportamento e regras de negócio, escrito na linguagem Gherkin, e pode ser utilizado no conceito de BDD e em outros casos sendo uma forma de baixo custo de versionamento de regras de negócio e casos de comportamento.

Toda Feature ou Produto, depende de como chamam, fica dentro do mesmo arquivo, ou seja, todas as regras e casos de comportamento sobre o Login, por exemplo, ficam dentro do arquivo login.feature.

Qualquer pessoa do time pode utilizar, aprender e relembrar, porém, cabe ao QA de Produto ou QA Tester, escrever e dar manutenção nos casos de comportamento.


Toda a solução é muito interessante, pois gera vários benefícios como:
 - Se utilizada com o conceito de BDD, pode trazer mais segurança ao desenvolvimento, pois todos os casos de comportamento estão mapeados e versionados.
 - Se utilizada para guardar casos de comportamento e regras de negócios, gera um ótimo local de pesquisa e basta um Ctrl+f, para encontrar alguma palavra chave.
 - Casos de comportamento disponíveis no Github e no repositório local, o que facilita o acesso, para todos do time.
 - Integração de todo o time.
 - Se alguém esquecer alguma regra de negócio ou caso de comportamento, basta procurar o arquivo da Feature/Produto, para ter toda a documentação.
 - Pessoas de Produto e Desenvolvedores podem utilizar.

# Gherkin
...é uma poderosa linguagem natural desenvolvida para que humanos possam a utilizar como forma de entendimento e compreensão acerca das especificações levantadas a partir de perspectivas...

https://medium.com/revista-tspi/gherkin-o-dia-em-que-entendi-que-estava-escrevendo-errado-220a84520819

https://cucumber.io/docs/gherkin/reference/

---

# Utilização
Com foco na fácil manutenção e utilização, ou seja, simplificando ao máximo, todos os arquivos ficam na pasta features e a partir dela as ramificações vão aumentando.

![image](https://user-images.githubusercontent.com/35244036/207982734-7bc26d49-a186-41b5-968b-713ca0f0a0fd.png)

Depois da pasta feature, temos as feature1, 2, 3pt e por ai vai, sim tem escrita Gherkin em português :), que são as funcionalidades em si. Cada pasta de funcionalidade tem um arquivo único da funcionalidade.

![image](https://user-images.githubusercontent.com/35244036/207983351-7335aed2-82b2-4d4d-871e-6f1fb8258ccc.png)

---

Este repositório tem a divisão de arquivos por feature/funcionalidade, por exemplo, o Login seria um arquivo e o Cadastro outro.
Todos os arquivos devem seguir o padrão de funcionalidade.feature e devem ficar dentro da pasta Features.

Todos os comportamentos de testes são baseados em usabilidade e não em elementos, por exemplo:

1 - Então ao clicar no botão os dois dados serão enviados ❌


2 - Então submeto o formulario 

E todos os dados serão enviados 🆗


Com isto, se o botão deixar de existir ou forem adicionados mais dados no formulário, não será necessária a refatoração dos comportamentos de testes.

---

A estrutura dos arquivos .feature é composta por:
Feature:

Cenário: / Scenario:

Dado / Given

Quando / When

Então / Then

Mas / But

E / And

Ou / Or não funciona :/

Feature: é utilizado uma única vez no arquivo e todos os outros podem ser adicionados mais de uma vez, sendo separados por Cenários:

![image](https://user-images.githubusercontent.com/35244036/207983962-b89825e7-8d66-495e-8f7c-35c04bc738a5.png)
![image](https://user-images.githubusercontent.com/35244036/207985427-ddba9f6b-f958-483d-bba2-04d7a1e46931.png)



---

# ✨ Dica
Tudo fica mais fácil essa extensão gratuita do VSCode

![image](https://user-images.githubusercontent.com/35244036/207985097-49734d6b-8adc-426a-bed6-e4377b0ac735.png)

Extension ID: alexkrechik.cucumberautocomplete

Extension Marketplace: https://marketplace.visualstudio.com/items?itemName=alexkrechik.cucumberautocomplete
