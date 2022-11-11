# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？

リモートリポジトリとは分散バージョン管理システムのネットワーク上のサーバで運用され、プロジェクトのメインのファイル群を保管及び管理するリポジトリ。

ローカルリポジトリとは分散バージョン管理システムのプロジェクト参画者各々のコンピュータに作成、複製されたリポジトリ。参画者がファイルの編集等を行うために利用される。

## プッシュとマージの違いは何でしょうか？

プッシュとはローカルリポジトリにコミットした内容をリモートリポジトリへ反映させるためのコマンド。同一ブランチ内の変更内容の更新。

マージとは別のブランチの変更内容をマスターブランチに取り込むこと。


## コミットとプッシュの違い

コミットは変更内容をローカルリポジトリ内で保存するためのコマンドのため、変更内容をリモートリポジトリへ反映させるためにはプッシュを行う必要がある。

## コミットのメッセージはどのように書いてあげるのが最適でしょうか？

過去にどのような編集を行ったか確認する際、確認したいログが一目で判るよう編集内容を正確かつ簡潔に記載する。

## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？

ローカルからのマージは編集者が直接マスターブランチへ編集したブランチを反映するが、プルリクエストの場合はプルリクエストを作成後他のプロジェクト参画者へマージを依頼する。

他参画者へマージを依頼することで、変更内容の不備がないか確認することができ、バグの発生を予防することが可能になる。

## コンフリクトを起こしてしまった場合、どう対処すべきですか？

自身の書いたコードとぶつかったコードを記述した他参画者と相談し、取り込む変更内容を決定する。
