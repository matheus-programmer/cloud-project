gerenciador-de-tarefas/
│
├── frontend/                        # Aplicação front-end
│   ├── public/                      # Arquivos públicos
│   │   ├── index.html               # Página principal
│   │   ├── style.css                # Estilos CSS
│   │   ├── script.js                # JavaScript principal
│   │   └── components/              # Componentes JS reutilizáveis
│   │       ├── modal.js             # Funcionalidades dos modais
│   │       └── notification.js      # Sistema de notificações
│   │
│   └── vercel.json                  # Configuração para deploy no Vercel
│
├── backend/                         # Aplicação back-end
│   ├── src/
│   │   ├── config/
│   │   │   └── parseConfig.js       # Configuração do Parse/Back4App
│   │   │
│   │   ├── models/
│   │   │   └── taskModel.js         # Modelo de dados para tarefas
│   │   │
│   │   ├── controllers/
│   │   │   └── taskController.js    # Controlador de tarefas
│   │   │
│   │   └── routes/
│   │       └── taskRoutes.js        # Rotas da API
│   │
│   ├── server.js                    # Ponto de entrada do servidor
│   └── package.json                 # Dependências do back-end
│
└── README.md                        # Documentação do projeto