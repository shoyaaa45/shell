--ヘッダー付きtsv出力コマンド
\copy (select * from m_user) to 'user.tsv' (DELIMITER E'\t', FORMAT csv, HEADER TRUE)
