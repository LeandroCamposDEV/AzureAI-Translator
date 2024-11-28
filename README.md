Tradutor de Artigos Técnicos com AzureAI

Este projeto foi desenvolvido como parte do Bootcamp Microsoft Certification Challenge #1 - AI 102, com o objetivo de explorar e aplicar conceitos de inteligência artificial utilizando os serviços do Azure OpenAI e Translator. A aplicação automatiza a tradução de artigos técnicos, facilitando o acesso e a compreensão de conteúdos em diferentes idiomas.

🛠️ Funcionalidades

Extração de texto de URLs: Coleta texto de páginas web automaticamente.
Tradução automatizada: Traduz textos para o idioma desejado utilizando a API Translator do Azure.
Integração com Azure OpenAI: Oferece traduções contextualizadas e de alta qualidade.

🚀 Tecnologias utilizadas

Azure Translator API
Azure OpenAI API
Python
Google Colab

📋 Pré-requisitos
Para executar o projeto, você precisa:

Ter uma conta no Microsoft Azure.
Configurar os serviços no Azure:
Translator: Criar e ativar uma instância do serviço.
Azure OpenAI: Configurar um endpoint para o uso de modelos GPT.
Obter as chaves de acesso e endpoints fornecidos pelo Azure.

📂 Organização do projeto

src/: Contém os scripts principais para execução do projeto.
notebooks/: Contém os experimentos realizados no Google Colab.
README.md: Documentação do projeto.

🧑‍💻 Como executar o projeto

Clone o repositório e instale as dependências necessárias.
Configure as variáveis de ambiente com as chaves e endpoints do Azure.
Execute o sistema para traduzir textos técnicos a partir de URLs.

📈 Resultados esperados

O sistema realizará os seguintes passos:

Extrairá o texto de uma URL fornecida.
Traduzirá o texto para o idioma desejado (ex.: português).
Exibirá a tradução ou salvará o resultado em um arquivo.

🌐 Exemplos de uso

O sistema pode ser usado para traduzir textos técnicos extraídos diretamente de artigos online, facilitando o acesso ao conteúdo em diferentes idiomas.

📖 Referências

Documentação do Azure Translator
Documentação do Azure OpenAI

🤝 Contribuições

Contribuições são sempre bem-vindas! Caso tenha sugestões ou encontre problemas, sinta-se à vontade para abrir uma issue ou enviar um pull request.