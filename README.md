# Install nextjs
Automatic Installation
```bash
npx create-next-app@latest
```

# prisma
## setting
```bash
npm i prisma @prisma/client
npx prisma init
```
## Creating the database schema - 초기화
```bash
npx prisma migrate dev
npx prisma migrate dev --name init
npx prisma migrate deploy
```
## Run prisma studio (DB GUI tool)
```bash
npx prisma studio
```

## DB 데이터 유지, schema 수정사항 적용
```bash
npx prisma db push
```

## DB model option setting 
```bash 
npx prisma  migrate dev --create-only
npx prisma  migrate dev
```

# Apollo server
## setting
```bash
npm install @apollo/server graphql
npm install @apollo/client
npm install apollo-upload-client
```

# Date utility library
```bash 
npm i date-fns
```