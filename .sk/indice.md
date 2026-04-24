# Índice do Projeto

## Estrutura de Arquivos

### Raiz do Projeto
- **README.md**: Documentação do projeto, incluindo descrição, setup e instruções de uso.
- **package.json**: Gerenciador de dependências do projeto, especificando bibliotecas utilizadas.
- **.gitignore**: Arquivo que define quais arquivos ou pastas devem ser ignorados pelo Git.
- **.env.example**: Exemplo de arquivo de variáveis de ambiente a ser copiado para .env com valores reais.

### Diretório `src/`
- **main.tsx**: Ponto de entrada da aplicação React. Renderiza o componente principal e configura o roteamento.
- **App.tsx**: Componente principal da aplicação que contém a lógica de roteamento e estrutura da aplicação.
  
#### Diretório `src/components/`
- **AIChat.tsx**: Componente de chat que interage com a IA.
- **AssistenteJuridico.tsx**: Componente que fornece assistência jurídica ao usuário.
- **CampoLivre.tsx**: Componente para entrada de texto livre pelo usuário.
- **CodeEditor.tsx**: Editor de código com suporte a diversas linguagens.
- **DriveBackupPanel.tsx**: Componente que gerencia backups de arquivos.
- **GitHubPanel.tsx**: Componente para integração com o GitHub.
- **TemplateSelector.tsx**: Componente para seleção de templates prontos.
  
#### Diretório `src/hooks/`
- **use-mobile.tsx**: Hook personalizado para responsividade em dispositivos móveis.
- **use-toast.ts**: Hook para gerenciar mensagens de feedback ao usuário.

### Diretório `db/`
- **neon.js**: Configuração e inicialização do banco de dados Neon.
- **migrate.js**: Script para gerenciar migrações do banco de dados.

### Diretório `lib/`
- **ai-service.ts**: Serviço responsável pela interação com a API de IA.
- **github-service.ts**: Serviço para gerenciar operações com o GitHub.
- **projects.ts**: Funções relacionadas ao gerenciamento de projetos.

### Diretório `public/`
- **index.html**: Arquivo HTML principal que estrutura a aplicação web.
- **manifest.json**: Configuração para Progressive Web App (PWA).
  
## Dependências Externas
- **React**: Biblioteca para construção de interfaces de usuário.
- **React Router**: Biblioteca para gerenciamento de rotas em aplicações React.
- **Axios**: Biblioteca para fazer requisições HTTP.
- **dotenv**: Biblioteca para carregar variáveis de ambiente a partir do arquivo `.env`.
- **@neondatabase/serverless**: Biblioteca para conexão e gerenciamento do banco de dados Neon.

## Funções e Classes Principais
- **AIChat**: Classe que gerencia a comunicação com a IA e exibe as mensagens.
- **AssistenteJuridico**: Classe que fornece assistência jurídica ao usuário com base nas entradas.
- **DriveBackupPanel**: Classe que lida com operações de backup de arquivos.
- **GitHubPanel**: Classe que permite interações com repositórios do GitHub.

## Mapa de Relações Entre Arquivos