# STOQORA Backend

Express + MongoDB REST API powering the STOQORA trading platform —
handles authentication (JWT), portfolio holdings, positions, and
order execution (BUY/SELL).

## Live API
https://stoqora-backend.onrender.com

## Tech Stack
Node.js, Express, MongoDB Atlas, JWT

## Endpoints
- POST /auth/signup, /auth/login
- GET /allHoldings, /allPositions, /allOrders
- POST /newOrder (BUY/SELL, updates holdings with weighted-average pricing)

## Related Repos
- Dashboard (trading UI): [stoqora-dashboard](link)
- Fronted (marketing site): [stoqora-fronted](link)
