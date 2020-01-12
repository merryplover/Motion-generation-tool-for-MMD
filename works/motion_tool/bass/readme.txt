⓪doublebass pibox v2D.mid
　DominoからSMF書き出しされたMIDIデータです。これをp-motionに読ませます。
①doublebass pibox v2D_鍵盤右.vmd、doublebass pibox v2D_指_右.vmd
　p-motionから出力されたモーションデータです。～_指_右.vmdの方は使用しません。
②doublebass pibox v2D_鍵盤右.csv
　①のデータを下記のそぼろ氏の「VMD Editor」で変換したものです。
　https://w.atwiki.jp/vpvpwiki/pages/218.html#id_e07bf223
③　②のファイルをベースモーション生成マクロ.xlsで変換します。
　生成するのは以下の4つのファイル。
　SLB200LTD用の右手/左手の2シート→slb200ltd_L.csv,slb200ltd_R.csvという名前で保存。
　時雨さん右手/左手用の2シート→時雨右手.csv,時雨左手.csvという名前で保存。
④時雨ウッドベース01.jpg
　PMXEのプラグインに、マスクザ春原さんの「楽器演奏用ボーン作成プラグイン」を
　追加した状態で、「ぽんぷ長式時雨改二」をPMXEに読み込んで、この画像のように
　設定します。
⑤時雨ウッドベース02.jpg
　https://seiga.nicovideo.jp/seiga/im3825317の「SLB200LTD」と、上記の改造を
　施した時雨さんをMMDに読み込んで、SLB200LTDをこの画像のように親登録します。
⑥時雨さんに「時雨構え191230.vmd」を読み込みます。
⑦slb200ltd_L.vmd、slb200ltd_L.vmdは、SLB200LTDのモーションデータです。
　slb200ltd_L.csv,slb200ltd_R.csvを、VMDエディターで変換して、
　slb200ltd_L.vmd、slb200ltd_L.vmdを作ります。
⑧同様に時雨右手.csv,時雨左手.csvを変換して時雨左手.vmd、時雨右手.vmdを
　作ります。時雨左手.vmd、時雨右手.vmdは時雨さんのモーションデータです。