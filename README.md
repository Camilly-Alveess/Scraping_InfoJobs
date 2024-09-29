# Projeto de Web Scraping - InfoJobs com UiPath

Este projeto tem como objetivo realizar o scraping de dados do site InfoJobs, especificamente da página de ranking das melhores empresas. Os dados extraídos serão utilizados em análises comparativas com informações coletadas do Glassdoor.

## Objetivos

- Coletar informações sobre as melhores empresas do InfoJobs.
- Extrair dados relevantes, como notas e classificações.
- Comparar essas informações com dados previamente coletados do Glassdoor.
- Armazenar os dados em uma estrutura adequada para análises posteriores.

## Pré-requisitos

Antes de executar este projeto, você precisará dos seguintes pré-requisitos:

- **UiPath Studio** (preferencialmente a versão mais recente)
- Conexão com a internet para acessar o site InfoJobs.

## Instalação

1. **Baixar e Instalar o UiPath**:
   - Baixe a versão mais recente do UiPath Studio do [site oficial](https://www.uipath.com).
   - Siga as instruções de instalação.

2. **Configurar o Projeto**:
   - Abra o UiPath Studio e crie um novo projeto.
   - Adicione as dependências necessárias (se houver) através do Gerenciador de Pacotes.

## Uso

1. **Configurar o Workflow**:
   - Abra o arquivo de workflow principal (ex: `Main.xaml`).
   - Configure a atividade de scraping para coletar os dados necessários da página do InfoJobs.

2. **Executar o Workflow**:
   - Clique no botão "Run" para executar o fluxo de trabalho e coletar os dados.

3. **Visualizar os Resultados**:
   - Após a execução, os dados coletados serão salvos em um arquivo (como Excel ou CSV) conforme especificado no workflow.

## Exemplos de Atividades

Aqui estão algumas atividades comuns que podem ser utilizadas no seu projeto:

- **Use Browser**: Para puxar a página web que temos interesse.
- **Extract Data Table**: Para extrair dados das tabelas da página.
- **Tabela de Dados de Saída como Texto**: Para salvar os dados extraídos como texto.
- **Write Range**: Para salvar os dados em um arquivo Excel.

## Contribuições

Contribuições são bem-vindas! Se você deseja contribuir com melhorias ou novos recursos, por favor, siga as etapas abaixo:

1. Faça um fork deste repositório (se estiver em um repositório compartilhado).
2. Crie uma nova branch (se aplicável).
3. Faça suas alterações e commit.
4. Envie para o seu repositório (se aplicável) e abra um Pull Request.

## Licença

Este projeto está licenciado sob a MIT License - consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

## Contato

Se você tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato:

- **Camilly Alves** 
