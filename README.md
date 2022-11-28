# robosys2022

 * ロボットシステム学の授業で用いています.

# このリポジトリの内容について

 * test.bashとgithub/workflowsはプログラムのテスト用.
 * plusについては下記に示してあります. 

# plusについて
![test](https://github.com/ryo0806/robosys2022/actions/workflows/test.yml/badge.svg) 　＊テスト認証の証

 * 本プログラムはsys.stdinを扱っているため, パイプ等の入力に対応しております.
 * このプログラムは数値を足し合わせるプログラムです 
 * 以下使用例
　$ seq 5 | ./plus　　　　　　　　　###整数例
　$ seq 5 | sed 's/$/.1/' | ./plus　###小数例
  

# 使用方法

 * 1.ubuntu22.04.1 LTSをインストール＆ダウンロードする
 * 2.pythonファイルを作成（pythonのversionに注意：下記に動作済みversionを示す）
 * 3.githubのcodeからSSHをコピーする
 * 4.git clone ＜SSH＞を行う
 * 5.確認しディレクトリに入っていれば大丈夫です
 * 6.実行する 

# 必要なソフトウェア
 * 動作確認済み:python 3.7∼3.10

# 動作確認済み環境
 * ubuntu 22.04.1 LTS 

# 権限について 
  * このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます．
  * 詳細はLICENSEをご確認ください

  * © 2022 Ryo Yanagisawa


