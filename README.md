# INTEGRAÇÃO GATEWAY DE PAGAMENTO - PAYPAL - DONATION

Esse código visa simplificar o processo de doações para usuários interessados em causas sociais e beneficiar organizações que dependem de doações para cumprir suas missões.




## VISÃO GERAL

### Propósito

O projeto visa criar uma plataforma de doações online que permita aos usuários fazer doações de forma conveniente e segura para diversas causas e organizações. A plataforma utiliza a integração com o PayPal para processar os pagamentos e oferece uma experiência de usuário simples e eficaz.

### Problema Resolvido

Muitas vezes, as pessoas desejam contribuir para causas nobres, mas podem enfrentar dificuldades ao encontrar métodos seguros e práticos para fazer suas doações. Além disso, as organizações sem fins lucrativos podem enfrentar obstáculos ao receber doações devido a barreiras de pagamento. O projeto resolve esses problemas ao fornecer uma interface amigável para doadores e uma maneira confiável para organizações capturarem fundos.

### Público-Alvo

O público-alvo do projeto inclui indivíduos que desejam apoiar causas filantrópicas, ONGs e organizações sem fins lucrativos que buscam uma solução eficiente para receber doações. A plataforma é projetada para ser acessível para pessoas com diferentes níveis de habilidades tecnológicas, tornando o processo de doação fácil e acessível para todos.


## CAPTURAS DE TELA

![gateway de pagamento](https://github.com/ph-nunan/GatewayDePagamento-Paypal/assets/117214802/ecd83d5f-5bb5-43cd-a44e-c17d9808649c)




## FUNCIONALIDADES PRINCIPAIS

### Seleção de Causas: 
Os usuários podem escolher entre uma variedade de causas e organizações sem fins lucrativos para as quais desejam fazer doações.

### Integração com o PayPal: 
A plataforma se integra com o PayPal para processar os pagamentos de forma segura e confiável.

### Botões de Pagamento do PayPal:
Botões de pagamento do PayPal são exibidos, permitindo que os usuários escolham os valores de doação e iniciem o processo de pagamento.

### Personalização de Valores:
Os doadores podem personalizar os valores de suas doações, permitindo flexibilidade nas contribuições.

### Interface Amigável: 
A plataforma é projetada com uma interface intuitiva e fácil de usar, tornando o processo de doação simples para pessoas com diferentes níveis de habilidades tecnológicas.

### Feedback de Sucesso:
Após a conclusão da doação, os doadores recebem feedback imediato sobre o sucesso da transação.

### Notificações para Organizações: 
As organizações recebem notificações instantâneas sobre doações recebidas, permitindo um acompanhamento eficiente.

### Suporte a Diferentes Moedas: 
A integração com o PayPal permite o processamento de doações em várias moedas, aumentando a acessibilidade global.

### Relatórios de Doações:
As organizações podem acessar relatórios detalhados sobre as doações recebidas, auxiliando na contabilidade e prestação de contas.

### Feedback de Doadores:
Os doadores podem fornecer feedback sobre a experiência de doação, contribuindo para melhorias contínuas na plataforma.

### Responsividade:
A plataforma é responsiva, oferecendo uma experiência de usuário consistente em dispositivos móveis e desktops.

### Segurança de Dados: 
Medidas de segurança são implementadas para proteger as informações pessoais e financeiras dos doadores.

- Essas funcionalidades combinadas criam uma plataforma completa e confiável para facilitar doações online, tornando mais fácil para os usuários contribuírem para causas significativas e para as organizações capturarem recursos de maneira eficaz.





## TECNOLOGIAS UTILIZADAS

- Python

###  Bibliotecas e Frameworks:

- #### Django
  
  Usada para trabalhar nas requisições backend;






## PRÉ-REQUISITOS


### Python: 
Certifique-se de ter Python instalado na versão correta (como Python 3.x).

### Django: 
Instale o Django usando o gerenciador de pacotes Python, por exemplo: pip install django.

### Django Rest Framework: 
Se você estiver construindo APIs RESTful, instale o DRF: pip install djangorestframework.

### PayPal SDK: 
Instale o SDK do PayPal para integração de pagamento: pip install paypalrestsdk.

## Configurações:

### Configurações de Banco de Dados:
Configure o banco de dados no arquivo settings.py do seu projeto Django, escolhendo entre PostgreSQL, MySQL ou SQLite, de acordo com suas necessidades.

### Configurações de Integração do PayPal: 
Configure as credenciais do PayPal no arquivo settings.py para autenticar as chamadas à API do PayPal.

### Configurações de URLs: 
Configure as URLs do seu aplicativo, incluindo rotas para as visualizações relacionadas a doações e organizações.




## AUTOR

Paulo Nunan



## LICENÇA

MIT




## AGRADECIMENTOS

Conhecimento adquirido através dos cursos: Alura, CodeAcademy,youtube + faculdade de Eng. de Software.
