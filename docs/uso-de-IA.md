---
titulo: Uso de IA no projeto
descricao: Registro de todas as conversas com chatbot usadas no projeto, com data, etapa e finalidade.
autores: Thiago Henrique, Lucas Gabriel, Pedro Almeida
versao: v0.9
ultima_atualizacao: 2026-11-23
arquivos_relacionados: docs/04-versoes/ site/css/style.css
---

Cada uso de IA deve ser documentado neste documento. Caso haja uso de IA além do que for documentado, será atribuída nota zero para o trabalho.

A documentação ERRADA também será penalizada.

O uso de IA deve ser para assistencia, não execução do projeto. Os alunos ainda deverão responder a questões relacionadas ao desenvolvimento e código. A resposta incorreta será considerada como erro durante a avaliação e penalizará a nota.

## Regras de uso

- A IA responde dúvidas. O código é escrito pelo grupo.
- Cada integrante deve explicar, com as próprias palavras, qualquer trecho que tenha surgido de uma conversa.
- Copiar código gerado pela IA sem entendê-lo não é permitido. Se um trecho for usado, ele deve ser registrado na tabela.
- Ferramentas que editam o repositório ou geram código de forma autônoma (Claude Code, agentes do Copilot, Cursor agent e similares) não são permitidas. Se identificado, a nota do trabalho será zero.
- Linhas da tabela sem a respectiva print serão consideradas **ERROS** do grupo.

O modelo de dúvidas tiradas com a assistencia de IA deverão ter o seguinte formato:

| Data | Ferramenta | Etapa | Arquivo(s) afetado(s) | Motivo do uso e erro antes do uso | O que foi feito com a resposta | Link ou print |
|---|---|---|---|---|---|---|
| 2026-11-23 | ChatGPT | Estrutura HTML | site/index.html |  | Reorganizei o cabeçalho e as seções da página e testei no navegador | prints/ia-01.png |
| 2026-11-23 | ChatGPT | Responsividade | site/css/estilo.css | O menu sumia no celular e não sabíamos como adaptar o layout; tentamos ajustar larguras fixas sem sucesso | Entendi o uso de `@media` e escrevi a regra do menu hambúrguer por conta própria | prints/ia-02.png |
| 2026-11-23 | ChatGPT | Validação do formulário | site/js/main.js | O envio aceitava campos vazios e e-mail inválido; não tínhamos certeza de como validar em JavaScript | Não usei o trecho sugerido; implementei a validação com `required` no HTML e revisei a lógica com o professor | prints/ia-03.png |
| 2026-11-23 | ChatGPT | Organização da navegação | site/index.html | Estava com dificuldade para organizar o acesso às outras partes do site e queria deixar a navegação mais simples para o usuário | Entendi como funcionava uma navbar e adaptei a estrutura do menu para acessar as outras páginas | prints/ia-04.png |
| 2026-11-23 | ChatGPT | Menu de navegação | site/index.html | Não sabia como deixar o menu posicionado na parte superior da página e manter ele organizado | Usei as explicações para entender o posicionamento dos elementos e ajustei o menu no projeto | prints/ia-05.png |
| 2026-11-23 | ChatGPT | Organização dos personagens | site/index.html | Tinha dúvidas sobre como organizar as categorias de personagens para facilitar a navegação pelo site | Utilizei as sugestões para separar melhor as categorias e organizar os nomes das seções | prints/ia-06.png |
| 2026-11-23 | ChatGPT | Modal | site/css/estilo.css | O modal estava pequeno e algumas informações não ficavam bem organizadas dentro dele | Tirei dúvidas sobre largura, altura e espaçamento e fiz ajustes para melhorar a visualização | prints/ia-07.png |
| 2026-11-23 | ChatGPT | JavaScript | site/js/main.js | Estava com dificuldades para entender como utilizar JavaScript para controlar algumas ações e interações da página | Utilizei as explicações para entender melhor a lógica e fui adaptando as funcionalidades no próprio projeto | prints/ia-08.png |






