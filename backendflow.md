backend
│
├── src
│   │
│   ├── config
│   │   ├── env.ts
│   │   ├── database.ts
│   │   └── logger.ts
│   │
│   ├── modules
│   │   │
│   │   ├── auth
│   │   │   ├── auth.controller.ts
│   │   │   ├── auth.service.ts
│   │   │   ├── auth.repository.ts
│   │   │   ├── auth.routes.ts
│   │   │   ├── auth.types.ts
│   │   │   └── auth.validation.ts
│   │   │
│   │   ├── user
│   │   │   ├── user.controller.ts
│   │   │   ├── user.service.ts
│   │   │   ├── user.repository.ts
│   │   │   ├── user.routes.ts
│   │   │   └── user.types.ts
│   │   │
│   │   ├── email
│   │   │   ├── email.service.ts
│   │   │   ├── email.worker.ts
│   │   │   └── email.templates.ts
│   │   │
│   │   └── twofa
│   │       ├── twofa.service.ts
│   │       ├── twofa.controller.ts
│   │       └── twofa.routes.ts
│   │
│   ├── middleware
│   │   ├── auth.middleware.ts
│   │   ├── error.middleware.ts
│   │   ├── rateLimit.middleware.ts
│   │   └── validation.middleware.ts
│   │
│   ├── routes
│   │   └── index.ts
│   │
│   ├── utils
│   │   ├── jwt.ts
│   │   ├── password.ts
│   │   ├── response.ts
│   │   └── token.ts
│   │
│   ├── workers
│   │   ├── email.worker.ts
│   │   └── sqs.worker.ts
│   │
│   ├── types
│   │   ├── express.d.ts
│   │   └── global.types.ts
│   │
│   ├── app.ts
│   └── server.ts
│
├── tests
│
├── tsconfig.json
├── package.json
└── .env.example