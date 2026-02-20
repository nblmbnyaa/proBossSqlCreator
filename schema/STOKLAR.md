TABLE: STOKLAR

| Column Name | Column Type | Description | Enum Values | Table Reference |
|-------------|------------|-------------|-------------|-------------|
| sto_Guid | uniqueidentifier |  |  |  |
| sto_create_user | smallint |  |  |  |
| sto_create_date | datetime |  |  |  |
| sto_lastup_user | smallint |  |  |  |
| sto_lastup_date | datetime |  |  |  |
| sto_special1 | nvarchar(4) |Özel Alan 1  |  |  |
| sto_special2 | nvarchar(4) |Özel Alan 2  |  |  |
| sto_special3 | nvarchar(4) |Özel Alan 3  |  |  |
| sto_kod | nvarchar(25) |Stok Kodu  |  |  |
| sto_isim | nvarchar(127) |Stok Adı |  |  |
| sto_kisa_ismi | nvarchar(50) |Stok Kısa Adı  |  |  |
| sto_yabanci_isim | nvarchar(127) |Stok yabancı adı  |  |  |
| sto_sat_cari_kod | nvarchar(25) |Tedarikçi Cari Kodu  |  |  |
| sto_cins | tinyint |Stok Cinsi  |0:Ticari Mal 1:İlk Madde 2:Ara Mamül 3:Yarı Mamül 4:Mamül 5:Yan Mamül 6:İşletme Malzemesi 7:Tüketim Malzemesi 8:Yedek Parça 9:Akaryakıt Stok 10:Montaj Reçeteli Mamül 11:Temel Hammadde  |  |
| sto_doviz_cinsi | tinyint |  |  |  |
| sto_detay_takip | tinyint |Detay Takip Şekli  |0:Detay takip yok 1:Parti bazında 2:Parti+lot bazında 3:Seri no bazında 4:Bağ bazında 5:Parti+lot+bağ bazında  |  |
| sto_birim1_ad | nvarchar(10) |  |  |  |
| sto_birim1_katsayi | float |  |  |  |
| sto_birim1_agirlik | float |  |  |  |
| sto_birim1_en | float |  |  |  |
| sto_birim1_boy | float |  |  |  |
| sto_birim1_yukseklik | float |  |  |  |
| sto_birim1_dara | float |  |  |  |
| sto_birim2_ad | nvarchar(10) |  |  |  |
| sto_birim2_katsayi | float |  |  |  |
| sto_birim2_agirlik | float |  |  |  |
| sto_birim2_en | float |  |  |  |
| sto_birim2_boy | float |  |  |  |
| sto_birim2_yukseklik | float |  |  |  |
| sto_birim2_dara | float |  |  |  |
| sto_birim3_ad | nvarchar(10) |  |  |  |
| sto_birim3_katsayi | float |  |  |  |
| sto_birim3_agirlik | float |  |  |  |
| sto_birim3_en | float |  |  |  |
| sto_birim3_boy | float |  |  |  |
| sto_birim3_yukseklik | float |  |  |  |
| sto_birim3_dara | float |  |  |  |
| sto_birim4_ad | nvarchar(10) |  |  |  |
| sto_birim4_katsayi | float |  |  |  |
| sto_birim4_agirlik | float |  |  |  |
| sto_birim4_en | float |  |  |  |
| sto_birim4_boy | float |  |  |  |
| sto_birim4_yukseklik | float |  |  |  |
| sto_birim4_dara | float |  |  |  |
| sto_muh_kod | nvarchar(40) |  |  |  |
| sto_muh_Iade_kod | nvarchar(40) |  |  |  |
| sto_muh_sat_muh_kod | nvarchar(40) |  |  |  |
| sto_muh_satIadmuhkod | nvarchar(40) |  |  |  |
| sto_muh_sat_isk_kod | nvarchar(40) |  |  |  |
| sto_muh_aIiskmuhkod | nvarchar(40) |  |  |  |
| sto_muh_satmalmuhkod | nvarchar(40) |  |  |  |
| sto_yurtdisi_satmuhk | nvarchar(40) |  |  |  |
| sto_ilavemasmuhkod | nvarchar(40) |  |  |  |
| sto_yatirimtesmuhkod | nvarchar(40) |  |  |  |
| sto_depsatmuhkod | nvarchar(40) |  |  |  |
| sto_depsatmalmuhkod | nvarchar(40) |  |  |  |
| sto_bagortsatmuhkod | nvarchar(40) |  |  |  |
| sto_bagortsatIadmuhkod | nvarchar(40) |  |  |  |
| sto_bagortsatIskmuhkod | nvarchar(40) |  |  |  |
| sto_satfiyfarkmuhkod | nvarchar(40) |  |  |  |
| sto_yurtdisisatmalmuhkod | nvarchar(40) |  |  |  |
| sto_bagortsatmalmuhkod | nvarchar(40) |  |  |  |
| sto_sifirbedsatmalmuhkod | nvarchar(40) |  |  |  |
| sto_ihrackayitlisatismuhkod | nvarchar(40) |  |  |  |
| sto_ihrackayitlisatismaliyetimuhkod | nvarchar(40) |  |  |  |
| sto_karorani | float |  |  |  |
| sto_min_stok | float |  |  |  |
| sto_siparis_stok | float |  |  |  |
| sto_max_stok | float |  |  |  |
| sto_ver_sip_birim | tinyint |  |  |  |
| sto_al_sip_birim | tinyint |  |  |  |
| sto_siparis_sure | smallint |  |  |  |
| sto_perakende_vergi | tinyint |  |  |  |
| sto_toptan_vergi | tinyint |  |  |  |
| sto_yer_kod | nvarchar(25) |  |  |  |
| sto_elk_etk_tipi | tinyint |  |  |  |
| sto_raf_etiketli | tinyint |  |  |  |
| sto_etiket_bas | tinyint |  |  |  |
| sto_satis_dursun | tinyint |  |  |  |
| sto_siparis_dursun | tinyint |  |  |  |
| sto_malkabul_dursun | tinyint |  |  |  |
| sto_malkabul_gun1 | bit |  |  |  |
| sto_malkabul_gun2 | bit |  |  |  |
| sto_malkabul_gun3 | bit |  |  |  |
| sto_malkabul_gun4 | bit |  |  |  |
| sto_malkabul_gun5 | bit |  |  |  |
| sto_malkabul_gun6 | bit |  |  |  |
| sto_malkabul_gun7 | bit |  |  |  |
| sto_siparis_gun1 | bit |  |  |  |
| sto_siparis_gun2 | bit |  |  |  |
| sto_siparis_gun3 | bit |  |  |  |
| sto_siparis_gun4 | bit |  |  |  |
| sto_siparis_gun5 | bit |  |  |  |
| sto_siparis_gun6 | bit |  |  |  |
| sto_siparis_gun7 | bit |  |  |  |
| sto_iskon_yapilamaz | bit |  |  |  |
| sto_tasfiyede | bit |  |  |  |
| sto_alt_grup_no | smallint |  |  |  |
| sto_kategori_kodu | nvarchar(25) |  |  |  |
| sto_urun_sorkod | nvarchar(25) | Ürün Sorumlusu Kodu |  | CARI_PERSONEL_TANIMLARI |
| sto_altgrup_kod | nvarchar(25) | Alt Grup Kodu |  | STOK_ALT_GRUPLARI |
| sto_anagrup_kod | nvarchar(25) | Ana Grup Kodu |  | STOK_ANA_GRUPLARI |
| sto_uretici_kodu | nvarchar(25) | Üretici Kodu |  |  |
| sto_sektor_kodu | nvarchar(25) |  |  |  |
| sto_reyon_kodu | nvarchar(25) |  |  |  |
| sto_muhgrup_kodu | nvarchar(25) |  |  |  |
| sto_ambalaj_kodu | nvarchar(25) |  |  |  |
| sto_marka_kodu | nvarchar(25) |  |  |  |
| sto_beden_kodu | nvarchar(25) |  |  |  |
| sto_renk_kodu | nvarchar(25) |  |  |  |
| sto_model_kodu | nvarchar(25) |  |  |  |
| sto_sezon_kodu | nvarchar(25) |  |  |  |
| sto_hammadde_kodu | nvarchar(25) |  |  |  |
| sto_prim_kodu | nvarchar(25) |  |  |  |
| sto_kalkon_kodu | nvarchar(25) |  |  |  |
| sto_paket_kodu | nvarchar(25) |  |  |  |
| sto_pozisyonbayrak_kodu | nvarchar(25) |  |  |  |
| sto_mkod_artik | nvarchar(10) |  |  |  |
| sto_kasa_tarti_fl | bit |  |  |  |
| sto_bedenli_takip | bit |  |  |  |
| sto_renkDetayli | bit |  |  |  |
| sto_miktarondalikli_fl | bit |  |  |  |
| sto_pasif_fl | bit |  |  |  |
| sto_eksiyedusebilir_fl | bit |  |  |  |
| sto_GtipNo | nvarchar(25) |  |  |  |
| sto_puan | float |  |  |  |
| sto_komisyon_hzmkodu | nvarchar(25) |  |  |  |
| sto_komisyon_orani | float |  |  |  |
| sto_otvuygulama | tinyint |  |  |  |
| sto_otvtutar | float |  |  |  |
| sto_otvliste | tinyint |  |  |  |
| sto_otvbirimi | tinyint |  |  |  |
| sto_prim_orani | float |  |  |  |
| sto_garanti_sure | smallint |  |  |  |
| sto_garanti_sure_tipi | tinyint |  |  |  |
| sto_iplik_Ne_no | float |  |  |  |
| sto_standartmaliyet | float |  |  |  |
| sto_kanban_kasa_miktari | float |  |  |  |
| sto_oivuygulama | tinyint |  |  |  |
| sto_zraporu_stoku_fl | bit |  |  |  |
| sto_maxiskonto_orani | float |  |  |  |
| sto_detay_takibinde_depo_kontrolu_fl | bit |  |  |  |
| sto_tamamlayici_kodu | nvarchar(25) |  |  |  |
| sto_oto_barkod_acma_sekli | tinyint |  |  |  |
| sto_oto_barkod_kod_yapisi | barkod_str |  |  |  |
| sto_KasaIskontoOrani | float |  |  |  |
| sto_KasaIskontoTutari | float |  |  |  |
| sto_gelirpayi | float |  |  |  |
| sto_oivtutar | float |  |  |  |
| sto_oivturu | tinyint |  |  |  |
| sto_giderkodu | nvarchar(25) |  |  |  |
| sto_oivvergipntr | tinyint |  |  |  |
| sto_Tevkifat_turu | tinyint |  |  |  |
| sto_SKT_fl | bit |  |  |  |
| sto_terazi_SKT | smallint |  |  |  |
| sto_RafOmru | smallint |  |  |  |
| sto_KasadaTaksitlenebilir_fl | bit |  |  |  |
| sto_ufrsfark_kod | nvarchar(40) |  |  |  |
| sto_iade_ufrsfark_kod | nvarchar(40) |  |  |  |
| sto_yurticisat_ufrsfark_kod | nvarchar(40) |  |  |  |
| sto_satiade_ufrsfark_kod | nvarchar(40) |  |  |  |
| sto_satisk_ufrsfark_kod | nvarchar(40) |  |  |  |
| sto_alisk_ufrsfark_kod | nvarchar(40) |  |  |  |
| sto_satmal_ufrsfark_kod | nvarchar(40) |  |  |  |
| sto_yurtdisisat_ufrsfark_kod | nvarchar(40) |  |  |  |
| sto_ilavemas_ufrsfark_kod | nvarchar(40) |  |  |  |
| sto_yatirimtes_ufrsfark_kod | nvarchar(40) |  |  |  |
| sto_depsat_ufrsfark_kod | nvarchar(40) |  |  |  |
| sto_depsatmal_ufrsfark_kod | nvarchar(40) |  |  |  |
| sto_bagortsat_ufrsfark_kod | nvarchar(40) |  |  |  |
| sto_bagortsatiade_ufrsfark_kod | nvarchar(40) |  |  |  |
| sto_bagortsatisk_ufrsfark_kod | nvarchar(40) |  |  |  |
| sto_satfiyfark_ufrsfark_kod | nvarchar(40) |  |  |  |
| sto_yurtdisisatmal_ufrsfark_kod | nvarchar(40) |  |  |  |
| sto_bagortsatmal_ufrsfark_kod | nvarchar(40) |  |  |  |
| sto_sifirbedsatmal_ufrsfark_kod | nvarchar(40) |  |  |  |
| sto_uretimmaliyet_ufrsfark_kod | nvarchar(40) |  |  |  |
| sto_uretimkapasite_ufrsfark_kod | nvarchar(40) |  |  |  |
| sto_degerdusuklugu_ufrs_kod | nvarchar(40) |  |  |  |
| sto_halrusumyudesi | float |  |  |  |
| sto_webe_gonderilecek_fl | bit |  |  |  |
| sto_min_stok_belirleme_gun | smallint |  |  |  |
| sto_sip_stok_belirleme_gun | smallint |  |  |  |
| sto_max_stok_belirleme_gun | smallint |  |  |  |
| sto_sev_bel_opr_degerlendime_fl | bit |  |  |  |
| sto_otv_tevkifat_turu | tinyint |  |  |  |
| sto_kay_plan_degerlendir | tinyint |  |  |  |
| sto_CRM_sistemine_aktar_fl | bit |  |  |  |
| sto_plu_no | int |  |  |  |
| sto_yerli_yabanci | tinyint |  |  |  |
| sto_mensei | nvarchar(30) |  |  |  |
| sto_oto_parti_lot_kod_fl | bit |  |  |  |
| sto_efat_sinif_kodu | nvarchar(20) |  |  |  |
| sto_efat_sinif_listesi | nvarchar(15) |  |  |  |
| sto_efat_sinif_versiyonu | nvarchar(15) |  |  |  |
| sto_utssisteminegonderilsin_fl | bit |  |  |  |
| sto_posetbeyannamekonusu_fl | bit |  |  |  |
| sto_STT_oncesi_kaldirma | smallint |  |  |  |
| sto_toplam_rafomru | smallint |  |  |  |
| sto_fiyat_kasada_belirlenir_fl | bit |  |  |  |
| sto_franchise_siparis_dursun | tinyint |  |  |  |
| sto_GEKAP | nvarchar(5) |  |  |  |
| sto_GEKAP_birim | tinyint |  |  |  |
| sto_resim_url | nvarchar(127) |  |  |  |
| sto_GEKAP_depozitoonaykodu | nvarchar(10) |  |  |  |
| sto_cabuk_bozulabilen_urun_fl | bit |  |  |  |
| sto_satin_alma_talep_birim | tinyint |  |  |  |

Rules:
- Only the above columns exist.
- Do not invent additional columns.
- Column names are case-sensitive.