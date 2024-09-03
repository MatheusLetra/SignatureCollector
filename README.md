# Coleta de Assinatura com React e TypeScript

Este projeto é uma aplicação web simples de desenho estilo Paint, para coleta de assinatura, construída com React, TypeScript e Vite. Ele oferece uma tela de desenho interativa com funcionalidades básicas de pintura.

## Funcionalidades

- Tela de desenho interativa
- Seletor de cor para o pincel
- Controle de tamanho do pincel
- Opção para salvar o desenho como PNG
- Botão para limpar a tela de desenho

## Pré-requisitos

Antes de começar, certifique-se de ter instalado em sua máquina:

- Node.js (versão 12.0.0 ou superior)
- npm (normalmente vem com Node.js)

## Instalação

1. Clone o repositório:
   ```
   git clone https://github.com/MatheusLetra/SignatureCollector.git
   cd SignatureCollector
   ```

2. Instale as dependências:
   ```
   npm install
   ```

## Executando o Projeto

Para iniciar o servidor de desenvolvimento:

```
npm run dev
```

Abra [http://localhost:5173](http://localhost:5173) no seu navegador para ver a aplicação.

## Construindo para Produção

Para criar uma versão otimizada para produção:

```
npm run build
```

Os arquivos gerados estarão na pasta `dist/`.

## Tecnologias Utilizadas

- [React](https://reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Vite](https://vitejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)

## Estrutura do Projeto

```
SignatureCollector/
│
├── src/
│   ├── App.tsx
│   ├── Collector.tsx
│   └── index.css
│
├── public/
│   └── index.html
│
├── package.json
├── tsconfig.json
├── vite.config.ts
└── README.md
```

## Contribuindo

Contribuições são sempre bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.