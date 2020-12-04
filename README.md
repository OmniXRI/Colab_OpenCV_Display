# Colab_OpenCV_Display
如果在Colab中執行OpenCV並顯示影像及視頻，解決imshow, videocapture無法作用問題。

範例程式說明

1. 將欲存取的檔案自行上傳到雲端硬碟(Google Drive)  
2. 掛載自己的Google Drive  
3. 選擇習慣之影像顯示方式  
   方法1.1 透過matplotlib show()顯示  
   方法1.2 透過IPython.display及PIL顯示  
   方法1.3 以Colab自帶cv2_imshow()函式顯示  
4. 選擇習慣之視頻顯示方式  
   方法2.1 透過IPython.display HTML()及base64 b64encode()函式庫顯示視頻  
   方法2.2 利用ffmpeg處理OpenCV VideoWriter()產出視頻播放問題  

請將測試影像、視頻及範例程式 Colab_OpenCV_Display.ipynb 複製到自己的雲端硬碟 Google Drive上，開啟*.ipynb後即可執行。
