2.2 Memahami AWS
Amazon Web Services (AWS) adalah platform layanan cloud yang disediakan oleh Amazon. AWS menawarkan berbagai layanan yang mencakup komputasi, penyimpanan, basis data, jaringan, analitik, pembelajaran mesin, keamanan, dan pengembangan aplikasi. Berikut adalah beberapa poin utama tentang AWS:

Layanan Komputasi: AWS menyediakan layanan komputasi seperti Amazon EC2 (Elastic Compute Cloud), yang memungkinkan pengguna menjalankan server virtual di cloud. AWS Lambda memungkinkan pengguna menjalankan kode tanpa perlu mengelola server, dengan menggunakan model "serverless".

Penyimpanan: AWS menawarkan berbagai solusi penyimpanan, termasuk Amazon S3 (Simple Storage Service) untuk penyimpanan objek, Amazon EBS (Elastic Block Store) untuk penyimpanan blok, dan Amazon Glacier untuk penyimpanan arsip berbiaya rendah.

Basis Data: AWS menyediakan berbagai layanan basis data seperti Amazon RDS (Relational Database Service) untuk basis data relasional, Amazon DynamoDB untuk basis data NoSQL, dan Amazon Redshift untuk data warehousing.

Jaringan: AWS memiliki layanan jaringan seperti Amazon VPC (Virtual Private Cloud), yang memungkinkan pengguna membuat jaringan virtual yang terisolasi secara logis di AWS Cloud, dan Amazon Route 53 untuk layanan DNS yang skalabel.

Keamanan: Keamanan merupakan prioritas utama di AWS. Layanan seperti AWS Identity and Access Management (IAM) memungkinkan pengguna mengelola akses ke sumber daya AWS. AWS juga menyediakan berbagai sertifikasi keamanan dan kepatuhan untuk memenuhi standar industri.

Alat Pengembang: AWS menawarkan berbagai alat untuk pengembang seperti AWS CodeBuild, AWS CodeDeploy, dan AWS CodePipeline untuk mendukung Continuous Integration dan Continuous Delivery (CI/CD).

Pembelajaran Mesin dan AI: AWS memiliki layanan seperti Amazon SageMaker untuk membangun, melatih, dan menerapkan model pembelajaran mesin. Selain itu, terdapat layanan seperti Amazon Rekognition untuk analisis gambar dan video, serta Amazon Polly untuk konversi teks ke ucapan.

Analitik dan Big Data: AWS menawarkan layanan seperti Amazon EMR (Elastic MapReduce) untuk memproses data besar menggunakan kerangka kerja seperti Hadoop dan Spark, serta Amazon Kinesis untuk pemrosesan data streaming secara real-time.

3. Studi Kasus: Menghosting Website di AWS
Untuk menghosting sebuah website di AWS, berbagai layanan dapat digunakan tergantung pada kebutuhan dan skala proyek. Berikut adalah beberapa layanan AWS yang biasa digunakan untuk menghosting website:

Amazon S3: Digunakan untuk meng-hosting website statis. Amazon S3 adalah layanan penyimpanan objek yang memungkinkan Anda menyimpan dan mengambil data dari internet. S3 mendukung hosting website statis, di mana Anda dapat menyimpan file HTML, CSS, dan JavaScript.

Amazon EC2: Jika website Anda memerlukan server aplikasi atau Anda membutuhkan fleksibilitas dalam memilih sistem operasi dan konfigurasi server, Anda dapat menggunakan Amazon EC2. EC2 memungkinkan Anda menyewa server virtual dan mengonfigurasinya sesuai kebutuhan.

Amazon RDS: Jika website Anda memerlukan basis data relasional, Amazon RDS adalah pilihan yang tepat. RDS mendukung berbagai mesin basis data seperti MySQL, PostgreSQL, MariaDB, Oracle, dan SQL Server.

Amazon Route 53: Untuk mengelola DNS dan routing traffic ke website Anda, Amazon Route 53 adalah layanan DNS yang sangat skalabel dan andal.

AWS Lambda: Untuk menjalankan kode tanpa mengelola server, terutama untuk tugas-tugas backend yang tidak selalu aktif, Anda dapat menggunakan AWS Lambda.

AWS CloudFront: Untuk meningkatkan performa website dengan mendistribusikan konten secara global melalui jaringan Content Delivery Network (CDN).

AWS Elastic Beanstalk: Jika Anda menginginkan kemudahan dalam mengelola aplikasi, AWS Elastic Beanstalk memungkinkan Anda untuk mendeploy dan mengelola aplikasi web dengan mudah. Anda hanya perlu meng-upload kode aplikasi, dan Elastic Beanstalk akan menangani detail deployment, termasuk kapasitas provisioning, load balancing, auto-scaling, dan monitoring. 