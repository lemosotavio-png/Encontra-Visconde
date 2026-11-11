# Encontra Visconde

Aplicação web escolar para catalogar objetos encontrados no Colégio Estadual Visconde de Guarapuava e facilitar a busca e a solicitação de retirada.

## Objetivo
Organizar a divulgação de objetos achados e perdidos, reduzindo o tempo de procura e apoiando a devolução presencial pela inspetoria.

## Funcionalidades da Sprint 1
- Busca por nome e descrição.
- Filtro por categoria e situação.
- Cadastro de usuário e login demonstrativos.
- Cadastro de objeto encontrado.
- Visualização dos detalhes do item.
- Solicitação de retirada com geração de código.
- Área administrativa demonstrativa para marcar itens como devolvidos.
- Layout responsivo para computador e celular.

## Tecnologias
- HTML5
- CSS3
- JavaScript (Vanilla)
- localStorage para persistência local de demonstração.

## Como executar
1. Baixe ou clone este repositório.
2. Abra `index.html` em um navegador moderno.
3. Para melhor experiência, use a extensão Live Server do VS Code.

Não há instalação de dependências.

## Estrutura
```
.
├── index.html
├── .gitignore
├── README.md
├── css/
│   └── style.css
├── js/
│   └── app.js
└── docs/
    ├── backlog-sprint-1.md
    └── retrospectiva-modelo.md
```

## Dados e segurança
Esta versão é um protótipo acadêmico front-end. Usuários, itens e solicitações ficam no armazenamento local do navegador e não são compartilhados entre dispositivos. A autenticação é apenas demonstrativa e **não deve ser usada com senhas reais**. Para uso real, será necessário backend, banco de dados, autenticação segura e controle de acesso no servidor.

Os itens pré-carregados são exemplos fictícios para demonstração, não registros reais do colégio.

## Equipe
- Otávio Lemos
- Gustavo Neves

## Próximos passos
- Criar backend e banco de dados.
- Implementar autenticação segura.
- Adicionar upload de imagens.
- Criar permissões reais para inspetores.
- Testar com a equipe escolar antes de qualquer uso real.
