# ASK-THIS-WEBSITE
<h3>A chatbot to chat with any website made with RAGChat & NextJS.</h3>

![Askthiswebsite](https://github.com/user-attachments/assets/04a6ce23-95a2-48e0-9b50-4ae09f06c136)

### Run this app locally

```shell
npm run dev
```

### How to use

```bash
Append http://localhost:3000/ to the beginning of the url of any website.
```

### Setup .env file

```bash
UPSTASH_VECTOR_REST_URL=your_upstash_vector_url
UPSTASH_VECTOR_REST_TOKEN=your_upstash_vector_token

QSTASH_TOKEN=your_qstash_token

UPSTASH_REDIS_REST_URL=your_upstash_redis_url
UPSTASH_REDIS_REST_TOKEN=your_upstash_redis_token
```

### Installation guide

```bash
git clone https://github.com/MaheshR03/askthiswebsite

cd askthiswebsite

bunx create-next-app@latest askthiswebsite

bun add @upstash/rag-chat

bun install @upstash/redis

bun install ai

bun i tailwind-merge clsx

bun i lucide-react

npx shadcn@latest init

bun i @nextui-org/react

npm run dev
```
