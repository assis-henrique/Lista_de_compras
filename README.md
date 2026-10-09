# 🛒 Lista de Compras

**Organize suas compras de forma simples e prática!**

Aplicativo mobile desenvolvido com React Native, Expo e TypeScript.

</div>

---

## 📌 Sobre o projeto

O **Lista de Compras** é um aplicativo desenvolvido para facilitar a organização de produtos que precisam ser comprados. Com uma interface simples e intuitiva, o usuário pode visualizar os produtos, adicionar novos itens e remover aqueles que não são mais necessários.

O projeto foi desenvolvido com o objetivo de praticar conceitos de desenvolvimento mobile, componentização, gerenciamento de estados e tipagem com TypeScript.

## 🚀 Funcionalidades

📝 Adicionar produtos à lista.
🔢 Informar a quantidade de cada produto.
🗑️ Remover produtos da lista.
📋 Visualizar todos os itens cadastrados.
🔔 Exibir uma mensagem quando a lista estiver vazia.
🔢 Mostrar a quantidade de itens cadastrados.
📱 Interface organizada e adaptada para dispositivos móveis.

## 🛠️ Tecnologias utilizadas

**React Native** — criação da interface mobile.
**Expo** — configuração e execução do aplicativo.
**TypeScript** — tipagem e organização do código.
**JavaScript** — lógica e funcionamento da aplicação.
**StyleSheet** — estilização dos componentes.

## 📂 Estrutura do projeto
text
lista-de-compras/
├── components/
│   ├── Cabecalho.tsx
│   ├── FormularioItem.tsx
│   ├── ItemCompra.tsx
│   └── ListaCompras.tsx
├── App.tsx
├── index.tsx
├── types.ts
├── app.json
├── babel.config.js
├── package.json
└── tsconfig.json

## ⚙️ Como executar o projeto

### Pré-requisitos

Antes de começar, você precisa ter instalado:

[Node.js](https://nodejs.org/)
[Visual Studio Code](https://code.visualstudio.com/)
Um emulador Android ou o aplicativo Expo Go no celular, caso queira testar no dispositivo físico.

### 1. Clonar o repositório
bash
git clone URL_DO_SEU_REPOSITORIO

Substitua URL_DO_SEU_REPOSITORIO pelo endereço do seu repositório no GitHub.

### 2. Acessar a pasta do projeto
bash
cd lista-de-compras

### 3. Instalar as dependências
bash
npm install

### 4. Iniciar o aplicativo
bash
npx expo start
Depois de iniciar, utilize o QR Code exibido no terminal ou no navegador para abrir o aplicativo com o Expo Go. Também é possível executar a aplicação em um emulador compatível.

## 💻 Como funciona

O projeto foi dividido em componentes para facilitar a manutenção e a organização do código.

| Arquivo | Responsabilidade |
|---|---|
| App.tsx | Controla o estado da lista e integra os componentes. |
| Cabecalho.tsx | Exibe o título e a apresentação do aplicativo. |
| FormularioItem.tsx | Permite informar o nome e a quantidade do produto. |
| ItemCompra.tsx | Apresenta individualmente cada produto e sua opção de remoção. |
| ListaCompras.tsx | Exibe os produtos utilizando FlatList e mostra o estado vazio. |
| types.ts | Define a estrutura dos itens de compra com TypeScript. |

## 📚 Conceitos praticados

Durante o desenvolvimento, foram trabalhados os seguintes conceitos:

Criação e reutilização de componentes.
Propriedades (props) para comunicação entre componentes.
Gerenciamento de estado com o hook useState.
Renderização de listas com FlatList.
Tipagem de dados e funções com TypeScript.
Estilização com StyleSheet.
Validação de campos do formulário.
Organização de arquivos e pastas.

## 🔮 Melhorias futuras

Algumas funcionalidades que podem ser implementadas em versões futuras:

[ ] Salvar os produtos no armazenamento local.
[ ] Editar produtos cadastrados.
[ ] Marcar produtos como comprados.
[ ] Criar categorias de produtos.
[ ] Adicionar filtros e pesquisa.
[ ] Implementar um banco de dados para persistência das informações.

## 👨‍💻 Autor

Desenvolvido como projeto de estudo em desenvolvimento mobile.

**Tecnologias:** React Native • Expo • TypeScript

---

<div align="center">

⭐ Se este projeto foi útil para você, considere deixar uma estrela no repositório!

</div>
