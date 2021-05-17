# Documentation
This repository is one of the demos of the code in [Rust MaxMind DB Reader](https://github.com/oschwald/maxminddb-rust)
and main.rs uses [lookup.rs in the repository](https://github.com/oschwald/maxminddb-rust/blob/main/examples/lookup.rs)

# How to use
0. If you have not installed Rust language yet, follow the instructions [here](https://www.rust-lang.org/ja/tools/install) to install the Rust lang.
1. Download the GeoLite2 ASN from [this page](https://www.maxmind.com/en/accounts/553251/geoip/downloads) and put `GeoLite2-City.mmdb` in `/data/` directory.
2. clone this repository and run the following(aaa.bbb.ccc.ddd means a IP address)
```
$ git clone https://github.com/RyosukeNAKATA/ip2city_rust_demo.git
$ cd ip2city_rust_demo
$ cargo run data/GeoLite2-City.mmdb aaa.bbb.ccc.ddd
```
3. For example, the output might look like this.
![img](/img/sample.png)


# License
This is free software, licensed under the ISC license.