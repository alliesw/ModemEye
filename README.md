# ModemEye
A Python-Based DOCSIS Modem Metrics Collector 

Description: A Python-based automation tool designed to collect performance metrics from DOCSIS cable modems (Hitron), by scraping data from their built-in HTML web portals. This data is parsed to extract key information such as channel metrics and event logs, stores the data in InfluxDB 2.0 for time-series tracking, and logs events in Grafana Loki. I utilized a Grafana dashboard to provide real-time visualization of modem performance (via InfluxDB metrics) and log events (via Loki), and configuration of custom alerts for monitoring signal quality, connectivity, and potential issues like SNR drops or modem reboots. 

REQS:
- A DOCSIS supported cable Modem   
- Grafana
- Loki
- InfluxDB 2.0
- Python3

Installation: 
> pip3 install -e 
 

