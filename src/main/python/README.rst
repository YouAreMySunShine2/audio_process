# 使用python进行音频处理

 1.将不是wav格式的音频转换成wav格式
  song = AudioSegment.from_mp3(path)

  song.export("E:/music/temp/%s%s" % (file_tuple[0], '.wav'), format="wav")

 2.使用wave处理wav音频，进行单声道转双声道

 3.使用song进行加大音量并转换为原始格式
