# Gerenciamento de Clínica Médica

Este projeto tem como objetivo gerenciar informações sobre pacientes, médicos, consultas e receitas em uma clínica médica. Ele inclui um banco de dados relacional utilizando MySQL.

## Estrutura do Banco de Dados

### Tabelas Criadas:

1. **Paciente**: Armazena informações sobre os pacientes da clínica.
2. **Medico**: Armazena dados sobre os médicos da clínica, incluindo especialidade.
3. **Consulta**: Contém informações sobre as consultas realizadas, incluindo o paciente, o médico, data e valor.
4. **Receita**: Armazena os medicamentos prescritos em cada consulta.

### Consultas SQL

O sistema permite realizar as seguintes consultas:

1. **Listar todas as consultas realizadas por um médico específico**.
2. **Exibir os medicamentos receitados para um paciente**.
3. **Mostrar o total de consultas e receita gerada por especialidade médica**.

## Instalação e Configuração

1. **Instalar MySQL**:
   - Certifique-se de que o MySQL ou MariaDB esteja instalado e configurado no seu ambiente.

2. **Criar o banco de dados**:
   Execute os comandos SQL para criar o banco de dados e as tabelas:

   ```sql
   -- Criação do banco de dados
   CREATE DATABASE IF NOT EXISTS ClinicaMedica;
   USE ClinicaMedica;
