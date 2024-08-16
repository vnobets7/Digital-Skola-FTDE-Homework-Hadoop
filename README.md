![image](https://github.com/vnobets7/Digital-Skola-FTDE-Homework-Hadoop/blob/main/images/logo/Hadoop_logo.jpg)

# Digital-Skola-FTDE-Homework-Hadoop
## Deskripsi Homework
Bagian dari tugas Fast-Track homework, yang merupakan tugas individual. Homework ini bernama "wordcount" menggunakan teknologi apache hadoop.

## Homework Project: "wordcount"
Homework project kali ini, akan menggunakan teknologi hadoop dan hadoop mapreduce untuk melakukan analisa content dalam file bernama "pembukaan_uud1945.txt". Program dibuat dengan menggunakan bahasa java dan python yang dijalankan melalui google collab.

## Project Workflow
<p align='center'><img src="https://editor.analyticsvidhya.com/uploads/46912mapreducepic3.png"/></p>
<br>
Penjelasan dari proses:
- **Splitting**: Pada bagian ini, dilakukan proses pemisahan kata menjadi key dan value. Parameter pemisahan yang digunakan bisa berupa koma atau spasi atau baris baru atau titik koma. <br>
- **Mapper**: Pada bagian ini, sekumpulan data hasil pemisahan diambil untuk dikumpulkan ke dalam blok yang terdiri dari key dan value. <br>
- **Shuffling**: Pada bagian ini, terjadi di satu atau lebih cluster secara paralel. Proses yang terjadi adalah pengumpulan satu atau lebih key yang sama agar nanti mudah untuk dilakukan agregrasi. <br>
- **Reducer**: Pada bagian ini, dilakukan proses agregrasi terhadap nilai key dan value yang sama. <br>
- **Combining**: Pada bagian ini, hasil dari process reducer akan dikumpulkan kembali untuk menunjukan hasil final.  

## Output Project
![image-1](https://github.com/vnobets7/Digital-Skola-FTDE-Homework-Hadoop/blob/main/images/screenshot/hadoop-mapreduce-with-java-output.PNG)
<br>

![image-2](https://github.com/vnobets7/Digital-Skola-FTDE-Homework-Hadoop/blob/main/images/screenshot/hadoop-mapreduce-with-python-output.PNG)
