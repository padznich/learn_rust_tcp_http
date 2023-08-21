TCP
---

---


#### Run TCP-server

```bash
cargo run -p tcpserver
```
```commandline

   Compiling tcpserver v0.1.0 (/Users/pad/code/learn_rust/scenario1/tcpserver)
    Finished dev [unoptimized + debuginfo] target(s) in 0.74s
     Running `target/debug/tcpserver`
Running on port 3000
```


#### Run TCP-client

```bash
cargo run -p tcpclient
```
```commandline
    Finished dev [unoptimized + debuginfo] target(s) in 0.03s
     Running `target/debug/tcpclient`
Got response from server:"Hello"

```



HTTP server
---

---


#### Run tests

```bash
cargo test -p http
```


#### Run server

```bash
cargo run -p httpserver
```


And check:

    localhost:3000/
    localhost:3000/health
    localhost:3000/api/shipping/orders
    localhost:3000/invalid-path
