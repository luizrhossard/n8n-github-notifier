# 🚀 n8n GitHub Push Notifier

Automação que monitora pushes no repo e notifica via WhatsApp/Telegram.

## Demo
![Execução](https://syspixel.cloud/wp-content/uploads/2026/04/n8n.png)

## 📰 Workflow: Download de Notícias para Meu Site

Este repositório contém um workflow do n8n responsável por fazer o **download automático de notícias** a partir de fontes externas e deixá-las prontas para publicação no meu site. A ideia é transformar um processo manual e repetitivo em uma automação confiável, fácil de manter e versionada no GitHub.

### O que este workflow faz

- Consulta fontes de notícias (API, RSS ou páginas HTML configuradas no n8n)
- Faz o tratamento dos dados (título, resumo, link, data, imagem, etc.)  
- Normaliza o conteúdo no formato que o meu site espera (JSON ou outro formato estruturado)  
- Opcionalmente registra logs/erros para facilitar o debug e a evolução da automação 

### Objetivo do projeto

- Manter meu site sempre atualizado com notícias recentes, sem precisar copiar e colar conteúdo na mão  
- Versionar o workflow no GitHub para ter histórico de mudanças, backup e possibilidade de evolução em equipe no futuro 

### Como usar

1. Importe o arquivo `.json` deste repositório no seu n8n (função de import de workflow) 
2. Configure as credenciais necessárias (APIs de notícias, banco de dados, webhook ou integração com o seu CMS)   
3. Ajuste os nodes de acordo com a estrutura do seu site  
4. Ative o workflow e defina a frequência de execução (cron ou outro gatilho) 

---

Esse workflow faz parte dos meus estudos e projetos de automação com n8n, focados em integrar **conteúdo dinâmico** com aplicações web que eu desenvolvo.
