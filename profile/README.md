# ShiftGraph

Early warning for the third-party APIs, SDKs, and tools your software depends
on. ShiftGraph profiles how your dependencies actually behave, detects
sustained contract drift with structural evidence, and warns you before a
silent change reaches production.

A field flips from integer to string. A property your parser reads disappears.
A response picks up an envelope. The API still returns 200, the provider's
status page stays green, and your integration breaks anyway. Nothing in a
normal monitoring stack watches for that, because it is not an availability
problem.

- **The product:** [app.shiftgraph.dev](https://app.shiftgraph.dev)
- **The Observatory:** a public daily structural record of 60+ API surfaces,
  including every confirmed contract drift and the false flags we withdrew
  when the engine was wrong. [shiftgraph.dev/observatory](https://shiftgraph.dev/observatory)
- **Learn:** what API drift is, how to detect it, and what you can build
  yourself for free. [shiftgraph.dev/learn](https://shiftgraph.dev/learn)
- **The recorder:** [`@shiftgraph/node`](https://www.npmjs.com/package/@shiftgraph/node)
  is open and MIT-licensed. It reduces responses to structure inside your own
  process, so field names, types, and shape are all that ever leave it. The
  code that touches your traffic is code you can read.

Questions: hello@shiftgraph.dev
