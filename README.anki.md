To build binaries for CI, from this folder:

- git submodule update --init 
- cargo install --path .
- cargo install mdbook --version 0.4.21
- cargo install mdbook-toc --version 0.10.0
- cd ~/.cargo/bin
- tar --zstd -cf ~/mdbook.tar.zst mdbook*
