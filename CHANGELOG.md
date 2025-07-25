# Changelog

All notable changes to this project will be documented in this file.

This project adheres to [Semantic Versioning](https://semver.org).

<!--
Note: In this file, do not use the hard wrap in the middle of a sentence for compatibility with GitHub comment style markdown rendering.
-->

## [0.1.16] - 2025-07-26

- n3io: `copy`: force flush when reach the end of the input io.

## [0.1.15] - 2025-07-26

- timing-wheel: rollback.
- n3io: add new `copy` func.

## [0.1.14] - 2025-07-26

- timing-wheel: adjust some parameters.

## [0.1.13] - 2025-07-26

- n3io: reactor::time-wheel, remove unnecessary sleep.

## [0.1.12] - 2025-07-25

- timing-wheel: rewrite `TimeWheel`.

## [0.1.11] - 2025-07-25

- n3io: rewrite `Reactor` component.

## [0.1.10] - 2025-07-24

- timing-wheel: fix `self.ticks` update bug.

## [0.1.9] - 2025-07-24

- n3io: change default io_timeout_interval to `200` milliseconds.

## [0.1.8] - 2025-07-24

- n3/n3agent: change default values of quic.

## [0.1.7] - 2025-07-24

- n3/n3agent: fixed a io copy bug.

## [0.1.6] - 2025-07-23

- futures_executor: limits the minimum number of threads to `10`.

## [0.1.5] - 2025-07-23

- n3: set_initial_max_stream_data_bidi_local/set_initial_max_stream_data_bidi_remote bug.

## [0.1.4] - 2025-07-23

- n3/n3agent: adjust default quic parameters.

## [0.1.3] - 2025-07-23

- n3/n3agent: add `max_ack_delay` configuration parameter.

## [0.1.1] - 2025-07-23

- n3io: try to fix lossing close/shutdown event bug.
- n3/n3agent: add more configuration parameters.

## [0.1.0] - 2025-07-21

- First release
