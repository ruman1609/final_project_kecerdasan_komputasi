# Implementasi Klasifikasi Diabetic Retinopathy
Program dari Final Project:
1. Rudy Rachman - 6025222002
2. Zelli Ghea Mardi Anugrah - 6025222014

## Tahap Replikasi
1. Unduh dataset di [Kaggle berikut ini](https://www.kaggle.com/datasets/mariaherrerot/eyepacspreprocess)
2. Ekstrak dan letakkan semua isi file .jpeg dan .csv nya di dalam folder Dataset/1_asli
2.1. Jika folder 1_asli belum ada, harap dibuat terlebih dahulu
3. Jalankan program [Main_Program.m](Entropy_Enhancemnet/Main_Program.m) untuk melakukan tahap preprocessing dari penelitian [Fatima dkk.](https://github.com/ImranNust/DiabeticRetinoPathyDetection), pastikan membuat folder baru di Dataset yaitu 2_0_0_enhanced, agar tidak terjadi error saat proses running program ini.
4. Jalankan program [1_split_image_into_folder](Program/ReferenceUpdated/1_split_image_into_folder.py) untuk melakukan splitting terhadap citra di folder 2_0_0_enhanced ke tiap kelas ke dalam folder, tahap ini akan menciptakan folder baru di Dataset yaitu 2_0_1_splitted.
5. Jalankan program [1_split_normal_without_preprocessing](Program/ReferenceUpdated/1_split_normal_without_preprocessing.py) untuk melakukan splitting terhadap citra di folder 1_asli ke tiap kelas ke dalam folder, tahap ini akan menciptakan folder baru di Dataset yaitu 1_asli_splitted.
6. Untuk proses eksperimen bisa dilihat di [2_training_and_testing_based_on_github](Program/ReferenceUpdated/2_training_and_testing_based_on_github.ipynb).

## Hasil Penelitian
Untuk hasil penelitian bisa dilihat di dalam folder [berikut](Result/2_4_reference_updated).