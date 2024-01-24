# Dashboard de Clientes

## 1. Getting Started
Olá, candidato. Este desafio faz parte do processo seletivo para desenvolvedores FullStack da **Predialize**. Somos uma startup que fornece uma plataforma para a gestão inteligente do pós-obra de construtoras de todo o país. 
Temos um time incrível e estamos em busca de mais pessoas que possam agregar com maturidade (sem perder a descontração) e muito gás para conquistar o mundo!

E aí, topa o desafio?

## 2. Sobre
- O projeto já possui uma estrutura básica inicial para que você não perca tempo com coisas que não estamos interessados em avaliar.
- O propósito deste projeto serve apenas para fins de avaliação em relação à sua _experiência_, _capacidade em resolver problemas_ e _conhecimentos da stack utilizada._ **Os dados contidos aqui são todos fictícios**.
- O projeto está divido em dois módulos: **Api** e **App**. A Api foi construída utilizando **NodeJs** e no App, utilizamos **Angular**. Ambas tecnologias utilizadas na Predialize.
- Não será necessário desenvolver testes automatizados, mas se você quiser adicionar, fique à vontade.
- Na raíz da Api, está mantido o arquivo `clients.mock.js`. Este arquivo será a base para realizar consultas e retornar os resultados. Será o nosso banco de dados para esta etapa!
- O desafio será dividido em **3 partes**: na primeira (4.1), você deve descobrir e resolver os bugs do app para seguir para a segunda etapa (4.2), onde você terá que implementar novas features para nossa página de clientes, que está em branco. A terceira etapa (4.3) será apenas garantir que a api rode em qualquer sistema que utilize Docker. 

## 3. Premissas e Restrições
- Este repositório deve ser **baixado (download) e não clonado**, sob efeito de desclassificação imediata.
- **Não faça fork, pull requests, nem favorite este repositório**, sob efeito de desclassificação imediata.
- **Você pode** mexer o quanto quiser na estrutura de pastas e no código já disponibilizado de acordo com o que acredita que seja melhor.
- **Você não deve** utilizar libs ou frameworks que já não estejam listadas no package.json.
- **A UI do seu projeto será avaliada**. Não precisa se preocupar com efeitos ou componentes não previstos no angular-material, mas a arquitetura da informação, espaçamentos e consistência do layout serão considerados.
- **Você não deve** fazer mais do que está sendo pedido, sob efeito de desclassificação imediata.

## 4. Desafio
Queremos construir um dashboard de clientes e empreendimentos para termos uma visão estratégica do nosso portfólio. Mas, para alcançarmos nosso objetivo, precisamos resolver alguns BUGs e evoluir um pouco mais nossa Api e App.

### 4.1. Jogo dos 7 erros

Nosso dashboard **não está funcionando.** Para começarmos a melhorá-lo, precisamos primeiro fazê-lo funcionar. Existem _7 erros_ em nosso **App** e cabe a você descobrir o que está acontecendo.

PS: **Corrija, anote os erros e mostre a lista no corpo do email de resposta ao nosso contato**.

Mãos à obra!

### 4.2. Novas Features

Se vocês chegou até aqui, parabéns! Agora, vamos melhorar nosso projeto? Abaixo segue o escopo das novas funcionalidades desejadas:

- **Na página de Clientes, o usuário deve visualizar os resultados na sua tela**.
  - Requisitar informações da api;
  - Retornar e exibir os campos: _id, imagem, nome, quantidade de empreendimentos e quantidade de imóveis/unidades de cada cliente.
  - Os itens poderão ser exibidos em lista, cards, tabela ou qualquer componente que você deseje.
    
- **Na página de Clientes, o usuário deve poder pesquisar por nome do cliente e ver os resultados de acordo com sua pesquisa.**
  - O filtro deve ser realizado somente no frontend.
  - O filtro deve ser aplicado no evento de digitação do usuário.
    
- **Na página de Clientes, o usuário deverá poder visualizar alguns totalizadores:**
  - Requisitar informações da api;
  - Retornar e exibir somente os totais de: _Clientes, Empreendimentos e Imóveis/Unidades;_
    
- **Na página de Clientes, o usuário deverá poder selecionar/clicar em um item e ver seus detalhes:**
  - Requisitar informações da api;
  - Retornar somente: _\_id, imagem, nome, total de empreendimentos e total de imóveis/unidades_;
  - Exibir as informações obtidas;

- **Na página de Detalhes do Cliente, o usuário deverá poder ver todos os empreendimentos referentes a ele:**
  - Requisitar informações da api;
  - Retornar e exibir somente: _\_id, imagem, nome e total de Imóveis/Unidades_;

### 4.3. Docker
Se você chegou até aqui, parabéns! Estamos quase terminando. Agora precisamos apenas garantir que sua api rodará em qualquer lugar usando Docker, mas existem algumas premissas:
- Você **deve usar** Docker Compose.
- Seu docker-compose.yml deve sincronizar/mapear as alterações do host com o volume do container.
 
## 5. Sobre a Entrega
- Você terá 2 dias para finalizar o teste.
- Ao final, coloque seu código em um repositório público seu após finalizar o teste. Não importa onde (github, gitlab etc), desde que esteja público, e envie o link do seu repositório no corpo do email de resposta ao nosso contato.

## 6. Próximas Etapas
- Seu código será analisado por nossa equipe e, em caso positivo, entraremos em contato para a última etapa da nossa análise técnica: um **hands-on** e um **quick questions** com um de nossos desenvolvedores.
- Caso avance, você terá uma conversa com nossa gerente de pessoas e com nosso CTO e co-founder.
- Caso avance, você terá uma conversa com nosso time de produto e desenvolvimento.
- Caso avance, você terá uma conversa com nosso CEO e co-founder.
- Caso avance, você receberá a proposta formal de trabalho e, caso aceite, você está dentro!!!

# Boa Sorte!
Para saber mais sobre nós, acesse: https://predialize.com.br
