# NetologyMonitoringGrafana
1:
<img width="1489" height="500" alt="image" src="https://github.com/user-attachments/assets/4de9e42e-de87-41f1-943f-ecb36a36802d" />
<img width="2536" height="1305" alt="image" src="https://github.com/user-attachments/assets/a1922665-a0d5-42a6-a36e-e45d0ca79965" />

2:
<img width="2536" height="1305" alt="image" src="https://github.com/user-attachments/assets/5997c635-be6a-4576-bbd4-2a64662d2479" />
1) 100 - (avg by (instance) (rate(node_cpu_seconds_total{mode="idle"}[5m])) * 100)
2) node_load1
node_load5
node_load15
3) node_memory_MemAvailable_bytes
4) node_filesystem_avail_bytes{mountpoint="/"}

