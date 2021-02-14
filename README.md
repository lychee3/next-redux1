# next-redux1

React.js + Redux.js + Next.jsにおける、ReducerとAction Creatorのサンプルです。<br>
Formから入力したメッセージをReduxのストアで保管し、ストアのデータをリアルタイムに表示します。<br>

![画面](./docs/images/screen.png)


* AddFormコンポーネントとMemoコンポーネントで共有するデータ（今回は入力したメッセージの配列）をReduxのストアで管理する。

* npx create-next-app --example with-redux-thunk next-app で作成した雛形を編集した。

![画面](./docs/images/lifecycle.png)
