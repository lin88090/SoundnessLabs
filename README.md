# SoundnessLabs

1.安裝環境(跳出選單時直接按enter跳過

```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

2.運行官方命令文件

```
curl -sSL https://raw.githubusercontent.com/soundnesslabs/soundness-layer/main/soundnessup/install | bash
source ~/.bashrc  # for bash
```

3.安裝CLI環境

```
soundnessup install  # Install the CLI
soundnessup update   # Update to the latest version
```

4.生成密鑰

```
soundness-cli generate-key --name my-key
```
