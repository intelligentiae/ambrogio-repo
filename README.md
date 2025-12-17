# ambrogio-repo
Debian packages for the [Ambrogio](https://github.com/intelligentiae/ambrogio) project. Run this on your server:

```bash
wget https://intelligentiae.github.io/ambrogio-repo/public.key
sudo gpg --dearmor < public.key | sudo tee /etc/apt/trusted.gpg.d/ambrogio.gpg > /dev/null
echo "deb [signed-by=/etc/apt/trusted.gpg.d/ambrogio.gpg] https://intelligentiae.github.io/ambrogio-repo stable main" | sudo tee /etc/apt/sources.list.d/ambrogio.list
```