# security-app-practice

## 概要
COACHTECH 教材 Tutorial 10-6「Webセキュリティ ハンズオン」で作成した成果物です。
（セキュリティを意識したお問い合わせフォームでコントローラー、ルートを作成、セキュリティ対策ができているかを確認しました）

## 使用技術
- PHP 8.x
- Laravel 10.x
- CSRF 保護（`@csrf`）、XSS 対策（Blade の自動エスケープ）

## 学んだこと
- @csrf ディレクティブによる保護
- Bladeの自動エスケープ処理

## 動作確認
http://localhost/contact
で問い合わせフォーム表示、および送信ができる。
また、@csrfを削除すると419 Page Expiredエラーになることを確認
