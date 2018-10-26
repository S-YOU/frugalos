**エラー時の応答:**

- エラー時の応答形式は[RFC 7807](https://tools.ietf.org/html/rfc7807)に準拠する
- 各エンドポイントで固有の意味を持つ応答ステータスコードに関しては、この文書内で明示的に定義している
- それ以外のエラー応答に関しては、HTTPの一般的なセマンティクスに従い、この文書内で定義することはしない
  - e.g., 応答ステータスが`500`なら、サーバ内部エラー