
- LaravelはPSR-1、PSR-4、PSR-12に準拠すること。
- PSR準拠により、コードの可読性と統一性を確保すること。
- インデントには **4スペース** を使用します。タブは使用しません。
- クラス名: **PascalCase**（例: `UserController`）
- メソッド名: **camelCase**（例: `storeUserData`）
- 変数名: **camelCase**（例: `$userData`）
- 定数名: **大文字スネークケース**（例: `MAX_USERS`）
- ファイル名: クラス名に一致する **PascalCase**（例: `UserController.php`）
- 単一責任の原則に従い、コントローラは1つの責務に集中すること。
- ビジネスロジックはサービス層に分離すること。
- コントローラが肥大化しないようにすること。
- 必要な箇所にはPHPDocコメントを記述する。
- 十分な量のコメントを記述すること
- 不要なコメントは削除すること
- メソッドの引数や戻り値に型宣言を追加すること。
