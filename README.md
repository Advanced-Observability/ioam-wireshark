# IOAM support in Wireshark

## Pre-allocated Trace Option

Support for the IOAM Pre-allocated Trace Option is available in Wireshark since v3.7.0.

## Direct Export

Support for [IOAM Direct Export](https://datatracker.ietf.org/doc/rfc9326/) inside Wireshark with the provided [patch](./ioam_dex_wireshark.patch).

### Upstream

We have opened a [merge request](https://gitlab.com/wireshark/wireshark/-/merge_requests/16848) in the upstream repository.

### Apply patch

1) Clone the [official repository](https://gitlab.com/wireshark/wireshark);
2) (Optional) Create a new branch;
3) Copy the [patch](./ioam_dex_wireshark.patch) inside the cloned repository;
4) Apply the patch `git apply ioam_dex_wireshark.patch`;
5) Refer to the official [developper documentation](https://www.wireshark.org/docs/wsdg_html_chunked/ChapterSetup.html) on how to build the modified Wireshark depending on your system;
6) Open the provided example [capture file](./dex.pcap).
