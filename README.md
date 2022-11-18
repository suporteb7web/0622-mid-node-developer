# Teste para vaga de Node Developer Junior

O objetivo deste teste é entender o candidato, sua experiência e sua capacidade de resolução de problemas com dúvidas e detalhes que serão exigidos no dia-a-dia como Node Veloper Junior.
O teste é baseado em questionamentos e problemas a serem resolvidos.

### Como será feito o teste?
O teste é dividido em 2 etapas:
- Questões teóricas.
- Projeto prático, quer seja correção de bug ou criação do mesmo.

O candidato precisa criar um repositório próprio com a seguinte estrutura:
- No README serão respondidas as questões teóricas (pergunta e resposta), de forma organizada e explicada.
- No próprio repositório estará o projeto prático, corrigido e/ou criado.

Após a finalização, o candidato deve enviar um e-mail para suporte@b7web.com.br com o link do repositório original (este) bem como o link do repositório pessoal com a resolução.

## Questões Teóricas

1. Qual a diferença entre WebService e API?
2. Em uma paginação por page (e não por offset), precisa setar o limite de itens por página? Por que?
3. O que significa Soft Delete?
4. Qual tipo de campo no SQL para armazenar textos grandes?
5. A requisição de atualização de conteúdo precisa ter qual método?

## Projeto prático

Crie um webservice em Node para um serviço de notícias, usando SQL e API Rest.

Essa aplicação deve fazer:
- Leitura de notícias, com paginação (por page, não por offset).
- Criação de notícia nova, validando dados e especificando autor.
- Atualização de notícia, com registro de data de atualização e criação.
- Soft delete de notícia, com registro de data de exclusão.

Toda a aplicação deve funcionar via API, com backend criado por você.
Pode utilizar a biblioteca EXPRESS para criação da API, só não pode utilizar frameworks completos como Adonis/Nest.

Colocar um arquivo .SQL com a criação da estrutura do banco de dados e eventuais dados iniciais (seeding) necessários.