# Dataset

Folder ini berisi dataset yang digunakan dalam proyek **Goat Sales Data Engineering Pipeline**.

## Dataset

| File | Deskripsi |
|------|-----------|
| Data_Transaksi_Updated3.csv | Data transaksi penjualan kambing yang digunakan sebagai sumber utama analisis. |
| Master_Kambing.csv | Data master yang berisi informasi mengenai jenis dan karakteristik kambing. |
| Master_Pembayaran.csv | Data metode dan status pembayaran pelanggan. |
| Master_Pembeli.csv | Data pelanggan yang digunakan untuk analisis segmentasi pembeli. |

## Data Source

Dataset digunakan sebagai data operasional (OLTP) yang diproses melalui pipeline ETL menggunakan Pentaho sebelum dimuat ke PostgreSQL untuk proses analitik.

## Data Processing

Dataset melalui beberapa tahapan pengolahan, antara lain:

- Data Cleansing
- Data Validation
- Data Transformation
- Data Integration

Seluruh dataset digunakan hanya untuk keperluan pembelajaran dan pengembangan proyek Data Engineering.
