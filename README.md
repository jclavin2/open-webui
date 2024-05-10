UI - README


# Medical Data Polygraph
## For evaluation and payment of Electronic Data Interchange  (EDI) 837 data
User-friendly claims decision support system. EDI 837 expert and learns your business process flows over time. 


## Build and Install 🛠️

```
git clone https://github.com/open-webui/open-webui.git
cd open-webui/

# Copying required .env file
cp -RPp .env.example .env

# Building Frontend Using Node
npm i
npm run build

# Serving Frontend with the Backend
cd ./backend
pip install -r requirements.txt -U
cd ..
npm install electron --save-dev
npm start
```

## License 📜

This project is licensed under the [MIT License](LICENSE) - see the [LICENSE](LICENSE) file for details. 📄

### Acknowledgments 
Built from Open WebUI.
