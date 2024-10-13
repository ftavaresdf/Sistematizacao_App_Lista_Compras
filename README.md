# Autores
- Fernando Tavares da Silva - RA: 72300777
- Vanessa Silva de Macedo - 72300778
# Instruções de Instalação
- Pré-requisitos:
-- Android Studio 4.2 ou superior
-- Kotlin configurado no ambiente de desenvolvimento
-- Gradle 7.0 ou superior
-- Dispositivo Android com API mínima 24 (Android 7.0)
# Passos para instalação
- Faça o download do projeto no github e descompacte o arquivo.
- Abra o Android Studio e importe o projeto baixado.
- Sincronize o projeto com o Gradle para garantir que todas as dependências estejam configuradas corretamente.
- Conecte um dispositivo Android ou utilize um emulador com API 24 ou superior.
- Execute o projeto clicando no botão "Run" no Android Studio.
# Funcionalidades Desenvolvidas
- Lista de Produtos:
-- Exibe todos os produtos cadastrados em uma RecyclerView.
-- A lista é atualizada automaticamente ao retornar da tela de cadastro ou edição.
-- Ao clicar em um item, os detalhes do produto são exibidos.
- Cadastro de Produto:
-- Tela de formulário onde o usuário pode inserir o nome, descrição, valor e imagem do produto.
- Suporte à adição de imagens via URL utilizando o Coil para carregamento.
- Detalhes do Produto: Exibe as informações detalhadas de um produto selecionado, incluindo imagem, nome, descrição e valor formatado para o padrão brasileiro.
- Edição de Produto: Permite alterar as informações de um produto existente. Ao clicar no botão de edição, o formulário de cadastro é carregado com os dados atuais.
- Exclusão de Produto: O usuário pode remover um produto diretamente da tela de detalhes, com a opção de confirmar a ação através do menu.
- Persistência de Dados: Utiliza a biblioteca Room para persistir localmente os dados dos produtos no dispositivo. Inclui conversores para a manipulação do tipo BigDecimal no banco de dados.
- Formatação Monetária: Implementação de formatação de valores monetários para o padrão brasileiro (R$).
- Carregamento de Imagens: A biblioteca Coil é utilizada para carregar imagens de produtos, com placeholders para imagens ausentes ou erros de carregamento.
# Dependências Utilizadas
- Room Database: Para persistência local de dados.
- Coil: Para carregamento e exibição de imagens.
- Kotlin Parcelize: Para serialização de objetos Parcelable.
- Material Components: Para uso de componentes visuais no estilo Material Design.
- ViewBinding: Para evitar o uso de findViewById e facilitar a manipulação de views.
