# // ちょっと便利っぽい Grasshopper のスクリプト  


毎日毎日、いつかのどこかの誰かがインターネットに残してくれた情報によって、多大な恩恵を受けていて、そういうものにいつもいつも助けられている。  

最近は、その恩を少しずつでも返していけたらと思っているので、制作の過程で作ったちょっと便利っぽいスクリプトを公開していきたいと思っています。  

それぞれ GitHub の各リポジトリに飛びます。  
ライセンスとか書いてませんがどうぞご自由に。  


### index  

- GenerateCuttingLine-from-UnrolledSurface   


---  

---  


### GenerateCuttingLine-from-UnrolledSurface  

UnrollSurface に自動でのりしろを生成して、レーザー加工用の線データを作成するスクリプト。  
これは、卒制(→)の時に作ったもので、最近綺麗に整理しました。  
レーザーの強さを調整してケガいてで折り線を作るのは調整がシビア過ぎるので、点線です。  

source code と使い方はこちら (→github)

photo

---  


### ReduceMesh-via-ghPython  

ReduceMesh を、ghPython の中で呼び出すスクリプト。  
gh のフローの中で、メッシュの削減ができる。  

source code はこちら (→github)

photo

-


### GrasshopperBake-with-SerialNumber  

K個の数列、UxV個の行列を、連番の名前をつけて、STL に書き出すスクリプト。  
id を振っておかないといけない時に、手でちまちまやりたくないので。  

source code はこちら (→github)  

photo


---  


### Study-makeSurface-gh  

フィギュアのような曲面をいくつか作った時に色々試したもので、今後も使えそうなスクリプト。  

2本のアウトラインのパス間でうまく断面パスを作って Loft して良さげな曲面を作るものと、  
可変半径の Pipe だけで済ましてるものと、あとは、 BoxMorph 的なもの、とりあえず3種類。  

source code はこちら (→github)

photo
