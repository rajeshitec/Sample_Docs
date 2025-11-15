# Data model

## Client entity

- `id` (string, primary key)
- `name` (string)
- `status` (enum: ACTIVE, INACTIVE, PENDING)
- `risk_rating` (enum: LOW, MEDIUM, HIGH)
- `created_at`, `updated_at` (timestamps)

## Trade entity

- `id` (string, primary key)
- `client_id` (FK → Client)
- `product_code`
- `notional`
- `currency`
- `trade_date`

