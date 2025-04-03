# Admin Dashboard

Repositório de um dashboard feito com Bootstrap 5

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Descrição do Projeto

Este repositório contém um dashboard administrativo simples, desenvolvido com Bootstrap 5. Ele oferece um layout básico com uma barra lateral, uma navbar fixa e uma área principal para exibição de dados e gráficos. O objetivo é fornecer um ponto de partida para a criação de interfaces administrativas mais complexas.

🔗 Acesse o projeto: [https://jaojogadez.github.io/admin-dashboard/]

## Funcionalidades

- **Layout Responsivo:** Desenvolvido com Bootstrap 5 para garantir compatibilidade em diferentes tamanhos de tela.
- **Sidebar Colapsável:** A barra lateral pode ser expandida ou reduzida através de um botão de toggle.
- **Navbar Fixa:** Contém uma barra de pesquisa e um menu suspenso de perfil do usuário.
- **Cartões de Dashboard:** Exibição de dados de exemplo em formato de cards.
- **Tabela de Dados:** Uma tabela HTML básica para visualização de informações de usuários.
- **Integração com Chart.js:** Exibição de um gráfico de barras representando dados fictícios.
- **Menu de Autenticação:** Opções de Login e Registro (não implementadas).
- **Menu Multi-Nível:** Exemplo de menu suspenso na barra lateral.

## Tecnologias Utilizadas

- **HTML:** Estrutura do dashboard.
- **CSS:** Estilização utilizando Bootstrap 5 e estilos personalizados em `style.css`.
- **JavaScript:** Funcionalidades como toggle da sidebar e renderização do gráfico.
- **Bootstrap 5:** Framework CSS para layout e estilização.
- **Boxicons:** Biblioteca de ícones via CDN.
- **Chart.js:** Biblioteca para criação de gráficos via CDN.

## Requisitos

- Um navegador web (Chrome, Firefox, Safari, etc.).
- Um editor de texto ou IDE (VSCode, Sublime Text, etc.).
- Conhecimento básico de HTML, CSS e JavaScript.

## Instalação e Execução

1. **Clone o repositório:**

    ```bash
    git clone https://github.com/jaojogadez/admin-dashboard.git
    ```

2. **Acesse o diretório do projeto:**

    ```bash
    cd admin-dashboard
    ```

3. **Abra o arquivo `index.html` no navegador.**

Este é um projeto estático, não necessário servidor.

## Guia de Uso

- **Toggle da Sidebar:** Clique no ícone `<i id="icon" class="bx bxs-chevrons-right"></i>` para colapsar ou expandir a barra lateral. Essa funcionalidade é controlada pela função `togglerNav()` no arquivo `script.js`.
- **Barra de Pesquisa:** Campo na navbar superior (apenas visual, sem funcionalidade implementada).
- **Menu de Perfil:** Clique na imagem de perfil para abrir um menu suspenso com opções (placeholders).
- **Tabela de Dados:** Exibição estática de informações de usuários.
- **Gráfico:** Representa crescimento populacional utilizando Chart.js. A configuração está no `script.js` e pode ser modificada conforme necessidade.

## Documentação da API

Este projeto não utiliza APIs externas. Os dados do gráfico são definidos estaticamente no `script.js`.

## Contribuição

Contribuições são bem-vindas! Para colaborar:

1. Fork o repositório.
2. Crie uma branch para sua funcionalidade ou correção.
3. Realize as alterações e faça commit com uma mensagem descritiva.
4. Envie suas modificações para o seu repositório.
5. Abra um Pull Request para a branch `main` deste repositório.

Certifique-se de seguir o padrão de código e adicionar comentários quando necessário.

## Licença

Este projeto está licenciado sob a MIT License. Consulte o arquivo `LICENSE` para mais informações.

```
MIT License

Copyright (c) 2024 jaojogadez

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## Contato e Suporte

Para dúvidas ou suporte, entre em contato:

- **GitHub:** [https://github.com/jaojogadez](https://github.com/jaojogadez)

