# batteryd
Monitor the system battery.

# Installation
```
sudo cp batteryd /usr/local/bin/
sudo chmod +x /usr/local/bin/batteryd
sudo cp batteryd.service /etc/systemd/system/
sudo systemctl enable batteryd.service
sudo systemctl start  batteryd.service
sudo systemctl status batteryd.service
```
