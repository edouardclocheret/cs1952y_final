# CS1952Y FINAL

## How to get started on OSCAR

To use modules (like rust, python, cargo, etc) you may have to load the module.
For example:

```
module load python/3.11
module load rust
```

to get started with bend:

1. make sure the rust module is loaded (this gives you access to the 'cargo' command)
2. `cargo install hvm`
3. `cargo install bend-lang`
4. make sure that cargo binaries are in the system path by adding `export PATH=/users/igordon/.cargo/bin:$PATH` to ~/.bashrc

 
