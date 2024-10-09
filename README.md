# Setup Kafka with Monitoring

## Clone Repositories

- Clone the Prometheus Kafka monitoring stack repository:

```
git clone https://github.com/ops-dshiv/jmx-monitoring-stacks.git
```

- Clone the cp-demo project in the same directory:

```
git clone https://github.com/confluentinc/cp-demo.git
```
## Start Monitoring Stack

- Navigate to the directory and execute the start.sh script:

```
cd jmx-monitoring-stacks/jmxexporter-prometheus-grafana
./start.sh
```

## Access Grafana Dashboard
Open http://localhost:3000 in your browser to visualize the Grafana dashboard. Use the following credentials:

```
Username: admin
Password: password
```
Credentials can be found in the file:

```
/jmx-monitoring-stacks/jmxexporter-prometheus-grafana/docker-compose.override
```

![alt text](</assets/Screenshot 2024-10-09 at 1.18.14 PM.png>)

## Grafana Dashboard Navigation

Navigate through the Grafana dashboard:

![alt text](</assets/Screenshot 2024-10-09 at 12.18.39 PM.png>) 

![alt text](</assets/Screenshot 2024-10-09 at 12.19.36 PM.png>) 

![alt text](</assets/Screenshot 2024-10-09 at 12.21.17 PM.png>) 

![alt text](</assets/Screenshot 2024-10-09 at 12.22.50 PM.png>) 

![alt text](</assets/Screenshot 2024-10-09 at 12.23.51 PM.png>) 

![alt text](</assets/Screenshot 2024-10-09 at 12.24.22 PM.png>) 

![alt text](</assets/Screenshot 2024-10-09 at 12.25.00 PM.png>) 

![alt text](</assets/Screenshot 2024-10-09 at 12.25.50 PM.png>) 

![alt text](</assets/Screenshot 2024-10-09 at 12.26.52 PM.png>) 
