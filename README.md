# Compile to Web - Language Support

The goal of this project is to see what languages can be compiled into [Web Assembly (WASM)](http://webassembly.org)

## Languages

| Language                  | Compiles to LLVM   | Compiles to WASM   |
|---------------------------|:------------------:|:------------------:|
| [C](C/)                   | :white_check_mark: | :white_check_mark: |
| [C#](C%23/)               | :white_check_mark: | :white_check_mark: |
| [C++](C++/)               | :white_check_mark: | :white_check_mark: |
| [Crystal](Crystal/)       | :white_check_mark: | :question:         |
| [F#](F#/)                 | :question:         | :question:         |
| [Go](Go/)                 | :question:         | :question:         |
| [Haskell](Haskell/)       | :question:         | :question:         |
| [Java](Java/)             | :question:         | :question:         |
| [Julia](Julia/)           | :white_check_mark: | :question:         |
| [Kotlin](Kotlin/)         | :question:         | :question:         |
| [Nim](Nim/)               | :question:         | :question:         |
| [Python](Python/)         | :question:         | :question:         |
| [Rust](Rust/)             | :white_check_mark: | :white_check_mark: |
| [Scala](Scala/)           | :question:         | :question:         |
| [Swift](Swift/)           | :white_check_mark: | :question:         |
| [TypeScript](TypeScript/) | :question:         | :question:         |

### Key

| Icon               | Meaning |
|:------------------:|---------|
| :white_check_mark: | Success |
| :no_entry:         | Broken  |
| :question:         | Unknown |

## Installation

1.  Install [Vagrant](https://www.vagrantup.com/downloads.html)
2.  Install [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
3.  For a desired language `cd` into the folder, then run
``` sh
vagrant up
vagrant ssh
sudo su -
install
build
```

## Contributing

Interested in seeing a new language? Found a bug in the examples?
Check out the [Contributing Guide](CONTRIBUTING.md) for how to get involved!
