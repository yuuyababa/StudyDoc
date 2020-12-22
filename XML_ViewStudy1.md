# Androidstudio画面作成について


Textでの記述をここに示す。      
以下のつがある.         
* LinerLayout
* RelativeLayout

今更聞けない**layout_width/height**
***
画面の横幅、縦幅を設定する項目
|プロパティ|説明|
|:---|:---|
|wrap_content|中身を表示するのに十分な分|
|match_parent|親のサイズめいっぱい|


## LinerLayout
配置されたコンポーネントを一定の方向に並べる時に使う。
プロパティのOrientationで並べる方向を変えられる。
  |横方向|縦方向|
  |:---|:---|
  |Vertical|horizontal|

  *コンポーネント(component) : 部品の意味。レイアウトに作成したオブジェクトたち



## RelativeLayout
配置されたコンポーネントを他のコンポーネントと相対的に配置するレイアウト。      
コンポーネント同士の配置関係を崩さないように移動ができる。

## プロパティ
以下にRelateiveLayoutの配置に関するプロパティを示していくかもしれない

|プロパティ名|どういう奴|入る値|
|:----|:----|:----|
|layout_alignParentTop|ビューの上端が親の上端と一致するように配置|true or false|
|layout_centerVertical|子が親の中心に配置される|true or false|
|layout_below|指定したidのビューの下に配置される。|@id|
|layout_toRightOf|指定したidの右側に配置される。|@id|
|layout_centerHorizontal|横の要素で中央に配置される。|true|
