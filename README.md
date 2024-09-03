# Hello Word! 👋

## Sobre Mim
- 👩‍💻 Desenvolvedora iniciante apaixonada por tecnologia.
- 🌱 Aprendendo constantemente e buscando novos desafios.
- 💼 Universitária.
- 📚 Compartilhando conhecimento através de projetos e tutoriais.

## Habilidades em treinamento

- **Linguagens:** HTML, CSS, JavaScript, Python, Java.
- **Frameworks:** React, Node.js, Flask, Spring Boot.
- **Ferramentas:** Git,VS Code

## Projetos Destacados
- [Projeto A]:
- Totoro em Defesa da Floresta 🌳🌲
Sobre o Projeto
"Totoro em Defesa da Floresta" é um projeto inspirado no filme "Meu Vizinho Totoro" do Studio Ghibli. Este site foi criado com o propósito de conscientizar sobre os impactos do desmatamento nas áreas florestais, assim como no enredo do filme, onde a floresta é um lugar mágico e essencial para o equilíbrio da natureza.

Áreas Mais Afetadas
Nosso site aborda as áreas mais afetadas pelo desmatamento, destacando os impactos ambientais, sociais e econômicos dessas ações. Além disso, oferecemos informações detalhadas sobre as consequências do desmatamento, como a perda da biodiversidade, o aumento das mudanças climáticas e o comprometimento dos recursos naturais.

Recursos do Site:

Mapa Interativo: Explore as regiões afetadas pelo desmatamento em um mapa interativo, mostrando dados e estatísticas detalhadas.

Notícias e Atualizações: Mantenha-se informado com as últimas notícias sobre conservação ambiental, iniciativas de reflorestamento e medidas de proteção das florestas.

Dicas de Preservação: Aprenda como você pode contribuir para a preservação das florestas e do meio ambiente em geral, através de dicas práticas e ações sustentáveis.

Galeria de Imagens: Explore uma galeria de imagens inspiradoras das florestas ao redor do mundo, destacando sua beleza e importância.

Junte-se à Causa

Participe da nossa missão em defesa das florestas! Seja um defensor da natureza, compartilhe conhecimento, apoie projetos de conservação e adote práticas sustentáveis no seu dia a dia. Juntos, podemos fazer a diferença e proteger os tesouros naturais que são as florestas

- [Projeto B]:
 RPG entre Amigos - Projeto de Site
Descrição
Este projeto é um site para um RPG (Role-Playing Game) jogado entre amigos. O site permite que os jogadores gerenciem personagens, visualizem histórias e participem de sessões de jogo. O objetivo é criar uma plataforma onde os jogadores possam interagir e acompanhar o progresso da campanha de forma eficiente e divertida.
Entrar

Cadastrar
Você disse:
Analisando o código 1, solucione os seus erros completando corretamente as lacunas do código 2:

Dicas:
- Utilize a tag adequada para títulos.
- A lista Pai (referente à competição) deve possuir marcadores de alfabeto romano maiúsculo.

Código 1 (com erros):
<!DOCTYPE html>
<html>
<head>
 <description>Copa Rio - São Paulo</description>
</head>
<body>
<h1>Copa Rio - São Paulo</h1>
 <li>
 <li>
  <h2>Times do Rio de Janeiro</h2>
  <ul>
   <li>Flamengo</li>
   <li>Vasco</li>
   <li>Fluminense</li>
   <li>Botafogo</li>
  </ol>
 </li>
 <li>
  <h2>Times de São Paulo</h2>
  <ul>
   <li>Palmeiras</li>
   <li>Corinthians</li>
   <li>São Paulo</li>
   <li>Santos</li>
   <li>Portuguesa</li>
  </ol>
 </li>
</li>
</body>
</html>




Código 2 (sem erros):
<!DOCTYPE html>
<html>
<head>
 
digite

</head>
<body>
<h1>Copa Rio - São Paulo</h1>
 
digite

  <li>
  <h2>Times do Rio de Janeiro</h2>
  <ul>
   <li>Flamengo</li>
   <li>Vasco</li>
   <li>Fluminense</li>
   <li>Botafogo</li>
  
digite

 </li>
 <li>
  <h2>Times de São Paulo</h2>
  <ul>
   <li>Palmeiras</li>
   <li>Corinthians</li>
   <li>São Paulo</li>
   <li>Santos</li>
   <li>Portuguesa</li>
  
digite

 </li>
digite

</body>
</html>
O ChatGPT disse:
ChatGPT
Para corrigir os erros no Código 1 e completar o Código 2 corretamente, você deve considerar as seguintes questões:

Tag <description> não existe: No HTML, a tag correta para descrever a página é a <meta>, e ela deve estar dentro da tag <head>.

Elementos de lista devem estar dentro de <ul> ou <ol>: No Código 1, você usou <li> sem uma lista contêiner correta. A lista pai deve ser uma <ul> (lista não ordenada) ou <ol> (lista ordenada). Neste caso, uma lista não ordenada é adequada.

