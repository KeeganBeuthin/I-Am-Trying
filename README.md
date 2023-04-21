

## QuickStart

```
npm install
npm start # API running at http://localhost:9000
```

```bash
curl -i http://localhost:9000/transactions
curl -i http://localhost:9000/transactions/1
```
```
push

curl -X POST -H "Content-Type: application/json" -d '{"id": number, "amount": number}' http://localhost:9000/transactions
```
