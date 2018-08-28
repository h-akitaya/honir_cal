# 2014/03/03 H. Akitaya

00README.txt
   このファイル

bpm_20140130.pl (--.fits.gz)
   bad pixel mask ファイル
   (舘内氏作成; [honir_core:2095]参照)

dsmask_030_201402a.pl (--.fits.gz)
   dark spot maskファイル; 撮像flat画像中、感度が30%以下のピクセルを抽出
dsmask_050_201402a.pl (--.fits.gz)
   dark spot maskファイル; 撮像flat画像中、感度が50%以下のピクセルを抽出
    (デフォルトで使用)
dsmask_070_201402a.pl (--.fits.gz)
   dark spot maskファイル; 撮像flat画像中、感度が70%以下のピクセルを抽出
dsmask_all_201402a.pl (--.fits.gz)
   dark spot 全体 maskファイル; 撮像flat画像(smoothing・低次割後)、
   感度が~85%以下のピクセルを抽出してにじませたもの

(*) --.fits.gz ファイルは、--.plをfits形式に戻して圧縮したもの。
    SFITSIO版 hnfixpix で参照する。
