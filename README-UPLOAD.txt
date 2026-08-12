PETA FOLLOW UP - MULTI HEADER V2

Perbaikan V2:
- Tetap membaca header Excel fleksibel.
- Hanya mengambil POLICE_NO, CUSTOMER, MODEL, VIN, SERVICE_ADVISOR, TELEPHONE_CP, RANGKA, ADDRESS.
- Jika di file Excel ada baris ganda dengan record_key yang sama, sistem otomatis mengambil data terakhir dan mengabaikan duplikat.
- Memperbaiki error:
  ON CONFLICT DO UPDATE command cannot affect row a second time

Cara pasang:
1. Extract ZIP.
2. Upload index.html ke root repository GitHub peta-follow-up-baru.
3. Replace index.html lama.
4. Commit changes.
5. Tunggu Vercel deploy.
6. Coba Upload Bulanan lagi.
