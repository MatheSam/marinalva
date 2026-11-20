# Casa da Mari — demonstração

Site estático em React + Vite, em português, sem administrador, banco, login ou cobranças. Os dados da casa, valores e datas são fictícios. O contato abre uma prévia e não envia mensagens.

## Executar

Requer Node.js 20.19+ ou 22.12+.

```sh
npm install
npm run dev
```

## Publicar

```sh
npm run build
```

Publique a pasta `dist` em uma hospedagem de arquivos estáticos. Em serviços com configuração automática: framework Vite, comando `npm run build`, diretório de saída `dist`. Não há variáveis de ambiente. Não exige regras de rotas, pois a navegação usa âncoras na mesma página.

## Alterar conteúdo

O conteúdo e as perguntas ficam em `src/main.jsx`, o visual em `src/styles.css`, e as fotos locais em `public/images`. A função `status` define padrões fictícios de datas a cada mês e precisa ser substituída por uma agenda real antes de uso comercial. Não existe persistência de reservas. A consulta usa uma estimativa fixa, sem cobrança. O mapa indica apenas a região fictícia de Praia do Forte, Bahia.

O site carrega Google Fonts e o mapa externo do Google. As fotos são incluídas localmente para não depender de URLs externas durante a navegação. Veja `CREDITOS.md`.

Antes de divulgar como anúncio real, substitua todas as informações e fotos, conecte o número correto do WhatsApp e implemente a atualização da disponibilidade.
