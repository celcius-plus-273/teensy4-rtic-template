# TEENSY4-TEMPLATE

Template for a teensy 4.0/4.1 rust embedded project

## main branch usage
1. Follow the instructions under the [Dependencies](https://github.com/mciantyre/teensy4-rs) section and download all required dependencies
2. Connect a Teensy 4.0 or 4.1 board via USB to your PC
3. Use the cargo run command with the appropriate target. For example:
```
cargo run --release --target thumbv7em-none-eabihf
```
4. Don't forget to press the pushbutton on the Teensy board to enter it's programming mode

## rtic branch usage
### Dependencies
1. You'll need to install [nightly rust](https://www.oreilly.com/library/view/rust-programming-by/9781788390637/e07dc768-de29-482e-804b-0274b4bef418.xhtml).

NOTE: If you already have the following dependencies installed (which are also listed under the instructions for the main branch) you'll still need to re-add the llvm-tools-preview. 

2. Follow the instructions under the [Dependencies](https://github.com/mciantyre/teensy4-rs) section and download all required dependencies
3. Connect a Teensy 4.0 or 4.1 board via USB to your PC
4. Use the cargo run command with the appropriate target. For example:
```
cargo run --release --target thumbv7em-none-eabihf
```
5. Don't forget to press the pushbutton on the Teensy board to enter it's programming mode
