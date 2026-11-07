# 🚀 Portfólio Profissional Pessoal

## Nome do Aluno
Kleberson Diego de Castro

## Descrição do Portfólio
Este projeto consiste na evolução e desenvolvimento de um portfólio web pessoal e profissional. O objetivo principal foi criar uma interface moderna, totalmente responsiva e interativa para destacar trajetórias, habilidades técnicas e projetos desenvolvidos.

## Tecnologias Utilizadas
* **HTML5 & CSS3**: Estruturação semântica e estilização customizada.
* **Bootstrap 5**: Framework CSS para layout responsivo, sistema de grid e componentes.
* **Git & GitHub / GitHub Pages**: Controle de versão e hospedagem contínua.

## Link do Site Publicado
*(Insira aqui o link do seu GitHub Pages após a ativação)*

## Explicação do Funcionamento do Projeto
O site está estruturado em uma página única com navegação fluida por âncoras no menu superior fixo:
1. **Seção de Perfil**: Apresentação pessoal e resumo profissional.
2. **Seção de Habilidades (Recurso Novo)**: Visualização gráfica do nível de domínio em diferentes competências através de barras de progresso animadas.
3. **Seção de Projetos**: Cards interativos organizados em grid, detalhando os trabalhos realizados com efeitos visuais de hover.
4. **Seção de Contato**: Formulário estruturado para captação de mensagens.

## Descrição do Recurso Novo Adicionado
Como recurso avançado além do modelo base visto em aula, foram implementadas **Barras de Progresso Animadas** para a seção de Habilidades e **Efeitos de Hover** personalizados nos cards de projetos (elevação suave do elemento e sombra aprimorada ao passar o cursor).

## Explicação de Como Esse Recurso Foi Implementado
* **Barras de Progresso**: Utilizou-se os componentes nativos de `progress` do Bootstrap combinados com classes de listras e animação (`progress-bar-striped progress-bar-animated`).
* **Efeitos de Hover**: Foi inserido um bloco de CSS customizado na seção de estilo (`<style>`), aplicando a propriedade `transition: transform 0.3s ease, box-shadow 0.3s ease;` em conjunto com o seletor `:hover` para alterar a elevação do card (`transform: translateY(-5px);`).
