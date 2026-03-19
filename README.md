# Event Loop Deep Dive (Node.js & Browser)

This demo provides a clear, structured overview of how the Event Loop works in both browser environments and Node.js. It visualizes the full execution model, including call stack behavior, task queues (macro/microtasks), and the distinct phases of the Node.js Event Loop.

The project highlights key differences between platforms, such as microtask prioritization, timers, I/O callbacks, and the role of APIs like setTimeout, Promise, and process.nextTick. Each phase is broken down to help understand execution order and timing nuances that often lead to unexpected behavior in asynchronous code.

Designed as a practical reference, this page is useful for developers who want a deeper understanding of JavaScript concurrency beyond high-level explanations.

---
This demo was created in Claude Code as part of a deep dive into the Event Loop while working with a mentee, exploring its mechanics in a practical, hands-on way.
