# rab23_stepper

Controller Boardでステッピングモーターを動かす用のコード。BluePill STM32F103C8用

ステッピングを2つ動かせてお互い逆方向に回転します。速度を変えたい場合はiocファイルをいじってください。

STARTボタンを押してenable、STOPボタンを押すとdisableになります。

UP、DOWN(十字キー)で操作する感じです。
