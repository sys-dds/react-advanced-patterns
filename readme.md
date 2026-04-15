
# Setting the server...
cd server/
```
rm -f database.db
rm -rf drizzle
pnpm drizzle:generate
pnpm drizzle:migrate
pnpm drizzle:seed
```

# running the server and the client, 
```
cd server/
pnpm dev

cd client/
pnpm dev
```