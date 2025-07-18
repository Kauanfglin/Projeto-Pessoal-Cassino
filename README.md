
Um site completo para análise da Blaze Double com previsões de sinais usando Inteligência Artificial 


### Pré-requisitos
- Node.js 20+
- Python 3.11+
- pnpm ou npm

### Instalação
```bash
# Instalar dependências do frontend
cd blaze-analyzer
pnpm install

# Instalar dependências do backend (IA)
pip3 install flask flask-cors numpy
```

### Execução
```bash
# Terminal 1: Iniciar API da IA
cd src
python3 api_server.py

# Terminal 2: Iniciar frontend
pnpm run dev --host
```

### Acessar
- Frontend: http://localhost:5173
- API: http://localhost:5000



