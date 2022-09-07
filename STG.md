# STG
<!-- TODO: フロー図(Flow Chart)
<!-- TODO: アクティビティ図(Activity Chart) -->
<!-- TODO: クラス図(Class Chart) -->

### フロー図(Flow Chart)
#### [Main](FlowChart/Main.puml)
<!-- @import "FlowChart/flowchart.puml" -->
#### [FlowChart](FlowChart/flowchart.puml)
#### [開始(Start)](FlowChart/Start)
#### [Settings](FlowChart/Settings)
#### [Setup](FlowChart/Setup)
#### [初期化(Init)](FlowChart/Init)
#### [入力(Input)](FlowChart/Input)
#### [攻撃(Attack)](FlowChart/Attack)
#### [移動(Move)](FlowChart/Move)
#### [レンダリング(Render)](FlowChart/Render)
  - 開始(Start)
    - (初期化)Player.initialize()
    -  (初期化)Enemy.initialize()
  - 更新(Update)
    - 入力(Input())
      - 攻撃(Attack())
      - 移動(Move())
  - レンダリング(Render)
    - Player.Render()
    - Enemy.Render()
#### [Example](FlowChart/example.puml)
<!-- @import "FlowChart\example.puml" -->
### アクティビティ図(Activity Chart)
### クラス図(Class Chart)
