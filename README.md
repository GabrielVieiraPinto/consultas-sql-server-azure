# consultas-sql-server-azure
algumas consultas para auxiliar no dia-dia para avaliar performance em sql-server-azure-database
# Troubleshooting de Desempenho no Azure SQL Server

Este repositório contém consultas SQL úteis para ajudar no troubleshooting de desempenho em um banco de dados Azure SQL Server. As consultas fornecidas aqui podem ser usadas para identificar problemas de desempenho, monitorar o desempenho do banco de dados e otimizar consultas lentas.

## Consultas Disponíveis

1. **Monitoramento de Atividade de Consulta**
   - `consulta_monitoramento.sql`: Esta consulta ajuda a monitorar as consultas em execução, identificar consultas lentas e entender o uso de recursos.

2. **Análise de Índices**
   - `consulta_analise_de_indices.sql`: Use esta consulta para identificar índices ausentes ou subutilizados que podem afetar o desempenho das consultas.

3. **Bloqueios e Deadlocks**
   - `consulta_bloqueios_deadlocks.sql`: Essa consulta auxilia na identificação de bloqueios e deadlocks no banco de dados, o que pode causar problemas de desempenho.

4. **Uso de Memória**
   - `consulta_uso_de_memoria.sql`: Monitore o uso de memória no banco de dados para garantir que ele não atinja limites críticos.

5. **Estatísticas e Plano de Execução**
   - `consulta_estatisticas_plano_execucao.sql`: Use esta consulta para visualizar as estatísticas de índice e os planos de execução das consultas, o que pode ajudar na otimização de consultas.

## Como Usar

1. Faça o clone deste repositório em seu ambiente local.

2. Abra o Azure Data Studio ou sua ferramenta SQL preferida e conecte-se ao seu banco de dados Azure SQL Server.

3. Abra e execute as consultas relevantes para o seu cenário de troubleshooting de desempenho.

4. Analise os resultados e tome medidas para otimizar o desempenho do seu banco de dados.

## Contribuições

Contribuições são bem-vindas! Se você tiver consultas SQL adicionais ou melhorias para as consultas existentes, fique à vontade para abrir um problema ou enviar uma solicitação de pull.

## Licença

Este projeto está licenciado sob a Licença MIT - consulte o arquivo [LICENSE](LICENSE) para obter detalhes.

## Agradecimentos

Agradecemos por usar este recurso. Esperamos que essas consultas sejam úteis para melhorar o desempenho do seu banco de dados Azure SQL Server.

