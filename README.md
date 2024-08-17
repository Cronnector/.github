# Cronnector

## Descrição

O **Cronnector** é uma plataforma desenvolvida para ajudar organizações e pequenas empresas a gerir e monitorizar ordens de trabalho, tarefas e serviços. A aplicação oferece uma gama de funcionalidades para otimizar a gestão de serviços, desde o planeamento até à execução e fiscalização.

## Funcionalidades

### 1. **Gestão de Ordens de Trabalho**
   - **Criação e Monitorização**: Permite criar ordens de trabalho detalhadas, incluindo informações como endereço, descrição, coordenadas geográficas e estado.
   - **Tarefas e Penalidades**: As ordens de trabalho são compostas por tarefas obrigatórias ou opcionais. Penalidades podem ser aplicadas se tarefas não forem concluídas dentro dos prazos estabelecidos.
   - **Estados e Status**: Acompanhe o estado das ordens de trabalho, como "Pendente", "Em Progresso", "Concluída", "Fechada" e "Cancelada".

### 2. **Gestão de Utilizadores e Funções**
   - **Utilizadores e Papéis**: Cadastro de utilizadores com diferentes papéis e níveis de acesso (Admin, Colaborador, Coordenador).
   - **Coordenadores de Centros de Trabalho**: Designação de coordenadores para centros de trabalho específicos.

### 3. **Gestão de Tarefas**
   - **Tipos e Preços**: Defina tipos de tarefas e associe preços específicos para cada tarefa.
   - **Registro de Tarefas**: Acompanhe o progresso das tarefas associadas a ordens de trabalho e ajuste conforme necessário.

### 4. **Centros de Trabalho**
   - **Cadastro e Localização**: Gere centros de trabalho com detalhes como endereço, coordenadas geográficas e zona.
   - **Equipa e Coordenação**: Atribua utilizadores aos centros de trabalho e defina os seus papéis.

### 5. **Relatórios e Inspeções**
   - **Relatórios**: Permita que colaboradores reportem defeitos ou questões relevantes.
   - **Inspeções**: Realize inspeções para avaliar a execução das ordens de trabalho e atribua tarefas específicas para inspeção.

### 6. **Pendências e Penalidades**
   - **Tipos de Pendência**: Registe e categorize situações que impossibilitam a execução de ordens de trabalho.
   - **Penalidades**: Aplique penalidades baseadas em tipos de pendência e tarefas não realizadas.

## Estrutura da Base de Dados

A aplicação utiliza uma base de dados relacional para armazenar informações. As principais tabelas incluem:

- **`orders`**: Informações sobre ordens de trabalho.
- **`tasks`**: Detalhes das tarefas associadas a ordens de trabalho.
- **`users`**: Dados dos utilizadores da aplicação.
- **`organizations`**: Informações sobre as organizações.
- **`workCenters`**: Centros de trabalho e suas informações.
- **`workCenterUsers`**: Relação entre utilizadores e centros de trabalho.

## Contribua

Este projeto está aberto a contribuições de programadores! Se deseja ajudar a melhorar a aplicação, aqui estão algumas maneiras de contribuir:

1. **Reporte Erros**: Envie relatórios de problemas encontrados na aplicação.
2. **Sugira Funcionalidades**: Proponha novas funcionalidades ou melhorias.
3. **Contribua com Código**: Faça um fork do repositório, crie uma branch para a sua funcionalidade ou correção e envie um pull request.

## Como Começar

Para começar a trabalhar com a aplicação:

1. **Clone o Repositório**: `git clone https://github.com/cronnector/cronnector.git`
2. **Instale Dependências**: Siga as instruções no arquivo `INSTALL.md` para configurar o ambiente.
3. **Execute a Aplicação**: Instruções para iniciar a aplicação estão no `RUN.md`.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

## Contacto

Para dúvidas ou mais informações, entre em contacto através do e-mail: hey@cronnector.com

