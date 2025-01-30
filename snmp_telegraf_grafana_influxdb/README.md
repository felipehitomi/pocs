# Build do container SNMP
docker-compose build

# Subir todos os containers
docker-compose up -d



# Configurar o Grafana

1. Acesse http://localhost:3000 e faça login (admin/admin).
2. Adicione o InfluxDB como Data Source:
3. URL: http://influxdb:8086
4. Database: telegraf
5. Username: admin
6. Password: admin123
7. Crie um Dashboard e adicione gráficos com os dados SNMP.