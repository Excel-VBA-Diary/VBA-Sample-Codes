Win32APIを利用した高速ファイル検索VBAクラスの実装
VBAによるファイル検索は通常FSO(FileSystemObject)またはDirを利用する。
ここではWin32API（FindFirstFile FindFirstFileEx FindNextFile）を利用した自作クラスを紹介する。

FileInfomation Class：検索したファイルの情報を構造体として扱うクラス
FileSearchByAPI Class：指定されたフォルダ配下のファイルを検索するクラス
Test Code：標準モジュールに実装するテスト用コード
