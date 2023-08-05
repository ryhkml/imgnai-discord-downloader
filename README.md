## imgnAI Discord image downloader

Format filename:

```bash
image1.png
image2.png
image3.png
# and so on...
```

### Download script

```bash
cd /usr/local/bin
curl -s -o imgnai-download https://raw.githubusercontent.com/ryhkml/imgnai-discord-downloader/main/imgnai-download
sudo chmod +x imgnai-download
```

### Run script

```bash
# Go to your download directory
imgnai-download https://cdn.discordapp.com/attachments/1136711282813313084/1137265331296018563/image.png
```