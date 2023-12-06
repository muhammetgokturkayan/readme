# readme

2acc75e4-694d-444b-83f0-8747d26bc41c/90944238-d9ac-43ec-992b-feb88acc9747

INSERT INTO [Forms_Menu]([title], [hint], [url], [parent], [sira], [userRoles], [form], [ing]) 

	VALUES('Email Arama', 'Gönderilen Maillerin Listesi', 'report/email.aspx', 1, 130, '#kisisel:menuMaillerGörüntüleyebilecekler', NULL, NULL);
 
INSERT INTO [forms_config]([form], [fieldname], [content], [consys], [constart], [conend], [separator], [authorize], [description], [typ], [sep], [roleeskidger], [isEditable], [title], [regex], [yetkili]) 

	VALUES('kisisel', 'menuMaillerGörüntüleyebilecekler', 'Any', NULL, NULL, NULL, NULL, 'S11', 'Sol Menü>Kişisel>Mailler linkini görebilecek kullanıclar', 'R', NULL, NULL, NULL, NULL, NULL, NULL);
 
