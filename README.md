BPMに合わせてreverbやcompressorのmsを設定すると、音が整理されると聞いて作ってみた。

BPMに合わせたvstのmsの計算方法

60000 ÷ BPM = 1拍の長さ（ms）
ex) 150 BPM : 1拍は400 ms、半拍は200 ms

kickみたいにそのままdawに置いて使うaudio sampleの方は長さがそのまま目に見えるからタイミングの計算は簡単だけど、
compressor(+side chain）系やreverbみたいにreleaseのタイミングをmsで設定できるvstを使う時、BPMに合わせて計算しておくと便利

+基本的には、1拍分や半拍分の長さに設定しておくと何となくきれいにできる
