# ptj-daily-report-maker
私のアルバイト先の居酒屋では，毎日営業終了後に当日の売り上げや当月の原価率，人件費率を特定のフォーマット（以下，売上報告）にてLINEで報告している．
以下に報告内容を示す．
- 当日の税抜売上
- 当月の税込累計売上
- 当月の税抜累計売上
- 当月の売上予想に対する差額
- 翌日の売上予想額
- 当月の累計税込売上に対する累計食材費の購入費の割合
- 当月の累計税抜売上に対する累計人件費の割合
- 翌日の出勤者名と出勤時刻
- 翌日から1週間の売上予想額

現状の売上報告の作成方法は，前日の売上報告をコピーし，報告事項を電卓で計算しながら書き換えていくというものであるが，時間がかかったりミスが頻発するなどの問題がある．
そこで，売上報告をより短時間で正確に作成することができるwebアプリを作成する．

## 入力
- 前日の売上報告
- 当日の税抜売上
- 当日の食材費
- 当日の人件費
- 翌日の売上予想
- 翌日から1週間の予約人数

## 出力
- 当日の売上報告

# 参考サイト
- [数字からカンマを取り除くparseIntとreplace【JavaScript】](https://web-tsuku.life/remove-comma-parseint-replace/)
