# Analisis Encoding dan Response

## 1. Case yang Dipilih
Case 2 - User/Mahasiswa API

## 2. Format Data yang Digunakan
Format data yang digunakan adalah JSON.

## 3. Analisis Request GET
### GET 01
**Endpoint:** `/api/users`  
**Tujuan request:** Mengambil daftar semua user.  
**Status code:** 200 OK  
**Analisis response:** Response berisi array/list user. Setiap user memiliki field id, nama, dan email.

### GET 02  
**Endpoint:** `/api/users/1`  
**Tujuan request:** Mengambil detail user berdasarkan ID.  
**Status code:** 200 OK  
**Analisis response:** Response berisi object detail user dengan field id, nama, email.

## 4. Analisis Request POST
### POST 01
**Endpoint:** `/api/users`  
**Tujuan request:** Menambahkan data user baru.  
**Request body:** 
```json
{
  "nama": "Putri Sahira",
  "email": "putri@email.com"
}
