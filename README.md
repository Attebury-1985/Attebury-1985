import { Ai } from '@cloudflare/ai';

const ai = new Ai(env.AI)

const output = await ai.run('@cf/meta/llama-2-7b-chat-int8', {
  prompt: 'Tell me about Workers AI'
})
