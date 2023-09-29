# Relatório de Atividade - Configuração de Aplicação na AWS

## Descrição da Atividade

Configuração uma aplicação na AWS que inclui um servidor de aplicação EC2 e um banco de dados RDS.

### Serviços e Recursos Utilizados

- **Amazon EC2**: 2 instâncias EC2 como servidor de aplicação e frontend para o cliente.

- **Amazon RDS**: banco de dados PostgreSql no Amazon RDS para armazenar dados da aplicação.

- **Amazon Security Groups**: Precisei criar grupos de segurança para controlar o tráfego de entrada e saída para as instâncias EC2 e RDS.

### Configurações de Segurança

- Configurei grupos de segurança para liberar o tráfego de rede para instâncias EC2 e RDS destinada a aplicação necessária.
### Etapas Realizadas

1. **Configuração do Amazon RDS**:
   - Foi criado um banco de dados PostgreSQL no RDS.
   - Coletei as informações de conexão, incluindo o endpoint, nome de usuário e senha, para em seguida testar no DBeaver.

2. **Configuração do Amazon EC2**:
    - Configurei uma instância EC2 com uma imagem de sistema operacional Amazon Linux para o backend com FastApi.
    - Configurei uma instância EC2 com uma imagem de sistema operacional Amazon Linux para o front para ser acessado por meio de um servidor apache.

3. **Configuração da Aplicação**:
   - Acessei por meio do proprio terminal da aws.
   - Foi instalado e configurado o docker para receber a imagem do back e apache para o front.
   - Incrementei os arquivo do back e front conforme no repositorio para aceitar as novas configuracões de conexão.

### Desafios Enfrentados

- Não consegui fazer funcionar.


## Capturas de Tela

Anexei algumas capturas de tela relevantes para demonstrar a configuração das instâncias EC2, RDS nos anexos do forms.
