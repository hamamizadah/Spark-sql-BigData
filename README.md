## Nama      : Muhammad Hamamiy Zadah
## Kelas     : TI - 3C
## No. Absen : 12
##

### Kode 1 
[ mylist, myschema ]
- mylist adalah variabel yang biasanya digunakan untuk menyimpan data dalam bentuk daftar atau array. Sintaks untuk membuat mylist dapat bervariasi tergantung pada bahasa pemrograman yang digunakan.

- myschema adalah variabel yang biasanya digunakan untuk menyimpan struktur atau skema dari suatu data
##

### Kode 2
[ spark.createDataFrame ]
- spark.createDataFrame() adalah metode yang digunakan dalam Apache Spark untuk membuat objek DataFrame baru dari data yang diberikan dalam format tertentu. Metode ini memungkinkan pengguna untuk membuat DataFrame dari berbagai sumber data seperti CSV, JSON, tabel basis data, RDD, dan lainnya.
##

### Kode 3
[ parallelize, toDF ]
- parallelize adalah metode dalam Spark SQL yang digunakan untuk membuat RDD (Resilient Distributed Dataset) dari koleksi yang ada di memori (in-memory collection), seperti list atau array.
- toDF adalah metode dalam Spark SQL yang digunakan untuk mengubah RDD menjadi DataFrame.
##

### Kode 4
[ hadoop, fs, put ]
- hadoop adalah modul dalam Spark SQL yang digunakan untuk berinteraksi dengan Hadoop Distributed File System (HDFS) dan sistem file lainnya yang didukung oleh Hadoop.
- fs adalah modul dalam Spark SQL yang digunakan untuk berinteraksi dengan sistem file secara langsung tanpa melalui Hadoop.
- put adalah sebuah operasi untuk mengunggah file atau objek dari mesin lokal atau virtual ke sistem penyimpanan objek pada PySpark.
##

### Kode 5
[ pyspark.sql, SQLContext, createOrReplaceTempView, show ]
- pyspark.sql adalah modul dalam PySpark yang menyediakan antarmuka untuk bekerja dengan data terstruktur menggunakan DataFrame API atau SQL.
- SQLContext adalah kelas dalam modul pyspark.sql yang digunakan untuk membuat objek SparkSession. SparkSession adalah objek yang dibutuhkan untuk mengakses fitur-fitur Spark SQL seperti membaca data dari sumber eksternal, mengeksekusi query SQL pada data, dan menyimpan hasil query.
- createOrReplaceTempView adalah method dalam DataFrame API yang digunakan untuk membuat view sementara dari DataFrame yang ada. View sementara ini bisa digunakan untuk mengeksekusi query SQL pada DataFrame dengan menggunakan SparkSession.sql().
##

### Kode 6
[ textFile, map, lambda, strip, StructField, StringType ]
- textFile adalah method pada objek SparkContext yang digunakan untuk membaca file teks dalam format Hadoop dan mengembalikan RDD yang berisi baris-baris dalam file tersebut.
- map adalah method pada RDD yang digunakan untuk mengaplikasikan sebuah fungsi pada setiap elemen di dalam RDD, menghasilkan RDD baru.
- lambda adalah sebuah fungsi anonim dalam Python yang dapat didefinisikan dalam satu baris kode.
- strip adalah method pada string yang digunakan untuk menghapus karakter whitespace dari awal dan akhir string.
- StructField adalah kelas dalam modul pyspark.sql.types yang digunakan untuk mendefinisikan kolom dalam schema DataFrame.
- StringType adalah salah satu kelas dalam modul pyspark.sql.types yang digunakan untuk mendefinisikan tipe data string dalam schema DataFrame.
##

### Kode 7
[ spark.read.format, jdbc, options, load ]
- spark.read.format adalah method pada objek SparkSession yang digunakan untuk membaca data dari sumber eksternal dalam berbagai format, seperti CSV, Parquet, JSON, dan lain-lain.
- jdbc adalah salah satu format yang didukung oleh spark.read.format. Format ini digunakan untuk membaca data dari database relasional menggunakan JDBC.
- options adalah parameter opsional pada method jdbc yang digunakan untuk menentukan opsi-opsi koneksi dan pembacaan data dari database, seperti username, password, URL koneksi, dan lain-lain.
- load adalah method pada objek DataFrameReader yang digunakan untuk membaca data dari sumber eksternal dan mengembalikan DataFrame.
##

### Kode 8
[ show ]
-show adalah method pada objek DataFrame pada PySpark SQL yang digunakan untuk menampilkan isi DataFrame. Method ini sangat berguna saat kita ingin melihat data yang terdapat dalam DataFrame.
##

### Kode 9
[ collect, rdd, take ]
- collect adalah method pada objek DataFrame pada PySpark SQL yang digunakan untuk mengumpulkan semua data dalam DataFrame dan mengembalikannya sebagai bentuk list di driver program. 
- rdd adalah singkatan dari Resilient Distributed Datasets, yaitu representasi dasar data pada Spark. RDD adalah koleksi yang terdistribusi dan tahan terhadap kegagalan, yang dapat dipartisi dan didistribusikan di seluruh node pada cluster Spark.
- take adalah method pada objek RDD pada PySpark yang digunakan untuk mengambil sejumlah elemen pertama dari RDD dan mengembalikannya sebagai bentuk list. Method ini berguna ketika kita ingin melihat sebagian data pada RDD untuk melakukan analisis dan debugging.
##

