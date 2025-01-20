# IOAM support in Wireshark

## Pre-allocated Trace Option

Support for the IOAM Pre-allocated Trace Option is available in Wireshark since v3.7.0.

## Direct Export

Our patch ([part 1](https://gitlab.com/wireshark/wireshark/-/merge_requests/16848) and [part 2](https://gitlab.com/wireshark/wireshark/-/merge_requests/18740)) has been **merged** in the upstream repository.

However, a new version has **not** been released since then.
Thus, you need to compile from the sources to benefit from our patch.
Please refer to Wireshark's [developer guide](https://www.wireshark.org/docs/wsdg_html_chunked/) for instructions on how to compile depending on your OS.

Once you have compiled Wireshark, you can test the update with the provided example [capture file](./dex.pcap).
