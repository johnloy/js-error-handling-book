# Async error handling

The essentially async nature of JavaScript, owing to not wanting to block the event loop, ensures that race conditions will feature prominently in the rogues gallery of bugs web app developers can count on. Race conditions arise from improperly coordinated async code. Trying to troubleshoot race conditions in the absence of good error handing melts your mind.

- silent (aka “swallowed”) exceptions;
- exceptions that aren’t real errors (with a type and stack);
- incoherent criteria for when exceptions should occur and how to identify their type;
- and less-than-useless stack traces.