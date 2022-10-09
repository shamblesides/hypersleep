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

Much better :)
