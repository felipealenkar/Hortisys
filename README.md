# Hortisys

Sistema de gestão de hortas

# Tecnologias Utilizadas

Linguagem: Delphi Athens 12.1

Arquitetura: Clean Delphi Architecture.

Banco de Dados: PostgreSQL 18.

Relatórios: Fortes report.

Consumo de APIs REST: RESTClient/NetHttpClient.

# Funcionalidades Principais

Cadastro e controle de culturas botânicas.

Cadastro e controle de manejos das culturas

Geração de relatórios dos cadastros

Integração com APIs REST para busca de imagem da cultura na web. (Uso da Api do Gemini para identificação do nome correto caso o usuário cometa erros de gramática)

# Como rodar o projeto

Instalar o PostgreSQL 18 x64 na porta 5433, caso queira utilizar outra porta faça a alteração da porta no arquivo Model.DbStart.pas

Rodar o arquivo exe contido na pasta \Hortisys\Win32\Debug

# Estrutura de Pastas

Hortisys\src\Controller: Mediação entre a lógica e a interface

Hortisys\src\DataModule: Container de fotos

Hortisys\src\Factory: Criador de instâncias

Hortisys\src\Model: Entidades

Hortisys\src\Repository: Classes que lidam com armazenamento

Hortisys\src\Service: Executor de Operações, lógica e regras de negócio

Hortisys\src\View: Telas

