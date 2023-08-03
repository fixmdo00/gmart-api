![image](https://github.com/fixmdo00/gmart-api/assets/100917455/f947a293-fc7e-425a-b5e3-071f9a9b4951)# gmart-api


# Create Product
API untuk menambhakan produk baru
Request :
- Method = POST
- endpoint = api/product/create
- body =
```json
{
  "id" : "int"
  "nama" : "string"
  "harga" : "int"
  "desk" : "string"
  "foto" : "foto"
  "jumlah" : "int"
}
```

Respon :
```json
{
  "id" : "int"
  "nama" : "string"
  "harga" : "int"
  "desk" : "string"
  "foto" : "foto"
  "jumlah" : "int"
}
```
# Get Product Detail
API untuk mengambil data sebuah produk
Request :
- Method = GET
- Endpoint = api/product/get_detail{id_product}

Respon :
```json
{
  "id" : "int"
  "nama" : "string"
  "harga" : "int"
  "desk" : "string"
  "foto" : "foto"
  "jumlah" : "int"
}
```

# Get product list
API untuk mengambil data list produk
Request :
- Method : GET
- - Endpoint : api/product/get_list{page}{item_per_age}


