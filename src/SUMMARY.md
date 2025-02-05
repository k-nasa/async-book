# Table of Contents

- [初めに](01_getting_started/01_chapter.md)
  - [なぜ非同期？](01_getting_started/02_why_async.md)
  - [非同期Rustの現状](01_getting_started/03_state_of_async_rust.md)
  - [`async`/`.await` 入門書!](01_getting_started/04_async_await_primer.md)
  - [HTTPサーバーを書いてみよう!](01_getting_started/05_http_server_example.md)
- [中身を見てみよう: `Future`と`Task`の実行](02_execution/01_chapter.md)
  - [`Future`トレイト](02_execution/02_future.md)
  - [タスクを起こせ！`Waker`！](02_execution/03_wakeups.md)
  - [エグゼキューターを書いてみよう](02_execution/04_executor.md)
  - [エグゼキューターとシステムIO](02_execution/05_io.md)
- [`async`/`await`再び！](03_async_await/01_chapter.md)
- [pinで固定しよう](04_pinning/01_chapter.md)
- [ストリーーム](05_streams/01_chapter.md)
  - [イテレーションと並行性](05_streams/02_iteration_and_concurrency.md)
- [たくさんのFutureを一度に実行しよう](06_multiple_futures/01_chapter.md)
  - [`join`マクロ](06_multiple_futures/02_join.md)
  - [`select`マクロ](06_multiple_futures/03_select.md)
  - [まだ書けてない: Spawning](404.md)
  - [まだ書けてない: キャンセルとタイムアウト](404.md)
  - [まだ書けてない: `FuturesUnordered`](404.md)
- [Workarounds to Know and Love](07_workarounds/01_chapter.md)
  - [戻り型エラー](07_workarounds/02_return_type.md)
  - [`async`ブロックでの`?`オペレーション](07_workarounds/03_err_in_async_blocks.md)
  - [`Send` Approximation](07_workarounds/04_send_approximation.md)
  - [再帰、再帰、再帰](07_workarounds/05_recursion.md)
  - [Traitsでの`async`](07_workarounds/06_async_in_traits.md)
- [まだ書けてない: I/O](404.md)
  - [まだ: `AsyncRead`と`AsyncWrite`](404.md)
- [まだ: 非同期デザインパターン: 解決法と提案](404.md)
  - [まだ: Modeling Servers and the Request/Response Pattern](404.md)
  - [まだ: Managing Shared State](404.md)
- [まだ: The Ecosystem: Tokio and More](404.md)
  - [まだ: Lots, lots more?...](404.md)
