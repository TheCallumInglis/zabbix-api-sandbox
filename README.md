# Zabbix API Sandbox
By Callum Inglis

## Setup Secrets
See [Zabbix API Docs](https://www.zabbix.com/documentation/current/en/manual/api#authentication) before you continue.  

Create `creds.py` file in the secrets directory
```shell
$ touch secrets/creds.py
```

Populate with your Zabbix API details, e.g.
```python
API_URL = 'https://myzabbixurl.com/zabbix/api_jsonrpc.php'
API_USER = 'ZABBIX_API_USERNAME'
API_PASS = 'ZABBIX_API_PASSWORD'
```