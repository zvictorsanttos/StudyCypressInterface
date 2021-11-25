# Cypress + Cucumber

Pré-requisitos para rodar localmente Instalação no Windowns Atenção: É necessário que a máquina esteja com todas as dependencias instaladas: Usar o comando abaixo dentro da pasta raíz: npm install

Iniciando os passos para rodar os testes Entrar pelo terminal do projeto Usar o comando npm run cy:open Resumindo o projeto Nesta pasta e dentro dela temos a features que estão dentro da pasta "spec" , e os cenarios pesquisa-médicos.feature.feature são os cenários própriamente ditos Na pasta "pages" ficam nossos elementos e métodos da página denomidados "pesquisa.page.js" step_definitions são nossos steps gerados pelo cucumber Na pasta screenshots é uma pasta onde o cypress colocará o prints dos resultadosdos testes A pasta \_base.page.js é a pasta onde encontramos métodos que possam auxiliar no projeto.

Para Rodar os testes utilizar o comando pelo terminal: npx cypress open

# Atenção

O Teste foi realizado e um ambiente de produção, poderá ocorrer quebras de acordo com o momento em que está o sistema.
