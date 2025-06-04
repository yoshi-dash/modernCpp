以下に、研究用計算プログラム作成に役立つ知識を身につけるためのC++学習プランをまとめました。\n\n---\n\n# C++学習プラン（8週間プログラム）\n

## Week 1: モダンC++基礎復習

1. ムーブセマンティクスと右辺値参照（`std::move`, `&&`）
2. スマートポインタ（`std::unique_ptr`, `std::shared_ptr`）
3. `auto`, `constexpr`, 構造化束縛
4. 簡単な演習: `std::vector<double>` に乱数を格納し、平均と分散を計算

> **おすすめ学習方法**
>
> * **書籍**：Scott Meyers『Effective Modern C++』第1〜5章を読み、各項目について自作コードで動作確認
> * **オンラインリファレンス**：cppreference.com で該当機能のドキュメントを参照し、典型的な用例を手でタイピング
> * **動画講座**：CppCon やYouTube上の「Move Semantics in C++11」「Smart Pointers in Modern C++」などを視聴し、要点をノート化
> * **コーディング演習**：小さなサンプルプログラムを自作し、AddressSanitizer や Valgrind で実行時挙動を検証
> * **クイズ形式学習**：Exercism.io の C++ トラックや LeetCode Playground で Modern C++ の短い問題に挑戦

## Week 2-3: テンプレートと数値ライブラリ

1. 関数テンプレート／クラステンプレート基礎
2. 自作 `Vector<T>` クラステンプレート作成（動的確保, `push_back`, `operator[]`, `size`）
3. Eigenライブラリ入門: ベクトル・行列演算
4. Boost.ODEInt を使って調和振動子の常微分方程式を解く

## Week 4: 乱数生成とモンテカルロ

1. `<random>` の分布クラス：`uniform_real_distribution`, `normal_distribution`
2. シード固定による再現性
3. モンテカルロ粒子追跡の小プログラム作成（`Particle` クラスの設計）
4. CSV出力とPython/gnuplotによる結果可視化

## Week 5: CMakeと依存管理

1. CMakeの基本: `CMakeLists.txt` の書き方
2. FetchContentまたはvcpkgによるライブラリ導入
3. プロジェクトひな形作成
4. GitHub連携＋GitHub Actionsでビルドテスト自動化

## Week 6: テストと品質管理

1. Catch2／GoogleTestに触れて単体テストを書く
2. AddressSanitizer／Valgrindでメモリチェック
3. GitHub Actionsでテスト実行を自動化

## Week 7: デバッグ＆プロファイリング

1. GDB／LLDBでステップ実行
2. `perf` または Intel VTune でホットスポット解析
3. コードのボトルネック特定と最適化演習

## Week 8: 小規模シミュレータのリファクタリング

1. GitHub上のシンプルシミュレータをクローン
2. コードを読み解き、モジュール化／クラス設計を改善
3. テストとCIを追加
4. ドキュメント（Doxygen）生成

---
