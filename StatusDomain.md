# Status Domain
## Client Assigned
1. clientHold
    
    Status ini mengizinkan registrar untuk menghapus nama domain dari DNS misal, pembayaran belum diterima dari registrant (user). Status ini tidak mempengaruhi kewenangan pihak registrar untuk melakukan update, transfer, hapus atau renew nama domain. Status ini hanya berpengaruh terhadap nama domain di eksistensi DNS, umumnya domain tidak akan dapat diakses.

2. clientTransferProhibited

    Status ini menginstruksikan Registry untuk menolak semua permintaan dari registrar lain dalam hal mentransfer nama domain ke sponsorship mereka.

3. clientUpdateProhibited

    Status ini menginstruksikan Registry untuk menolak semua permintaan update detil terhadap nama domain oleh Registrar. Tujuan dari ini adalah untuk melakukan “safety lock” terhadap informasi data nama domain sebelum itu dapat diupdate oleh registrar.

4. clientDeleteProhibited

    Status ini sama dengan clientUpdateProhibited, menginstruksikan Registry untuk menolak semua permintaan untuk penghapusan nama domain. Nama domain tetap dapat dihapus oleh registry jika sudah expire.

5. clientRenewProhibited

    Status ini sama dengan status clientUpdateProhibited dan clientDeleteProhibited, menginstruksikan Registry untuk menolak semua permintaan untuk merenew sebuah domain. Nama domain tetap dapat di auto-renew oleh Registry jika domain sudah memasuki waktu expire.


## Server Assigned
1. serverHold

    Status ini mengindikasikan bahwa Registry telah memilih untuk menghapus nama domain dari DNS untuk alasan finansial, legal atau operasional

2. serverTransferProhibited

    Status ini mengindikasikan bahwa Registry akan menolak semua permintaan untuk transfer atau melepas nama domain ke registrar lain.

3. serverUpdateProhibited

    Status ini mengindikasikan bahwa Registry akan menolak semua permintaan untuk melakukan update terhadap nama domain.

4. serverDeleteProhibited

    Status ini mengindikasikan bahwa Registry akan menolak semua permintaan untuk penghapusan nama domain. Status ini terkadang diset oleh Registry untuk pencegahan domain terhapus otomatis.

5. serverRenewProhibited

    Status ini mengindikasikan bahwa Registry akan menolak semua permintaan untuk renew nama domain. Registry terkadang menset status ini untuk alasan teknis dan kebijakan. Nama domain yang mendapatkan status ini akan berubah status menjadi pendingDelete 5 hari setelah waktu expire.

6. pendingDelete/RedemptionPeriod

    Status ini mengindikasikan bahwa Registry telah menerima permintaan untuk penghapusan nama domain, dan domain ini sudah masuk ke jadwal penghapusan dalam siklus domain. Di case tertentu Registrar masih bisa merestore nama domain menggunakan sistem Redemption Grace Period dari Registry.

7. pendingTransfer

    Status ini mengindikasikan bahwa Registry telah menerima permintaan untuk transfer nama domain ke registrar lain, dan permintaan masih dalam proses pending oleh losing registrar.

8. inactive

    Status ini dapat mengandung arti:

        a. nama domain tidak memiliki nameserver

        b. host atau informasi kontak domain tidak terkait ke nama domain (tidak resolve ke domain tertentu)