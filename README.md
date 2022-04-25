<h1 align="center">
	<img src="https://static.thenounproject.com/png/3028948-200.png" width="150px"><br>
    Boot Loader written in x86 Assembly.
</h1>

### Dependencies
```
sudo apt install qemu
---------------------
sudo apt install nasm
```
### Compiling
```
nasm -f bin boot.asm -o boot.bin
```
### Running
```
qemu-system-x86_64 boot.bin
```
### Contributions 🎉
###### If you're interested in contributing simply open a pull request!
