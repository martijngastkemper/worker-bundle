CHANGELOG
=========

1.1.2
-----

 * onShutdown function is now called when worker-limit or memory-limit are reached

1.1.1
-----

 * fix limits (worker-limit /memory-limit) bugs

1.1.0
-----

 * add --memory-limit option.
 * add overridable onException(), onNoWorkload(), onShutdown() functions.
 * add WorkerControlCodes to control execution (continue, stop).
 * add queue management functions on ProviderInterface and AWS SQS (SDK v1/v2) implementation.
 * moved to Bitbucket