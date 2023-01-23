# Type Chat

A typed, real-time chat application built with TypeScript and React.

## Installation

- Clone this repository

```bash
git clone https://github.com/tnowad/type-chat.git
```

- Install the dependencies for both client and server

```bash
npm install
```

- Start the client and server

```bash
npm start
```

The application will be running on <http://localhost:3000>

## Features

- Real-time chat functionality using Socket.io
- TypeScript for static type checking
- React for building user interface
- Tailwind CSS for styling
- Express.js for server-side routing

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Folder Struct

```bash
TypeChat/
├── client/
│   ├── public/
│   │   ├── index.html
│   │   ├── favicon.ico
│   │   ├── images/
│   │   │   ├── ...
│   │   └── ...
│   ├── src/
│   │   ├── App.tsx
│   │   ├── index.tsx
│   │   ├── components/
│   │   │   ├── Chat.tsx
│   │   │   ├── Message.tsx
│   │   │   └── ...
│   │   ├── Pages/
│   │   │   ├── Login/
│   │   │   │   ├── Login.tsx
│   │   │   │   └── ...
│   │   │   ├── Register/
│   │   │   │   ├── Register.tsx
│   │   │   │   └── ...
│   │   ├── routes/
│   │   │   ├── login.route.tsx
│   │   │   ├── register.route.tsx
│   │   │   └── ...
│   │   ├── services/
│   │   │   ├── socket.ts
│   │   │   └── ...
│   │   ├── styles/
│   │   │   ├── tailwind.css
│   │   │   └── ...
│   │   └── ...
│   ├── package.json
│   ├── tsconfig.json
│   ├── webpack.config.js
│   └── ...
├── server/
│   ├── src/
│   │   ├── controllers/
│   │   │   ├── auth.controller.ts
│   │   │   ├── message.controller.ts
│   │   │   └── ...
│   │   ├── models/
│   │   │   ├── auth.model.ts
│   │   │   ├── message.model.ts
│   │   │   └── ...
│   │   ├── routes/
│   │   │   ├── auth.route.ts
│   │   │   ├── message.route.ts
│   │   │   └── ...
│   │   ├── services/
│   │   │   ├── auth.service.ts
│   │   │   ├── message.service.ts
│   │   │   └── ...
│   │   ├── index.ts
│   │   └── ...
│   ├── package.json
│   ├── tsconfig.json
│   ├── jest.config.js
│   ├── .env
│   └── ...
├── package.json
├── README.md
├── .gitignore
└── ...
```
