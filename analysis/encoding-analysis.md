# Analisis Encoding - UTS Communication Protocol

## Case yang Dipilih
Case 3 - Order/Transaction API

## Format Data
API ini menggunakan format JSON (JavaScript Object Notation).

## Analisis GET Orders
- Endpoint: GET /api/orders
- Status Code: 200 OK
- Format response: JSON array berisi list order
- Field penting: id, orderId, customer, amount, status, items, channel, createdAt
- Content-Type: application/json

## Analisis GET Transactions
- Endpoint: GET /api/transactions
- Status Code: 200 OK
- Format response: JSON array berisi list transaksi
- Field penting: id, transactionId, orderId, method, amount, status, paidAt, channel
- Content-Type: application/json

## Analisis POST Create Order
- Endpoint: POST /api/orders
- Status Code: 201 Created
- Request body: JSON object dengan field orderId, customer, amount, status
- Response: JSON object data order yang baru dibuat

## Analisis POST Create Transaction
- Endpoint: POST /api/transactions
- Status Code: 201 Created
- Request body: JSON object dengan field transactionId, orderId, method, amount, status
- Response: JSON object data transaksi yang baru dibuat

## Kesimpulan
JSON dipilih karena ringan, mudah dibaca, dan kompatibel dengan REST API.
