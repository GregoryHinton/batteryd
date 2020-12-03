# batteryd
Monitor the system battery.

# Installation
```bash
sudo cp batteryd /usr/local/bin/
sudo chmod +x /usr/local/bin/batteryd

# system-wide install
sudo cp batteryd.service /etc/systemd/system/
sudo systemctl enable batteryd.service
sudo systemctl start  batteryd.service
sudo systemctl status batteryd.service

# per-user install
mkdir -p ~/.config/systemd/user
cp batteryd.service ~/.config/systemd/user/
systemctl --user enable batteryd.service
systemctl --user start  batteryd.service
systemctl --user status batteryd.service
```
