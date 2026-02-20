TABLE: STOK_ANA_GRUPLARI

| Column Name | Column Type | Description | Enum Values | Table Reference |
|-------------|------------|-------------|-------------|-------------|
| san_Guid | uniqueidentifier |  |  |  |
| san_create_user | smallint |  |  |  |
| san_create_date | datetime |  |  |  |
| san_lastup_user | smallint |  |  |  |
| san_lastup_date | datetime |  |  |  |
| san_special1 | nvarchar(4) | Özel Alan 1 |  |  |
| san_special2 | nvarchar(4) | Özel Alan 2  |  |  |
| san_special3 | nvarchar(4) | Özel Alan 3 |  |  |
| san_kod | nvarchar(25) | Ana Grup Kodu  |  |  |
| san_isim | nvarchar(50) | Ana Grup Adı  |  |  |

Rules:
- Only the above columns exist.
- Do not invent additional columns.
- Column names are case-sensitive.