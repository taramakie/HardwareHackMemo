# ハードウェアハッキングメモ
## NAND ROM
- OOBとかあるとそのままではアンパックできない
    - 取り出している例
        - https://github.com/meh301/HG8045Q
        - https://www.mnemonic.io/resources/blog/reverse-engineering-an-ev-charger/
    - ツール
        - https://github.com/DigitalSecurity/imx-nand-tools
        - https://github.com/Hitsxx/NandTool

## パッチ差分解析(Patch diffing analysis)
https://onekey.com/blog/patch-diffing-firmware-images/
ブログ記事の内容はパッチ差分解析の方法については触れているが、ツールなどには触れていない。

## バックドアの検証手法
様々な検証手法がまとまっている。
    - https://speakerdeck.com/luminjp/batukudoafalsefa-jian-tojian-zheng

## 脆弱な関数やsemgrepを使った脆弱性の検出方法
Ghidraスクリプトを使って脆弱な関数を検出するスクリプト
Ghidraのデコンパイル結果を関数ごとに吐き出してsemgrepを使って脆弱性を検出する方法
    - https://security.humanativaspa.it/automating-binary-vulnerability-discovery-with-ghidra-and-semgrep/
    - https://github.com/0xdea/ghidra-scripts

## GTFOBins
UnixやLinuxに入っている正規のバイナリでコマンドを実行するための方法が書いてある
- https://gtfobins.github.io/

## PCB解析
Ground planeなどが書いてあるのは珍しい
- https://0x434b.dev/linksys-ea6100_pt1/
- https://0x434b.dev/linksys-ea6100_pt2/
