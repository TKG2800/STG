# STG

## フローチャート(FlowChart)

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