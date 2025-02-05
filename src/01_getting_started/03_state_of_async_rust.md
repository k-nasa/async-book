# Rust非同期の現状

非同期Rustはエコシステム時間とともに大きく進化してきたため、使うツール、投資するライブラリ、読むべきドキュメントを把握するのは大変です。ただ、標準ライブラリの`Future`トレイトと言語機能の`async` / `await`は最近安定化されました。(パチパチ!) なので、エコシステム全体は新しく安定化されたAPIへの移行の真っ最中で、その後、エコシステムの激しい動きは大幅に解消されます。

しかし現時点では、エコシステムはまだ急速に発展していて、非同期Rustの経験は磨かれていません。ほとんどのライブラリはまだ、`futures`クレートの0.1を使っています。そのため開発者が`futures`0.3と相互運用したければ`compat`クレートの機能を頻繁に使用する必要があります。
また、トレイトメソッド内の`async fn`構文はまだ実装されていなかったり、分かりやすいコンパイルエラーメッセージはまだなかったりします。`async` / `await`言語機能はまだ、新しいからですね。


とは言っても、Rustはパフォーマンスが高く、非同期プログラミングに対して人間工学に基づいたサポートもあります、なのであなたが冒険、探検を恐れないのであれば、Rustの非同期プログラミングの世界に飛び込みましょう！ ダイブ！
