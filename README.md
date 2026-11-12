<table>
  <tr>
    <td><b>Full Stack Developer.</b> Building and shipping AI-native products.</td>
    <td><a href="https://furqan7.dev/">Portfolio</a> · <a href="https://www.linkedin.com/in/furqan-132378327/">LinkedIn</a> · <a href="https://x.com/B_Furqan07">X</a> · <a href="https://leetcode.com/u/FURQAN_07_/">LeetCode</a></td>
  </tr>
</table>

I build **RAG pipelines, real-time voice AI systems and full-stack products** with TypeScript, Node.js, PostgreSQL and AWS.

### Projects

- [**Brainly AI**](https://github.com/Furqan-7/Brainly-AI) · AI-powered second brain for reels, videos, tweets, articles, PDFs and notes · [Live](https://brainlyai.me/)
    - Multi-stage RAG pipeline: HyDE query rewriting, hybrid vector + full-text search, Reciprocal Rank Fusion, Cohere reranking and neighbor-chunk expansion · **6.7s** average response
    - Resilient retrieval with time-boxed AI calls, keyword-only fallbacks and an LRU embedding cache · saves **300–500ms** on cache hits
    - PostgreSQL job queue with `SKIP LOCKED` and exponential backoff turns **9 content types** into searchable embeddings · **46** Vitest tests
    - <sub>TypeScript · Next.js 16 · Express 5 · PostgreSQL · pgvector · Prisma · Nomic Embeddings · Groq · Cohere Rerank · Docker</sub>
- [**DevPrep**](https://github.com/Furqan-7/DevPrep) · AI mock interview platform with a real-time voice interviewer · [Live](https://dev-prep-frontend.vercel.app/)
    - Real-time voice pipeline: Silero VAD → WebSocket PCM streaming → Groq Whisper → Gemini streaming → Deepgram TTS · **4.06s** from end of speech to first AI audio
    - Sentence-level LLM streaming and pre-warmed Deepgram WebSockets start audio before the full reply is ready · about **1–2s** saved per turn
    - Adaptive interview engine over SSE · **10-question** interviews across **12 role tracks** · per-answer scoring (0–10) · real-time barge-in · WebSocket server on AWS
    - <sub>TypeScript · Next.js · Express · PostgreSQL · Prisma · WebSockets · Gemini · Groq Whisper · Deepgram Aura-2 · Silero VAD · AWS · Turborepo</sub>
- [**Crevo**](https://github.com/Furqan-7/Crevo) · AI operating system for creators: inbox, brand deals, content, calendar and analytics in one place · [Live](https://crevo-one-theta.vercel.app/)
    - **48-endpoint** REST API on a **23-model** Prisma schema · Supabase JWT auth · Zod validation · per-user AI rate limits · AES-256-GCM encrypted OAuth tokens
    - AI Copilot with **10 tools** and hybrid RAG (pgvector, full-text search, Reciprocal Rank Fusion) over emails, contracts and video transcripts · automatic Gemini → Groq fallback
    - PostgreSQL background jobs for **13 job types**: Gmail, Calendar and YouTube sync, FFmpeg vertical video rendering, batched embeddings
    - <sub>TypeScript · Next.js 16 · Express 5 · PostgreSQL · pgvector · Prisma 7 · Gemini · Groq · Supabase Auth · FFmpeg · Google APIs · Playwright</sub>

### Open Source

- [**AOSSIE · DebateAI**](https://github.com/AOSSIE-Org/DebateAI) · Contributor · **2 merged PRs** · [#593](https://github.com/AOSSIE-Org/DebateAI/pull/593) Debate Room session restore · [#663](https://github.com/AOSSIE-Org/DebateAI/pull/663) mobile nav and theme selector

### Competitive Programming

<img align="right" src="https://count.getloli.com/@Furqan-7?name=Furqan-7&theme=moebooru&padding=7&offset=0&align=top&scale=1&pixelated=1&darkmode=auto" alt="profile views" height="90">

- [**LeetCode**](https://leetcode.com/u/FURQAN_07_/) · **550+ problems solved** in C++ · Graphs, DP, trees, binary search
- **Contest rating 1,715** · Top **13.08%** globally · 23 contests
- **Rank 1,250 of 31K+** in a Biweekly Contest · Top **4%**
