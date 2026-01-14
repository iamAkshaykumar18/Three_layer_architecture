# Three_layer_architecture
using Azure 
On App-VM:

sudo fuser -k 5000/tcp (to clear the port)

nohup python3 app.py > output.log 2>&1 & (to run forever)

On Web-VM:

sudo systemctl restart nginx