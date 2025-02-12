# Projeto de Serviço Web com Odoo em Python utilizando Docker para desenvolver um addon referente a vitrine virtual

## Descrição do Projeto
Este projeto tem como objetivo criar um serviço web que utilize o Odoo, uma plataforma de ERP (Enterprise Resource Planning) open-source, e Docker, uma ferramenta de contêineres, para desenvolver um addon referente a uma vitrine virtual. O addon será focado em ajudar os clientes de e-commerce a avaliarem se um produto de roupa (loja virtual) ficará bem com eles baseando-se no processamento de imagens do produto e da pessoa cliente que foi cadastrada no perfil do mesmo.

## Funcionalidades
1. **Cadastro e Gerenciamento de Usuários:** O sistema permitirá o cadastro e gerenciamento de usuários, incluindo a coleta de informações básicas para personalização da experiência do cliente.
2. **Integração com Processamento de Imagens:** A aplicação terá uma função que permitirá o upload e processamento de imagens do produto e da pessoa cliente. Com base nessas imagens, será possível analisar se o produto se adequará ao corpo do cliente.
3. **Avaliação Visual:** O sistema permitirá que os clientes avaliem visualmente a compatibilidade entre o produto e seu corpo, fornecendo uma experiência personalizada e informativa.
4. **Dashboard de Análise:** Um dashboard será disponibilizado para analisar as imagens processadas e obter insights sobre a compatibilidade do produto com diferentes tipos de corpos.

## Tecnologias Utilizadas
- **Odoo:** Plataforma ERP open-source utilizada como base para o desenvolvimento da vitrine virtual.
- **Python:** Linguagem de programação principal para a lógica de negócios e integração com Odoo.
- **Docker:** Ferramenta de contêineres para garantir um ambiente de desenvolvimento consistente e isolado.
- **Frontend:** Utilização de tecnologias web modernas (HTML, CSS, JavaScript) para a interface do usuário.
- **Processamento de Imagens:** Aplicação de técnicas de processamento de imagens para análise e comparação.

## Como Executar o Projeto
1. **Instalação das Dependências:** Certifique-se de ter Docker instalado no seu sistema. Clone este repositório e execute `docker-compose up --build` para instalar as dependências e iniciar o contêiner Odoo.
2. **Configuração do Banco de Dados:** Após a inicialização, acesse `http://localhost:8069` no seu navegador para configurar o banco de dados.
3. **Desenvolvimento e Testes:** Utilize as funcionalidades disponíveis no Odoo para desenvolver e testar o addon da vitrine virtual.

## Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests para melhorar este projeto.

## Licença
Este projeto é licenciado sob a [Licença MIT](https://opensource.org/licenses/MIT). Consulte o arquivo `LICENSE` para mais detalhes.
