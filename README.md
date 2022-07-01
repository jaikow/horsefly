# Horsefly

[![Support Ukraine Badge](https://bit.ly/support-ukraine-now)](https://github.com/support-ukraine/support-ukraine)

Horsefly is a fork of the amazing [Locust](https://github.com/locustio/locust), with the intent of making it fully mitigate Coordinated Omission, either by adding estimated responses post-hoc (similarly to how it's done at [Goose](https://book.goose.rs/coordinated-omission/mitigation.html)) or by making the workers generate requests with a fixed throughput.

The latter should be achievable by a pure python implementation, or, to increase performance, using C-level bindings.

This project is still in very early stages and no meaningful changes have been made yet.

## License

Open source licensed under the MIT license (see _LICENSE_ file for details).
