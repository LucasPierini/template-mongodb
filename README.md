# Template MongoDB
Projeto dedicado a servir de base para criação de containers do docker-compose
para mongodb, com ou sem replicaset.

## Criando um novo projeto

---

1. Clone este projeto;
2. Remova o arquivo `.git` que vier na raíz do projeto;
3. Remova ou sobrescreva os arquivos `README.md` e `CHANGELOG.md`;
4. Copie o arquivo `.env.template` para `.env`, preenchendo as variáveis de ambiente;
5. Escolha um dos arquivos de `docker-compose.yml.XXX.template` com o serviço
   do mongodb de sua escolha, renomeando-o para `docker-compose.yml`, excluindo
   os demais;
