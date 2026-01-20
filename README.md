# markdown-chess
chess server based on gRPC microservices

Built with NestJS + Vue.js, leveraging NATS JetStream, PostgreSQL and Redis.

Included features:

🎮 Multiple game modes and ranked/unranked matches
🤖 Play against AI (Stockfish)
⏳ Matchmaking server
💪 Fault-tolerant, persistent queues
💬 Chat and live matchmaking queues status
Tech stack:

💻 Typescript + NestJS microservices (monorepo)
🖌️ Vue.js + Pinia
📔 NATS JetStream, PostgreSQL (kysely), Redis
🗣️ gRPC, WebSocket (Socket.IO), HTTP
🐳 docker compose
