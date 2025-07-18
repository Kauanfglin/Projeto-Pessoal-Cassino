


### Pré-requisitos
- Node.js 20+
- Python 3.11+
- pnpm ou npm

### Instalação
```bash
# Instalar dependências do frontend
cd blaze-analyzer
pnpm install

# Instalar dependências do backend
pip3 install flask flask-cors numpy
```

### Execução
```bash
# Terminal 1: Iniciar API 
cd src
python3 api_server.py

# Terminal 2: Iniciar frontend
pnpm run dev --host
```

### Acessar
- Frontend: http://localhost:5173
- API: http://localhost:5000



