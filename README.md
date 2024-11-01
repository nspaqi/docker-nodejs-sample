# Docker Node.js Sample
Eine einfache Node.js-Anwendung, die in einem Docker-Container läuft.
## Installation
1. **Repository klonen:**
   ```bash
   git clone https://github.com/username/docker-nodejs-sample.git
   cd docker-nodejs-sample
   ```
2. **Notwendige Pakete installieren:**
   ```bash
   npm install
   ```
3. **Docker-Image erstellen:**
   ```bash
   docker build -t docker-nodejs-sample .
   ```
4. **Container starten:**
   ```bash
   docker run -p 3000:3000 docker-nodejs-sample
   ```
Jetzt ist die Anwendung unter `http://localhost:3000` erreichbar.
## Nutzung von Git
Um Änderungen zu speichern:
```bash
git add .
git commit -m "Änderungskommentar"
git push origin main
```