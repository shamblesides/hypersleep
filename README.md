# hypersleep
Technically does everything that `sleep` does but it is "blazingly fast!"

For example,

```sh
$ time sleep 1

real    0m1.005s
user    0m0.001s
sys     0m0.004s
```

1 whole second to run? So slow!

```sh
$ rustc hypersleep.rs
$ time ./hypersleep 1

real    0m0.002s
user    0m0.002s
sys     0m0.000s
```

Only 0.002 seconds! Three orders of magnitude faster! :rocket:

## How does it work???

Check out [the source code](hypersleep.rs), I think you'll really like it :)
