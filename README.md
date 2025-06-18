# 📡 APTECH FIRMWARE (BLUEJAMMER) - Pentest Tools 🔥

![Skema BlueJammer]./(skemabt.png)

> 🚨 **PERHATIAN:**  
> Firmware ini ditujukan untuk **eksperimen edukasi dan pentest** jaringan pribadi. Dilarang digunakan untuk merusak sistem orang lain tanpa izin.

---

## 📥 Download Firmware

- 🔗 [Klik di sini untuk download .bin](./bluejammer.bin)
- Ukuran: ±512KB
- Versi: 1.0.0
- Platform: ESP32 / ESP32U / ESP32S

---

## 🔍 Fungsi & Kegunaan

🛠️ **BlueJammer** adalah firmware pentest untuk pengujian kekuatan sinyal & reaksi perangkat terhadap gangguan jaringan. Dapat digunakan untuk:

- Simulasi serangan wireless
- Uji kekuatan NRF24 terhadap interferensi
- Eksperimen IOT jammer (legal di ruang lab)

---

## 🧰 Daftar Komponen

| Komponen         | Jumlah | Keterangan                          |
|------------------|--------|-------------------------------------|
| 🔌 ESP32U / ESP32S | 1x     | Sebagai otak utama (pengontrol)     |
| 📡 NRF24L01       | 2x     | Modul komunikasi 2.4GHz             |
| 🔋 Baterai BL-5C   | 1x     | Baterai utama                        |
| ⬇️ Step Down      | 1x     | Menyesuaikan voltase ke 3.3V        |
| ⬆️ Step Up        | 1x     | Boost voltase dari 3.7 ke 5V jika perlu |
| 🧯 Elco 100uF 10V  | 2x     | Dipasang di VCC & GND tiap NRF24    |

---

## 🔌 Pemasangan Komponen

🔧 Hubungkan komponen sesuai skema di atas.  
📷 Pastikan posisi elco benar (polaritas), agar modul NRF24 tidak drop.  
💡 Gunakan kabel pendek agar sinyal stabil & tidak ada delay.

---

## 📢 Himbauan Penting

❗ Jangan gunakan alat ini di area publik atau jaringan milik orang lain.  
✅ Disarankan digunakan hanya di mode **offline testing**.  
📚 Pelajari dan gunakan dengan tanggung jawab, seperti **Nethercap** atau tools pentest profesional lain.

---

## 🧪 Testing

- Sudah diuji menggunakan ESP32 Devkit & NRF24 asli
- Daya tahan baterai BL5C sekitar 2–4 jam pemakaian
- Firmware ringan, hanya memakan ~20% dari total flash

---

## 🤝 Credits

- Dibuat oleh: **ARYA25**
- Dibantu AI: ChatGPT
- Terinspirasi dari: Nethercap, Deauther, & ESP32 Tools

---

## 💬 Kontak

📧 WA/Email/Telegram (opsional)  
💻 [GitHub ARYA25](https://github.com/...) *(update linkmu dewe)*