Fechamento das tags de lista: As tags <ul> foram fechadas com <ol>, o que é um erro. Devem ser fechadas com </ul>.

Estrutura correta das listas: A lista principal deve ter marcadores de alfabeto romano maiúsculo. Para isso, use <ol type="I">.

Aqui está o Código 2 corrigido:

html
Copiar código
<!DOCTYPE html>
<html>
<head>
 <meta charset="UTF-8">
 <meta name="description" content="Copa Rio - São Paulo">
 <title>Copa Rio - São Paulo</title>
</head>
<body>
<h1>Copa Rio - São Paulo</h1>
 <ol type="I"> <!-- Lista principal com marcadores de alfabeto romano maiúsculo -->
  <li>
   <h2>Times do Rio de Janeiro</h2>
   <ul>
    <li>Flamengo</li>
    <li>Vasco</li>
    <li>Fluminense</li>
    <li>Botafogo</li>
   </ul> <!-- Fechamento correto da lista não ordenada -->
  </li>
  <li>
   <h2>Times de São Paulo</h2>
   <ul>
    <li>Palmeiras</li>
    <li>Corinthians</li>
    <li>São Paulo</li>
    <li>Santos</li>
    <li>Portuguesa</li>
   </ul> <!-- Fechamento correto da lista não ordenada -->
  </li>
 </ol> <!-- Fechamento correto da lista principal -->
</body>
</html>
Explicações:
Tag <meta>: Foi usada para descrever a página e incluir a codificação de caracteres.
Tag <title>: Adicionada para definir o título da página na aba do navegador.
Tag <ol> com type="I": Para a lista principal com marcadores romanos maiúsculos.
Fechamento correto das listas: Usou <ul> para as listas de times e fechou com </ul>. A lista principal é fechada com </ol>.
Assim, o HTML estará estruturado corretamente e exibirá as informações conforme desejado.



Você disse:
Preencha corretamente o código HTML abaixo:

digite

<html>
<head>
 <title>Categorias de Produtos</title>
</head>
<body>
 <h1> Categorias de Produtos</h1>
 
digite

  <li>
   <h2>Eletrodomésticos</h2>
   <ul>
    <li>Geladeira</li>
    <li>Micro-ondas</li>
    <li>Máquina de Lavar</li>
   </ul>
  </li>
  <li>
   <h2>Móveis</h2>
   
digite

    <li>Cama</li>
    <li>Sofá</li>
    <li>Mesa de jantar</li>
   
digite

  </li>
 
digite

</body>
</html>
O ChatGPT disse:
ChatGPT
Para preencher corretamente o código HTML, você deve garantir que todos os elementos de lista estejam corretamente aninhados e fechados. A estrutura HTML básica para a lista de categorias e seus itens deve ser revisada. Aqui está o código HTML preenchido corretamente:

html
Copiar código
<!DOCTYPE html>
<html>
<head>
 <title>Categorias de Produtos</title>
</head>
<body>
 <h1>Categorias de Produtos</h1>
 
 <ul> <!-- Lista principal iniciada -->
  <li>
   <h2>Eletrodomésticos</h2>
   <ul>
    <li>Geladeira</li>
    <li>Micro-ondas</li>
    <li>Máquina de Lavar</li>
   </ul>
  </li>
  <li>
   <h2>Móveis</h2>
   <ul>
    <li>Cama</li>
    <li>Sofá</li>
    <li>Mesa de jantar</li>
   </ul>
  </li>
 </ul> <!-- Lista principal fechada -->
 
</body>
</html>
Explicações:
Tag <ul>: Adicionada para criar uma lista não ordenada contendo as categorias de produtos.

Fechamento correto das listas: A lista principal é iniciada com <ul> e fechada com </ul>. Dentro dela, cada categoria é representada por um <li>, e cada categoria contém sua própria lista não ordenada <ul> com seus itens.

Indentação e estrutura: A indentação ajuda na leitura e manutenção do código, garantindo que as listas estejam corretamente aninhadas.

Com essas adições e correções, o código HTML está completo e estruturado corretamente.



Você disse:
me ajude, descreva um curriculo de um aluno no segundo periodo do curso Sistemas para intenet
O ChatGPT disse:
ChatGPT
Claro, posso te ajudar com isso! Um currículo para um aluno no segundo período do curso de Sistemas para Internet deve refletir as habilidades, conhecimentos e experiências que ele já adquiriu. Aqui está um exemplo de como você pode descrever um currículo para esse aluno:

[Nome do Aluno]

[Endereço]
[Cidade, Estado, CEP]
[Telefone]
[E-mail]
[LinkedIn] (opcional)
[GitHub] (opcional)

Objetivo
Estudante do segundo período do curso de Sistemas para Internet, com forte interesse em desenvolvimento web e programação. Busco uma oportunidade para aplicar e expandir meus conhecimentos em um ambiente prático e desafiador, contribuindo para projetos de desenvolvimento e adquirindo experiência prática na área.

