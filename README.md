### hey, I'm Shashank

Backend engineer, about 8 months in. Most of what I've learned so far has come from breaking things in production and slowly figuring out *why* — not from tutorials or design docs read in a vacuum.

I work mainly on event-driven backends, which sounds clean on paper and is messy in practice. A lot of what I now believe about software comes from that mess.

---

**stuff I've actually learned the hard way**

- *"At-least-once" delivery is a promise, not a feature.* Idempotency is the part you actually have to design. The queue is the easy part.
- A 3-second latency wasn't a "performance problem" — it was a polling architecture. Real wins usually come from changing the shape of the system, not tuning the slow piece.
- Race conditions don't show up in dev. They show up the first weekend after launch, in the one flow you didn't think to retry-test.
- "Eventual consistency" is fine until someone in support asks why the UI shows one thing and the third-party API shows another. Now it's your problem.
- Reading the docs of a thing I'm already using (Redis Streams, Postgres indexes, Express middleware) usually teaches me more than reading about a new thing.

**stuff I'm currently chewing on**

- how to design systems so failures are observable instead of silent
- what RAG actually is once you strip away the marketing — building a small AI backend (FastAPI + pgvector) to find out
- when caching is a real solution vs when it's a way to delay a database problem
- DSA, mostly because pattern-recognition is a separate muscle from system design and I don't want it to atrophy

**stack I reach for**
Python · Java · Node.js · Django · Express · Postgres · Redis · MongoDB · Docker · AWS · GCP

---

I try to build small things end-to-end instead of copying tutorial projects. I'd rather understand 5 lines than ship 500 I can't defend.

[LinkedIn](https://www.linkedin.com/in/shashank-joshi-3664b2226/) · [LeetCode](https://leetcode.com/Shashank_1203) · joshishashank2003@gmail.com
