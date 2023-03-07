# API Response Documentation Event Sekolah

## Detail Tagihan

```
{
    "data_siswa": [
        {
            "id_siswa": "896867",
            "nama": "Sejuk",
            "kelas": "Kelas Luar Biasa Umum",
            "nama_ayah": "Ayah",
            "nama_ibu": "Ibu",
            "nohape_ayah": "0813332221113",
            "nohape_ibu": "0813332221113"
        },
        {
            "id_siswa": "989777",
            "nama": "Saiph",
            "kelas": "Kelas Luar Biasa Umum",
            "nama_ayah": "Ayah",
            "nama_ibu": "Ibu",
            "nohape_ayah": "0813332221113",
            "nohape_ibu": "0813332221113"
        }
    ],
    "list_tagihan": [
        {
            "id_siswa": "896867",
            "bulan": "Februari",
            "tahun": "2022/2023",
            "id_lembaga": "230300",
            "totaltagihan": "2175000",
            "rekening_lembaga": "352323030000",
            "detailtagihan": [
                {
                    "jumlah": 150000,
                    "status": "belum lunas",
                    "id_tagihan": 347,
                    "nama_kategori": "Biaya Almamater",
                    "id_jenis_tagihan": 97
                },
                {
                    "jumlah": 25000,
                    "status": "belum lunas",
                    "id_tagihan": 348,
                    "nama_kategori": "Kartu Perpustakaan",
                    "id_jenis_tagihan": 98
                },
                {
                    "jumlah": 500000,
                    "status": "belum lunas",
                    "id_tagihan": 349,
                    "nama_kategori": "Buku Paket Pelajaran",
                    "id_jenis_tagihan": 99
                },
                {
                    "jumlah": 500000,
                    "status": "belum lunas",
                    "id_tagihan": 350,
                    "nama_kategori": "Biaya Study Tour",
                    "id_jenis_tagihan": 100
                },
                {
                    "jumlah": 1000000,
                    "status": "belum lunas",
                    "id_tagihan": "SPP-239",
                    "nama_kategori": "SPP Kelas Luar Biasa Umum",
                    "id_jenis_tagihan": "2303001"
                }
            ]
        }
    ]
}
```

## Riwayat Tagihan

```
{
    "list riwayat": [
        {
            "id_siswa": "929278",
            "nama": "Puput Fir",
            "kelas": "1403001",
            "nama_ayah": "Puput Fir",
            "nama_ibu": "081584785287",
            "nohape_ayah": "081584785287",
            "nohape_ibu": "Puput Fir",
            "bulan_bayar": "Februari",
            "tahun_bayar": "2022/2023",
            "kwitansi": "BTS2023022702390985280",
            "created_at": "2023-02-27 14:39:09",
            "detailtagihan": [
                {
                    "jumlah": 20000,
                    "status": "lunas",
                    "id_tagihan": 198,
                    "nama_kategori": "Infaq",
                    "id_jenis_tagihan": 32
                },
                {
                    "jumlah": 3500,
                    "status": "lunas",
                    "id_tagihan": 197,
                    "nama_kategori": "Biaya Pengadaan Sistem",
                    "id_jenis_tagihan": 11
                },
                {
                    "jumlah": 100000,
                    "status": "lunas",
                    "id_tagihan": 192,
                    "nama_kategori": "SPP/UKT I Reguler"
                }
            ]
        }
    ]
}
```
