
# Kamus Data tabel_analitik_pricing
- borough_naik: wilayah penjemputan, string, dari taxi_zone_lookup
- jam_mulai: awal jam dalam timezone New York, datetime, floor per jam
- jumlah_perjalanan: count baris per kelompok, integer, size
- rata_tarif_per_mil: median total_amount / trip_distance, dolar per mil
- rata_kecepatan: median trip_distance / durasi_menit*60, mph
- suhu_c: suhu dari Open-Meteo hourly, celcius, first
- hujan: flag hujan_mm>0.1, 0/1, max per jam
