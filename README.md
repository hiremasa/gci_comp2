# gci_comp2
<br><br><br>
inputディレクトリにはGCI上のデータを3つ入れる<br>
notebookディレクトリにあるipynbをtreeに書いてある上から実行すれば正しく動くと思います<br>
xfeat_homecredit.ipynbはダウンロードしてKaggleのKernel上で行ってください<br><br>
<br>
input<br>
┣train.csv<br>
┣test.csv<br>
┗sample_submission.csv<br>
<br>
notebook<br>
┣xfeat_homecredit.ipynb<br>
┣Additional_FE.ipynb<br>
┣Null_importance.ipynb<br>
┣Bayes_parameter.ipynb<br>
┣LightGBM.ipynb<br>
┣XGBoost.ipynb<br>
┗submission.ipynb<br>
<br>
features<br>
┣feature_num_features.ftr<br>
┣feature_arithmetic+_combi2.ftr<br>
┣feature_arithmetic-_combi2.ftr<br>
┣feature_arithmetic*_combi2.ftr<br>
┣feature_arithmeticdiv_combi2.ftr<br>
┣train_test_7th_df.ftr<br>
┣train_test_oliverFE_df.ftr<br>
┣feature_1way_label_encoding_with_te.ftr<br>
┣feature_2way_label_encoding_with_te.ftr<br>
┣feature_3way_including_CODE_GENDER_label_encoding_with_te.ftr<br>
┣feature_round_num_label_encoding.ftr<br>
┣github_feature2.fhr<br>
┣actual_imp_df.csv<br>
┗null_imp_df.csv<br>
<br>
submission<br>
┣beyas226feat_5fold_LGBM.csv<br>
┣226feat_5fold_seed1001_XGB.csv<br>
┗XGB_LGBM.csv<br>
<br>
<br>XGB_LGBM.csv is the final submission
