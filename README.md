# Klasifikasi Batik Menggunakan GLCM dan KNN

Project ini bertujuan untuk mengklasifikasikan batik berdasarkan fitur tekstur. Fitur ini diekstrak menggunakan metode GLCM (Gray Level Co-occurence matrix), yang kemudian akan menjadi inputan pada metode klasifikasi KNN.<br /> <br />
Dataset diambil dari : https://data.mendeley.com/datasets/cx5sr2dgrr/1 <br /><br />
Dataset ini memiliki 60 kelas, namun pada projek ini hanya digunakan 7 kelas saja. Dimana kelas tersebut adalah : ["Gedhangan", "Kawung Nitik", "Sekar Cengkeh", "Sekar Kemuning", "Sekar Liring", "Sekar Menur", "Sekar Randhu"]. Dataset yang ada kemudian diaugment menggunakan library "Augmentor". Proses augmentasi data ini menghasilkan 700 dataset dengan 7 kelas.
