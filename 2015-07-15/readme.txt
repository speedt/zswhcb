Ëæ»ú·¢ËÍ100Ìõ

SELECT * FROM m_mobile WHERE id >= 

((SELECT MAX(id) FROM m_mobile)-(SELECT MIN(id) FROM m_mobile)) * RAND() + (SELECT MIN(id) FROM m_mobile)  LIMIT 10000

