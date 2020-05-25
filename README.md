# Offline-Continuous-Handwriting-Recognition-Seq2Seq
Jorge Sueiras, Victoria Ruiz, Angel Sanchez, Jose F. Velez, Offline Continuous Handwriting Recognition Using Sequence to Sequence Neural Networks, Neurocomputing (2018), doi: 10.1016/j.neucom.2018.02.008  
  
high-level api from tensorflow 2.0  
Handwriting Recognition  
本科毕设  
1.预处理只实现了文章中的slant_correction部分  
2.bi-LSTM使用concat前后向output做attention部分，不知道是concat还是add更好一些  
3.解码过程中用的cell_state做attention，不知道是用hidden_state还是concat(h_s,c_s)更好一些  
4.py文件由ipynb文件转换格式得来，没有具体分文件实现模块