Educação
Curso: Sistemas para Internet
[Nome da Instituição], [Cidade]
Data de Início: [Mês/Ano] - Previsão de Conclusão: [Mês/Ano]

Em andamento (2º período concluído)
Experiência Acadêmica
Projetos Acadêmicos

Desenvolvimento de Aplicação Web
Descrição: Projeto individual realizado na disciplina de Programação Web. Desenvolvi uma aplicação web utilizando HTML, CSS e JavaScript, que inclui funcionalidades básicas de CRUD (Create, Read, Update, Delete) com armazenamento local.
Tecnologias: HTML, CSS, JavaScript, Local Storage

Sistema de Gerenciamento de Tarefas
Descrição: Projeto em grupo focado na criação de um sistema de gerenciamento de tarefas com interface amigável. Implementamos a estrutura do front-end e o gerenciamento de dados utilizando uma API REST.
Tecnologias: HTML, CSS, JavaScript, API REST

Habilidades Técnicas
Linguagens de Programação: HTML, CSS, JavaScript
Desenvolvimento Web: Criação de páginas estáticas e dinâmicas, desenvolvimento de interfaces responsivas
Ferramentas e Tecnologias: Git (controle de versão), Visual Studio Code, Figma (design de interfaces)
Conceitos: Estruturas de dados básicas, programação orientada a objetos, design de interfaces
Certificações e Cursos
Introdução ao Desenvolvimento Web
Plataforma: [Nome da Plataforma de Cursos Online]
Data: [Mês/Ano]

Fundamentos de JavaScript
Plataforma: [Nome da Plataforma de Cursos Online]
Data: [Mês/Ano]

Atividades Extracurriculares
Participante do Clube de Tecnologia
Descrição: Atividades de aprendizado colaborativo, workshops e hackathons para aprimorar habilidades técnicas e networking.
Idiomas
Português: Nativo
Inglês: Intermediário (leitura e compreensão de documentação técnica)
Referências
Disponíveis mediante solicitação.

Dicas Adicionais:
Atualize regularmente: Certifique-se de manter o currículo atualizado com novos projetos e habilidades adquiridas.
Personalize: Ajuste o currículo conforme o tipo de vaga ou estágio desejado, destacando as habilidades e experiências mais relevantes.
Formatação: Mantenha o currículo claro e bem formatado, utilizando títulos e seções distintas para facilitar a leitura.
Esse modelo é uma base que pode ser adaptada conforme suas necessidades e experiências pessoais.



Você disse:
crie um retertorio para um projeto de codigo de um site de um rpg entre amigos descrito
O ChatGPT disse:
ChatGPT
Claro! Um repositório para um projeto de código de um site de RPG entre amigos deve ser bem organizado e fornecer informações claras sobre o projeto. Abaixo está um exemplo de como você pode estruturar o README.md para esse projeto. Esse arquivo README deve ser colocado na raiz do repositório.

RPG entre Amigos - Projeto de Site
Descrição
Este projeto é um site para um RPG (Role-Playing Game) jogado entre amigos. O site permite que os jogadores gerenciem personagens, visualizem histórias e participem de sessões de jogo. O objetivo é criar uma plataforma onde os jogadores possam interagir e acompanhar o progresso da campanha de forma eficiente e divertida.

Funcionalidades
-Cadastro e Login de Usuários: Sistema de autenticação para jogadores e mestres de jogo.
-Gestão de Personagens: Cadastro, edição e visualização de personagens dos jogadores.
-História e Missões: Seções para descrever a história do RPG e gerenciar missões.
-Notas de Jogo: Espaço para que o mestre e os jogadores possam adicionar notas e informações importantes.
-Sessões de Jogo: Interface para gerenciar e visualizar sessões de jogo anteriores e futuras.

Claro! Um repositório para um projeto de código de um site de RPG entre amigos deve ser bem organizado e fornecer informações claras sobre o projeto. Abaixo está um exemplo de como você pode estruturar o README.md para esse projeto. Esse arquivo README deve ser colocado na raiz do repositório.

RPG entre Amigos - Projeto de Site
Descrição
Este projeto é um site para um RPG (Role-Playing Game) jogado entre amigos. O site permite que os jogadores gerenciem personagens, visualizem histórias e participem de sessões de jogo. O objetivo é criar uma plataforma onde os jogadores possam interagir e acompanhar o progresso da campanha de forma eficiente e divertida.

Funcionalidades
Cadastro e Login de Usuários: Sistema de autenticação para jogadores e mestres de jogo.
Gestão de Personagens: Cadastro, edição e visualização de personagens dos jogadores.
História e Missões: Seções para descrever a história do RPG e gerenciar missões.
Notas de Jogo: Espaço para que o mestre e os jogadores possam adicionar notas e informações importantes.
Sessões de Jogo: Interface para gerenciar e visualizar sessões de jogo anteriores e futuras.

Tecnologias Utilizadas

Frontend: HTML, CSS, JavaScript
Backend: Node.js, Express.js
Banco de Dados: MongoDB
Autenticação: Passport.js
Ferramentas: Git, GitHub, Visual Studio Code
