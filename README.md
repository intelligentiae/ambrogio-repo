# ambrogio-repo
Packages for the Ambrogio project

```bash
wget https://intelligentiae.github.io/ambrogio-repo/public.key
sudo gpg --dearmor < public.key | sudo tee /etc/apt/trusted.gpg.d/ambrogio.gpg > /dev/null
```

```bash
echo "deb [signed-by=/etc/apt/trusted.gpg.d/ambrogio.gpg] https://intelligentiae.github.io/ambrogio-repo stable main" | sudo tee /etc/apt/sources.list.d/ambrogio.list
```