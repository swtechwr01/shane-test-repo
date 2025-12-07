# API Examples Guide

This document provides code examples for common API tasks.

## Example 1: GET Request
```python
import requests
response = requests.get('https://api.example.com/data')
print(response.json())
```

## Example 2: POST Request
```python
import requests
response = requests.post('https://api.example.com/data', json={'key': 'value'})
print(response.json())
```

## Example 3: Authentication
```python
import requests
from requests.auth import HTTPBasicAuth
response = requests.get('https://api.example.com/secure-data', auth=HTTPBasicAuth('user', 'pass'))
print(response.json())
```
