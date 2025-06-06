
# 💾 Criando uma Instância de Banco de Dados SQL no Azure: Minha Experiência

Durante a realização do **Lab 02** no curso *Microsoft 50 Anos - Computação em Nuvem com Azure*, explorei o processo de criação de uma Instância de Banco de Dados SQL no portal do Azure. O passo a passo é simples, mas cheio de oportunidades de aprendizado sobre configuração, segurança e estruturação de serviços em nuvem.

---

## 📦 Etapa 1 – Criando o Grupo de Recursos

Antes de tudo, é essencial criar um grupo de recursos para manter os serviços organizados e facilitar a gestão no Azure.

![Criar grupo de recursos](assets/01-ms50-lab02--criacao-do-grupo-de-recursos.png)

---

## 🖥️ Etapa 2 – Criando o Servidor SQL

Criei um servidor para hospedar as instâncias de banco de dados. Esse servidor vai centralizar a autenticação e facilitar futuras conexões com outros bancos.

![Criar servidor SQL](assets/02-ms50-lab02-criacao-servidor-do-banco-de-dados-sql.png)

---

## 🗃️ Etapa 3 – Criando o Banco de Dados SQL

Configurei o nome do banco de dados, vinculei ao servidor que criei na etapa anterior e escolhi o nível de desempenho apropriado para o laboratório.

![Criar Instância de Banco de Dados SQL](assets/03-ms50-lab02-criacao-bancode-dados-sql.png)

---

## 🌐 Etapa 4 – Configurando a Rede de Acesso

Aqui defini as opções de conectividade – para que seja acessível publicamente ou com regras específicas de firewall.

![Configurar rede de acesso](assets/04-ms50-lab02-criacao-da-rede-banco-de-dados-sql.png)

---

## 🔍 Etapa 5 – Revisando as Configurações

Antes de confirmar a criação, revisei cuidadosamente as configurações. Essa etapa é importante para evitar custos indesejados ou falhas na conectividade.

![Revisão da criação](assets/05-ms50-lab02-revisao-criacao-bancode-dados-sql.png)

---

## ⚙️ Etapa 6 – Acompanhando o Provisionamento

Com tudo revisado, cliquei em "Criar" e acompanhei o provisionamento da Instância via portal. Em poucos minutos, tudo estava pronto.

![Andamento da criação](assets/06-ms50-lab02-andamento-da-criacao-bancode-dados-sql.png)

---

## ✅ Etapa 7 – Instância de Banco de Dados Pronta

A criação foi concluída com sucesso, e a instância ficou disponível para uso imediato, com as informações de conexão e painel de controle disponíveis no portal.

![Criação finalizada](assets/06-ms50-lab02-finalizado-criacao-banco-de-dados-sql.png)

---

## 📝 Conclusão

Esse laboratório foi uma introdução sólida ao mundo dos **bancos de dados como serviço (DBaaS)** no Azure. Além de entender a estrutura de um servidor SQL gerenciado, foi possível explorar boas práticas de organização (grupos de recursos), segurança (acesso de rede) e performance (nível de serviço).

Próximos passos? Automatizar esse processo com **Azure CLI** ou **Bicep**, e conectar esse banco a um aplicativo hospedado no **App Service** – algo que pretendo experimentar em breve.