### Kode 10
[ makeRDD, Seq, createDataset ]
- makeRDD adalah method pada objek SparkContext pada PySpark yang digunakan untuk membuat RDD dari kumpulan data yang ada di dalam memory driver program.
- Seq (Sequence) adalah struktur data pada bahasa pemrograman Scala yang digunakan untuk merepresentasikan kumpulan data berurutan dalam bentuk list. Pada PySpark, kita dapat menggunakan Seq sebagai input pada method makeRDD atau createDataFrame untuk membuat RDD atau DataFrame.
- createDataset adalah method pada objek SparkSession pada PySpark yang digunakan untuk membuat Dataset dari kumpulan data yang ada di dalam memory driver program. Dataset adalah API yang lebih baru dan lebih terstruktur daripada RDD atau DataFrame pada PySpark. Dataset merupakan bentuk yang lebih tinggi dari RDD, yang menggabungkan kekuatan RDD dengan kemampuan SQL dan pemrosesan tipe data yang aman.
##

### Kode 11
[ filter ]
- Sintaks filter pada PySpark digunakan untuk memfilter RDD atau DataFrame berdasarkan suatu kondisi atau predikat yang didefinisikan. Fungsi ini memungkinkan kita untuk mengambil subset dari data yang kita perlukan, berdasarkan kondisi tertentu.
##

### Kode 12
[ as, toDF, first ]
- as adalah method pada PySpark yang digunakan untuk memberi alias pada suatu kolom pada DataFrame atau RDD. Dengan memberikan alias pada kolom, kita dapat mengacu pada kolom tersebut dengan nama yang lebih mudah dibaca dan dimengerti
- toDF adalah method pada RDD pada PySpark yang digunakan untuk mengubah RDD menjadi DataFrame. Method ini sangat berguna ketika kita ingin menggunakan fitur-fitur DataFrame pada RDD yang kita miliki.
- first adalah method pada RDD atau DataFrame pada PySpark yang digunakan untuk mengembalikan nilai pertama pada RDD atau DataFrame. Method ini sangat berguna ketika kita ingin melihat nilai pertama dari suatu RDD atau DataFrame, atau ketika kita ingin mengambil satu elemen pertama untuk digunakan dalam perhitungan selanjutnya.
##

### Kode 13
[ listDatabases, listTables, listFunctions, isCached, select ]
- listDatabases() adalah method pada SparkSession yang digunakan untuk mengambil daftar nama database yang ada dalam cluster Spark.
- listTables(databaseName=None) adalah method pada SparkSession yang digunakan untuk mengambil daftar nama tabel yang ada dalam database tertentu atau semua database dalam cluster Spark.
- listFunctions adalah method pada SparkSession yang digunakan untuk mengambil daftar nama fungsi yang tersedia dalam database tertentu atau semua database dalam cluster Spark.
- isCached() adalah method pada RDD atau DataFrame pada PySpark yang digunakan untuk mengecek apakah RDD atau DataFrame tersebut sudah dicache di memori atau belum.
- select(*cols) adalah method pada DataFrame pada PySpark yang digunakan untuk memilih kolom tertentu dari DataFrame.
##

### Kode 14
[ Read, text ]
- Sintaks read dan text pada PySpark digunakan untuk membaca file teks dan mengonversi isi file menjadi RDD (Resilient Distributed Dataset) pada PySpark.
##

### Kode 15
[ load, json, format, printSchema ]
- load adalah method yang digunakan pada objek DataFrameReader untuk membaca data dari berbagai format file dan mengembalikan DataFrame. Method ini memungkinkan kita untuk menentukan format file yang ingin dibaca dan mengatur beberapa opsi saat membaca data.
- json adalah method yang digunakan pada objek DataFrameReader untuk membaca file JSON dan mengonversi isi file menjadi DataFrame.
- format adalah method yang digunakan pada objek DataFrameWriter untuk menentukan format file saat menyimpan DataFrame sebagai file. Format yang didukung oleh PySpark antara lain adalah JSON, CSV, Parquet, dan Avro.
- printSchema adalah method yang digunakan pada DataFrame untuk mencetak schema DataFrame ke konsol.
##

### Kode 16
[ write, save ]
- Sintaks write dan save pada PySpark digunakan untuk menyimpan DataFrame ke dalam format file yang berbeda-beda, seperti CSV, Parquet, dan JSON.
##

### Kode 17
[ parquet ]
- Sintaks parquet pada PySpark dapat digunakan untuk membaca, menulis, dan memproses data dalam format Parquet pada DataFrame.
##

### Kode 18
[ Options, inferSchema, csv, header, codec ] 

Sintaks Options, inferSchema, csv, header, dan codec pada PySpark digunakan untuk membaca file CSV dan mengonfigurasi opsi pembacaan.
- Options: Digunakan untuk mengkonfigurasi opsi pembacaan file CSV. Beberapa opsi yang tersedia adalah delimiter, quote, escape, nullValue, dan dateFormat.
- inferSchema: Digunakan untuk mengambil skema data dari file CSV secara otomatis.
- csv: Digunakan untuk mengidentifikasi format file yang dibaca sebagai file CSV.
- header: Digunakan untuk menentukan apakah baris pertama dalam file CSV berisi header kolom.
- codec: Digunakan untuk mengidentifikasi jenis codec yang digunakan untuk membaca file CSV. Beberapa codec yang didukung adalah UTF-8, ISO-8859-1, dan US-ASCII.

##