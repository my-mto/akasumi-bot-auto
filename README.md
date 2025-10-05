# akasumi-bot-auto
https://discord.com/api/webhooks/1424263481187893286/uguwTG_Eg0VM9z1HY7SM5zmp1xJVwwkfjjhWZvF-BLU5sgFWAzp35eF1b5nkXwMILAli
import requests
import time

WEBHOOK_URL = "https://discord.com/api/webhooks/1424263481187893286/uguwTG_Eg0VM9z1HY7SM5zmp1xJVwwkfjjhWZvF-BLU5sgFWAzp35eF1b5nkXwMILAli"

def send_message():
    data = {"content": "/trade graph"}  
    requests.post(WEBHOOK_URL, json=data)

if __name__ == "__main__":
    send_message()
