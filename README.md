LET OP: Krijg de volgende melding die evt moeilijkheden kan veroorzaken vanaf juli 2021:

SharedArrayBuffer usage is restricted to cross-origin isolated sites
SharedArrayBuffers (SABs) can be used to construct high-resolution timers. High-resolution timers simplify Spectre attacks on cross-origin resources.
To mitigate security risks across browsers, SharedArrayBuffers are gated behind cross-origin isolated contexts starting with Chrome 92 (July 2021). To continue using SharedArrayBuffers, please ensure that this page opts-into cross-origin isolation by setting Cross-Origin-Opener-Policy and Cross-Origin-Embedder-Policy appropriately.
Note that for each iframe, only the first issue is reported for performance reasons.
1 violation
Source Location	Trigger	Status
scheduler.development.js:303	Instantiation	warning
Learn more: Enabling SharedArrayBuffer
