# TABLE RELATIONSHIPS

------------------------------------------------------------
RELATIONSHIP 1
------------------------------------------------------------

Parent Table: STOK_ANA_GRUPLARI
Child Table: STOKLAR
Relationship Type: Single-Column 1-N

Column Mapping:
| Parent Column | Child Column |
|---------------|-------------|
| san_kod | sto_anagrup_kod |

Join Rule:
ON STOK_ANA_GRUPLARI.san_kod = STOKLAR.sto_anagrup_kod

------------------------------------------------------------
RELATIONSHIP 2
------------------------------------------------------------

Parent Table: STOK_ALT_GRUPLARI
Child Table: STOKLAR
Relationship Type: Composite 1-N

Column Mapping:
| Parent Column | Child Column |
|---------------|-------------|
| sta_anagrup_kod | sto_anagrup_kod |
| sta_kod | sto_altgrup_kod |

Join Rule (ALL columns must be used together):
ON  STOK_ALT_GRUPLARI.sta_anagrup_kod = STOKLAR.sto_anagrup_kod
AND STOK_ALT_GRUPLARI.sta_kod        = STOKLAR.sto_altgrup_kod

------------------------------------------------------------
RELATIONSHIP 3
------------------------------------------------------------

Parent Table: STOK_ANA_GRUPLARI
Child Table: STOK_ALT_GRUPLARI
Relationship Type: Single-Column 1-N

Column Mapping:
| Parent Column | Child Column |
|---------------|-------------|
| san_kod | sta_anagrup_kod |

Join Rule:
ON STOK_ANA_GRUPLARI.san_kod = STOK_ALT_GRUPLARI.sta_anagrup_kod


GLOBAL RULES:
- Only the relationships defined above exist.
- Do not assume ID-based joins.
- Do not invent alternative join keys.
- For composite relationships, ALL listed columns must be used together.
