# readme

/portal/tr/l/e/83ec20b7-4d4d-4c8f-83b6-16c88822afbb/bb48b9a7-6c3a-4ffa-a15b-8a51c38806a1

CREATE TABLE [dbo].[InsertInvoiceKibeleEntegrasyon](
	[id] [int] IDENTITY(1,1) NOT NULL,
	[tarih] [datetime] NULL,
	[form] [varchar](16) NOT NULL,
	[formid] [int] NOT NULL,
	[INVOICE_ID] [varchar](16) NULL,
	[paymentAmount1] [decimal](18, 2) NULL,
	[taxAmount1_KDV] [decimal](18, 2) NULL,
	[taxAmount1_STP] [decimal](18, 2) NULL,
	[taxAmount1_TEV] [decimal](18, 2) NULL,
	[currencyCode1] [varchar](3) NULL,
	[totalAmount1] [decimal](18, 2) NULL
) ON [PRIMARY]
GO
