# Arquitetura da Solução Preditiva

## Visão Geral do Fluxo de Dados
1. **Coleta (Sensores IoT):** Hidrômetros inteligentes medem continuamente vazão e pressão em tempo real nas redes de distribuição.
2. **Processamento em Nuvem:** Os dados são enviados para o back-end em nuvem, onde o algoritmo de Machine Learning analisa séries temporais em busca de desvios.
3. **Apresentação e Camada de Dados:**
   - **Front-end / MVP:** Desenvolvido em HTML, CSS e JavaScript para o painel operacional e app mobile do cliente.
   - **Back-end & API:** Estrutura Serverless baseada em **Supabase**.
   - **Banco de Dados:** **PostgreSQL** hospedado no Supabase para armazenamento estruturado das informações.
