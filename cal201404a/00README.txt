# 2014/04/17 H. Akitaya

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

flat_img_b_20140305.fits
flat_img_h_20140317.fits
flat_img_i_20140305.fits
flat_img_j_20140317.fits
flat_img_k_20140317.fits
flat_img_r_20140305.fits
flat_img_v_20140305.fits
flat_sppol_irl_allhwp.fits
flat_sppol_irs_allhwp.fits
flat_sppol_opt_allhwp.fits

 フラット画像(撮像・偏光分光)。
   ※分光、偏光撮像用は未整備
