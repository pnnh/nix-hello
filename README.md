参考Nix官方hello程序的构建示例编写

执行以下命令构建：

```shell
nix-build default.nix
```

官方hello程序构建脚本如下：

https://github.com/NixOS/nixpkgs/blob/nixos-21.11/pkgs/applications/misc/hello/default.nix

需要改下第一行才能编译，编译完成后在result目录有构建后的内容